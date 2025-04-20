<h1 align="center">🌀 Minishell</h1>

<p align="center">
  <b>A minimalistic shell implementation in C, developed as part of the 42 School curriculum.</b><br>
  <i>Emulating core functionalities of Unix shells like Bash, focusing on process management, parsing, and built-in commands.</i>
</p>

---

## 📚 Project Overview

**Minishell** is a team project at [42 School](https://42.fr/en/homepage/) aimed at creating a basic shell program in C. The goal is to understand and implement the fundamental aspects of a Unix shell, including:

- Command parsing and execution
- Handling built-in commands
- Managing environment variables
- Implementing redirections and pipelines
- Signal handling and error management

This project emphasizes adherence to the school's coding standards and promotes a deeper understanding of system-level programming.

---

## 🛠️ Features

- **Prompt Display**: Customizable shell prompt awaiting user input.
- **Built-in Commands**:
  - `echo` with `-n` option
  - `cd` with relative and absolute paths
  - `pwd` displaying the current directory
  - `export` and `unset` for environment variable management
  - `env` to display environment variables
  - `exit` to terminate the shell
- **External Command Execution**: Running binaries located in system paths or specified by the user.
- **Redirections**:
  - Input `<` and output `>` redirection
  - Append output `>>`
  - Here-document `<<`
- **Pipelines**: Using `|` to pass the output of one command as input to another.
- **Environment Variable Expansion**: Interpreting `$VARIABLE` within commands.
- **Signal Handling**: Managing `SIGINT` (Ctrl+C) and `SIGQUIT` (Ctrl+\) signals gracefully.
- **Error Handling**: Providing meaningful error messages without using `errno`.

---

## 📁 Project Structure


---

## 🚀 Getting Started

### Prerequisites

- GCC compiler
- GNU Make
- Readline library

### Installation

1. **Clone the Repository**:

   ```bash
   git clone git@github.com:yourusername/minishell.git
   cd minishell

