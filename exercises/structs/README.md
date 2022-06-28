# Structs

Rust has three struct types: a classic C struct, a tuple struct, and a unit struct.

```rust
// a classic C struct
struct Person {
  name: String,
  age: u32,
}

// a tuple struct
struct Distance(i32);


// a unit struct
struct Hello;
```

## Further information

- [Structures](https://doc.rust-lang.org/book/ch05-01-defining-structs.html)
- [Method Syntax](https://doc.rust-lang.org/book/ch05-03-method-syntax.html)
