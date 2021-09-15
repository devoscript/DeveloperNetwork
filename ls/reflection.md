# Reflection

## Reference Equality

A type may overload the equality operator. In that case it is useful to implement the method `Reflect.RefEq(a, b)`.

## Constructor

- `Reflect.Construct(t, argumentsList)` may be used instead of `New T` where `T` is a dynamic reference.