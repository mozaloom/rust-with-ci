# Rust with CI

[![Build binary release](https://github.com/mozaloom/rust-with-ci/actions/workflows/release.yml/badge.svg)](https://github.com/mozaloom/rust-with-ci/actions/workflows/release.yml)
[![Rustfmt](https://github.com/mozaloom/rust-with-ci/actions/workflows/rustfmt.yml/badge.svg)](https://github.com/mozaloom/rust-with-ci/actions/workflows/rustfmt.yml)
[![Tests](https://github.com/mozaloom/rust-with-ci/actions/workflows/tests.yml/badge.svg)](https://github.com/mozaloom/rust-with-ci/actions/workflows/tests.yml)
[![Clippy](https://github.com/mozaloom/rust-with-ci/actions/workflows/lint.yml/badge.svg)](https://github.com/mozaloom/rust-with-ci/actions/workflows/lint.yml)

This repository demonstrates how to set up Continuous Integration (CI) for a Rust project using GitHub Actions.

## Getting Started

To initialize a new Rust project, run the following command:

```bash
cargo init --name trust
```

This will create a new Rust project named `trust`.

## CI Workflows

This repository includes the following GitHub Actions workflows:

- **Build binary release**: Builds and releases the binary.
- **Rustfmt**: Ensures the code is formatted according to Rust's style guidelines.
- **Tests**: Runs the test suite to ensure code correctness.
- **Clippy**: Lints the code to catch common mistakes and improve code quality.

## Badges

The badges above provide a quick overview of the status of each workflow.

## Contributing

Feel free to open issues or submit pull requests to improve this project.

## License

This project is licensed under the [MIT License](LICENSE)