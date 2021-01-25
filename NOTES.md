# Notes/Summary

Default arguments are easy to add, you simply assign them a default value with `=` ("equals") in the argument list. There's no limit to the number of arguments that you can make default.

```ruby
def greeting(name="Ruby programmer", language="Ruby")
  puts "Hello, #{name}. We heard you are a great #{language} programmer."
end
```

It is possible to define a method that takes in both required and default arguments. To do so, however, we must place the default argument at the end of the argument list in the method definition. 