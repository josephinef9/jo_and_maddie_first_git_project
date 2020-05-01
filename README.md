# My 4 Favorite Ruby methods

### `.to_a`
method converts a range to an array
```ruby 
(1..10).to_a #=> [1, 2, 3, 4, 5, 6, 7, 8, 9, 10]
```

### `.each`
method iterates over each element of an array followed by a block of code
```ruby 
array= ["puppies", "doggies", "doggos"]
array.each {|dog| puts"type of #{dog}"} 
type of puppies
type of doggies
type of doggos
#=> ["puppies", "doggies", "doggos"]
```

### `.length`
method returns how many indiviual x's are in one y; can be used on an array or string
```ruby 
array= ["puppies", "doggies", "doggos"]
array.length #=> 3
```
### `.times`
method runs loop specific number of times 
```ruby
5.times {puts "Hello!"} 
Hello!
Hello!
Hello!
Hello!
Hello!
#=>5
```
