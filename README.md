# Rust-Command-line
Command line program built using Rust

## Project Overview
This project, named **minigrep**, is a simple grep-like tool implemented in Rust. It searches for a query string within a text file and prints out the lines containing the query.

## Installation
To install and run this project, you need to have Rust installed on your system. Here are the steps:

1. **Install Rust**: If you don't have Rust installed, follow the instructions at [rustup.rs](https://rustup.rs/).
2. **Clone the Repository**: 
   ```sh
   git clone https://github.com/your-username/minigrep.git
   ```
3. **Navigate to the Project Directory**:
   ```sh
   cd minigrep
   ```
4. **Build the Project**:
   ```sh
   cargo build --release
   ```
   The executable will be located in `target/release/minigrep`.

## Usage
To use minigrep, run the following command from the project directory:

```sh
./target/release/minigrep <query> <filename>
```

- **query**: The string to search for.
- **filename**: The file to search in.

For example:
```sh
./target/release/minigrep "hello" poem.txt
```

## Project Structure
- **minigrep/**: The main project directory.
  - **Cargo.toml**: Project manifest file.
  - **src/**: Source code directory.
    - **main.rs**: The main entry point of the application.
  - **grep_fun/**: A library module for grep functionality.
    - **src/lib.rs**: The library source file.
  - **poem.txt**: A sample text file for testing.

## License
This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.
