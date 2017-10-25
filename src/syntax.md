# Syntax

## Function Invocation

A function may be invoked with or without parentheses: 

```ruby
a.range?(b,c)
a.range? b, c
```


## Variables

Overview: http://strugglingwithruby.blogspot.dk/2010/03/variables.html

### Local Variables

`user` is a local variable and exists only within the current block

### Instance Variables

`@user` or `self.user` is an instance variable that belongs to one instance of a class

`@user` to define the instance variable


### Class Variables

`MyClass.var` A class variable belongs to any instance of a class and is accessible from any instance. 
They have protected access outside of the class

`@@var` defines the class variable


### Global Variables

`$var` is a global variable and is accessible by any class, instance, or scope. 


### Special Variables

`self`    # "this" in Java, etc.
`true`
`false`
`nil`      # "null" in Java, etc., also counts as false
`__FILE__` # the current file
`__LINE__` # the current line number.


## Operators

### `a ||= b`  Double Pipe Equals

Double pipe equals equates, functionally, to the expression: `a || a = b`.  It's just a shorthand syntax. 
