## what is the difference between a statement and an expression?
[[statements]] make some changes or give instructions to the interpreter
[[expressions ]] resolve to / return a value

2+2 is an expression

x = 7 is an expression (this is an expression because y = x = 7 => the value is being returned)

## when is an expression a statement?
an expression is also a statement when it gives the interpreter an instruction or changes its state. so you have function expressions 
```js
() => {}
```
and you have function declarations which are statements
```js
function myFunc (){}
```

## when is an expression not a statement?
an expression is not a statement when

[[software]]

if, while, for, const are statements because they give instructions to the interpreter