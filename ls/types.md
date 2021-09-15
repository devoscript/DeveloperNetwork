# Types

## Null

Null is the only type indicating absence of value. The three literals `Empty`, `Nothing` and `Null` all produce the same value, `Null`, however each literal has its own compile-time symbol.

In particular:

- The following conditions hold: `Empty = Null` and `Nothing = Null`.
- When code documentation is generated, a constant is printed as is. For instance, `SomeProperty = Empty` and `Sub Fn(Opt = Nothing)`.
- `CType(Empty, AFlagsEnum)` converts the `Empty` constant into an `AFlagsEnum` instance.