# Experiment

A simple Rust project that prints "Hello, world!".

## Project Structure

```
experiment/
├── src/
│   └── main.rs      # Main application entry point
├── Cargo.toml       # Project manifest
└── README.md        # This file
```

## Building and Running

To build the project:

```bash
cargo build
```

To run the project:

```bash
cargo run
```

## Development

This project uses Rust 2021 edition and can be developed using any Rust-compatible IDE. The project includes VSCode debugging configuration in `.vscode/launch.json` for easy debugging with the CodeLLDB extension.

### VSCode Debugging

1. Install the "CodeLLDB" extension in VSCode
2. Open the project in VSCode
3. Press F5 or select "Debug Experiment" from the Run and Debug menu

### Requirements

- Rust toolchain (2021 edition)
- Cargo (Rust's package manager)
