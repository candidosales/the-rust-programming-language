# The Rust Programming Book

https://doc.rust-lang.org/

## 📝 Notes

### Chapter 1

- `cargo check`: https://doc.rust-lang.org/book/ch01-03-hello-cargo.html

### Chapter 2

- Rust prelude: https://doc.rust-lang.org/std/prelude/index.html
- In Rust, variables are immutable by default, meaning once we give the variable a value, the value won’t change.

```rust
let apples = 5; // immutable
let mut bananas = 5; // mutable
```

- Result’s variants are `Ok` and `Err`. The `Ok` variant indicates the operation was successful, and inside `Ok` is the successfully generated value. The `Err` variant means the operation failed, and `Err` contains information about how or why the operation failed.
- Another neat feature of Cargo is that running the `cargo doc --open` command will build documentation provided by all your dependencies locally and open it in your browser.
- A `match` expression is made up of arms. An arm consists of a pattern to `match` against, and the code that should be run if the value given to `match` fits that arm’s pattern.
