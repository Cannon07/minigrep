# MiniGrep: A Command Line Search Tool

MiniGrep is a command line search tool inspired by the classic `grep` command, designed and implemented in Rust. This tool allows users to search for specific strings within files, making it efficient, fast, and cross-platform.

## Features

- **Efficient Search**: Quickly locate strings within files.
- **Cross-Platform**: Works seamlessly on various operating systems.
- **Single Binary Output**: A standalone executable for easy deployment and use.

## Getting Started

### Installation

To use MiniGrep, you need to have Rust installed. If you haven't installed Rust yet, you can get it from [Rust's official website](https://www.rust-lang.org/tools/install).

Once Rust is installed, you can build the project using Cargo, Rust's package manager:

```bash
git clone https://github.com/Cannon07/minigrep.git
cd minigrep
cargo build
```

This will create the executable file `minigrep` in the `target/release/` directory.

### Usage

The basic usage of MiniGrep is as follows:

```bash
cargo run -- <search_string> <file_path>
```

Replace `<file_path>` with the path to the file you want to search within and `<search_string>` with the string you want to find.

For example:

```bash
cargo run -- "search this string" path/to/file.txt
```


This will search `file.txt` for occurrences of `"search this string"` and print the matching lines.

## Contributions

Contributions are welcome! If you find any issues or want to enhance MiniGrep, feel free to open an issue or submit a pull request.
