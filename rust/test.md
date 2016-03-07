# test

`test/main.rs`:
```rust
# crate name has to exist in Cargo.toml in root
extern crate adder;

#[test]
fn it_works() {
    assert_eq!(4, adder::add_two(2));
}
```

With `test/main.rs` do:
```sh
$ cargo test
```
- [rustbook/testing](https://doc.rust-lang.org/book/testing.html)