# sway-test-rs

A cargo-generate template that makes it easy to create integration tests for
Rust + Sway projects.

This template is designed for Rust developers who wish to test integration of
their Rust application and Sway code.

## Usage

With [Rust installed][rust-installation]:

1. Install the `cargo generate` command.
   ```
   cargo install cargo-generate
   ```

2. Generate your integration tests.
   ```
   cargo generate https://github.com/fuellabs/sway-test-rs
   ```
   The cargo generate command will prompt you for a project name along with some
   other details before initialising a new repository containing your generated
   integration testing crate.

[rust-installation]: https://www.rust-lang.org/tools/install