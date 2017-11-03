# units.rs

## Example
experimental

### Plan 1

```rust
let angstrom: Angstrom = "1.0".parse()?;
assert_eq!(angstrom.magnitude, 1.0e-10);
```

### Plan 2

```rust
let parser = Parser();
let angstrom: f64 = parser.parse::<Angstrom>("1.0")?;
assert_eq!(angstrom, 1.0e-10);
```

### Plan 3

```rust
```
