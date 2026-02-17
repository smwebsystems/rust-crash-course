# Day 1 - Introduction, Toolchain, and "Hello, World!"

## [YouTube](https://youtu.be/X-wSwAVbuSY)
## [Slides](https://tinyurl.com/yvrvjvch)

## 1. The "Why" of Rust
* **Speed vs. Safety:** Rust bridges the gap by offering the raw performance of C++ with the memory safety of Java (without relying on a garbage collector).
* **Web3 Integration:** Major networks like Solana, Polkadot, and Arbitrum Stylus rely on Rust because its strict compiler prevents catastrophic, system-breaking bugs in smart contracts.

## 2. Understanding the Toolchain
* `rustup`: The official installer and toolchain manager.
* `rustc`: The core Rust compiler (translates your Rust code into machine code).
* `cargo`: Rust’s official package manager and build system. You will use this tool for almost everything in your Rust career.

## 3. Environment Setup
* **Install Rust:** Use the terminal command provided on the [official Rust website](https://www.rust-lang.org/tools/install).
* **Verify Installation:** Run `rustc --version` and `cargo --version` in your terminal.
* **IDE Setup:** Download VS Code and install the **rust-analyzer** extension for live error checking, formatting, and autocompletion.

## 4. Your First Project
Creating a project from scratch is made simple with Cargo.
* **Initialize:** Run `cargo new hello_world` in your terminal. This generates a `Cargo.toml` (your project's configuration manifest) and a `src/main.rs` file.
* **The Anatomy of `main.rs`:**
  * `fn main() { ... }`: The entry point of every Rust executable.
  * `println!("Hello, World!");`: A Rust macro (denoted by the `!`) used to print text to the console.

## 5. Essential Cargo Commands
* `cargo check`: Quickly checks your code for errors without doing the heavy lifting of compiling an executable.
* `cargo build`: Compiles your code and places the unoptimized binary in `target/debug/`.
