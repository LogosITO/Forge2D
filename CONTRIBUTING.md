# Contributing to Forge2D

First off, thank you for considering contributing to Forge2D! We welcome contributions from everyone, whether it's a bug report, a feature suggestion, or a pull request.

## Code of Conduct

This project adheres to the [Rust Code of Conduct](https://www.rust-lang.org/policies/code-of-conduct). By participating, you are expected to uphold this code. Please report unacceptable behavior to the project maintainers.

## How Can I Contribute?

### Reporting Bugs

- Ensure the bug was not already reported by searching on GitHub under [Issues](https://github.com/LogosITO/forge2d/issues).
- If you're unable to find an open issue addressing the problem, [open a new one](https://github.com/LogosITO/forge2d/issues/new). Be sure to include a **title and clear description**, as much relevant information as possible, and a **code sample** or an **executable test case** demonstrating the expected behavior that is not occurring.

### Suggesting Enhancements

- Open a new issue with a clear title and detailed description.
- Explain why this enhancement would be useful to most users.
- If possible, provide a rough sketch of the implementation.

### Pull Requests

1. Fork the repository and create your branch from `main`.
2. If you've added code that should be tested, add tests.
3. Ensure the test suite passes.
4. Make sure your code lints (`cargo clippy`) and is formatted with `rustfmt`.
5. Issue that pull request!

## Development Setup

1. Make sure you have [Rust](https://rustup.rs/) installed (nightly or stable, we recommend stable).
2. Clone your fork:
   ```bash
   git clone https://github.com/LogosITO/forge2d.git
   cd forge2d

    Build the project:
    bash

    cargo build

    Run tests:
    bash

    cargo test

    Run an example:
    bash

    cargo run --example basic_window

## Coding Guidelines

Rustfmt: Always run cargo fmt before committing.

Clippy: Your code should not produce warnings when running cargo clippy. We recommend using cargo clippy -- -D warnings to enforce this.

Documentation: Public items (functions, structs, etc.) must be documented with /// comments. Consider adding examples in doc comments where helpful.

Testing: Write unit tests for new functionality. Place integration tests in the tests/ directory.

Commits: Write clear and concise commit messages. The first line should be a short summary (50 chars or less), optionally followed by a blank line and a more detailed description. Reference issue numbers if applicable.

## Style Guide

Follow the Rust API Guidelines.

Use snake_case for functions and variables, CamelCase for types, SCREAMING_SNAKE_CASE for constants.

Prefer Result<T, E> over panicking when errors are recoverable.

For error types, consider using thiserror or creating custom enums.

## License

By contributing to Forge2D, you agree that your contributions will be licensed under the MIT License (as specified in the LICENSE file).
Questions?

Feel free to open an issue with the label "question" or contact the maintainers directly.

Thank you for helping make Forge2D better! 🚀
