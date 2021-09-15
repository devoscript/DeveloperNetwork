# Expressions

## Lambda

Either `Function` or `Sub` keyword can be used for lambdas, followed by explicit parentheses and body.

```
Let GreetFn = Sub(s) Print("Greetings, " & s & "!")
GreetFn "world"
```

## Operators

- `Or`: if operands are neither numeric or Boolean, then it selects a reference (e.g. `List?.Map(...) Or {}`).
- `If`: `If(condition, arg1, arg2)`
- `ClosureOf m` results in method reference.
- Comparison `x <> y` is the reverse of `x = y`. `IsNot` and `Is` are equivalent operators.

## Dictionary initializer

```
D = {
    SomeField = 10,
    AnotherField = 10,
}
' with prefix
D = D{}
D = M{}
```

## Collection initializer

Use the `#` character followed by curly braces (`#{}`) to initialize a Collection:

```
L = #{ V1, ...S, }
' prefixes other than #
L = C{}
L = L{}
L = A{}
```