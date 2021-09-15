# Enumerations

## Flags Operations

- `E.Variant1 + E.Variant2`: include Variant2
- `E.Variant1 - E.Variant2`: exclude Variant2
- `CType(Empty, E)`: empty
- `SomeFlags.Toggle(E.Variant1)`
- `SomeFlags.Filter(E.Variant1 + E.Variant2)`
- `SomeFlags.Has(E.Variant1)`