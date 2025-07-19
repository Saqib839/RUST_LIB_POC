# Simple Rust Library

This is a minimal Rust library project that demonstrates how to define, test, and use a simple public function in a Rust crate. It serves as a proof of concept for creating and publishing a reusable Rust library.

## ✨ Features

- Exposes a simple `add(left, right)` function
- Includes basic unit testing using Rust's built-in test framework
- Designed as a starting point for more complex Rust libraries

## 📦 Usage in project

Add this crate as a dependency in your `Cargo.toml` (if published):

```toml
[dependencies]
simple_rust_library = "0.1.0"

use simple_rust_library::add;
fn main() {
    let sum = add(2, 3);
    println!("Sum is: {}", sum);
}

