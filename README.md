# Learning Rust: Projects from "The Rust Programming Language"

This repository documents my journey of learning the Rust programming language by building the projects outlined in the official book, ["The Rust Programming Language"](https://doc.rust-lang.org/book/).

Each project is organized into its own directory.

---

## Projects Completed

- **[Chapter 2: Guessing Game](./Chapter2_guessing_game/)**: A classic number guessing game where the program picks a random number and the user has to guess it.

- **[Chapter 12: Minigrep](./minigrep/)**: A simplified command-line tool that clones the functionality of `grep` to search for a string within a file.

- *(More projects will be added as I progress through the book!)*

---

## How to Run a Project

To run any of the projects locally, follow these steps:

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/nigamanandajoshi/Rust_book.git](https://github.com/nigamanandajoshi/Rust_book.git)
    cd Rust_book
    ```

2.  **Navigate to a specific project's directory:**
    ```bash
    # For example, to run minigrep:
    cd minigrep/
    ```

3.  **Use Cargo to build and run the project:**
    ```bash
    # To run the program:
    cargo run

    # To run tests (for projects that have them):
    cargo test
    ```
