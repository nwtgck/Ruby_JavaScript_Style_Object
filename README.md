# Ruby_JavaScript_Style_Object

### How to use
```rb
  require './js_obj'
```

### How it works
```rb
require './js_obj'

user = {
  name: 'user1',
  position: {
    x: 15,
    y: 0
  }
}

# Read
puts user.name #=> user1
puts user.position.x #=> 15

# Add new property
user.age = 10
puts user.age #=> 10

user.position.z = 22
puts user.position.z #=> 22
  
```
