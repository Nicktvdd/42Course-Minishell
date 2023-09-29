# MiniShell
:white_check_mark: Project completed with 101/100 points

# Minishell

Minishell is a lightweight Unix-like shell implemented in C, designed to provide a basic command-line interface to users. It is one of the larger projects done in the 42 curriculum. Minishell allows to relive the challenges of the past, experiencing firsthand the problems faced when Windows was non-existent. Dive into the realm of interactive command lines, understanding the essence of this fundamental form of communication. With Minishell, we are exploring the past and the art of command-line mastery.

We have written this with certain requirements and a limitations, like a limited amount of allowed functions and a norm we had to comply to (like no 'for' loops). This meant we had to build most things from scratch and from a very low-level. We have used [Bash](https://www.gnu.org/software/bash/) as a reference.

I worked on it as a group project in collaboration with [Rasmus](https://github.com/RushMaverick), [Juan](https://github.com/jestebanpelaez18) and [Jun](https://github.com/composerjunhee). We all had a part in creating the completed project, after which we teached eachother our parts and made sure that everyone understood exactly what is going on. My main focus: Lead architecture design, group communication, pipe implementation, and bug hunting.

## Features

- **Basic Shell Commands:** Minishell supports common shell commands such as `ls`, `cd`, `pwd`, `echo`, and `exit`.

- **Piping and Redirection:** You can use pipes (`|`) to chain commands and redirection (`>`, `>>`, `<`) to manage input and output streams.

- **Environment and Internal Shell Variables:** Minishell allows you to work with environment variables like `PATH` and user-defined variables with `export, set, unset`.

- **Inhibitors:** It includes dealing with inhibitors like `" " and ' '`.

-  **History management:** In the shell it remembers all the used commands, you can browse the history with the arrow keys.

- **Inhibitors:** It includes dealing with inhibitors like `" " and ' '`.

## Getting Started

### Prerequisites

- C compiler (e.g. GCC)
- Unix-like operating system (Linux or macOS)

### Installation

1. Clone the Minishell repository:

   ```shell
   git clone https://github.com/nicktvdd/minishell.git
   ```
2. Build the Minishell executable:
   ```
   cd minishell
   make
   ```
3. Usage
   Run Minishell:
   ```
   ./minishell
   ```
You can now start using Minishell. Try basic shell commands, piping and redirection.
In no way should this shell ever crash (e.g. segmentation fault or bus error), leak memory, freeze or get stuck in a loop. Please report any such issues to us if you find them!

# Contact

If you have any questions or feedback, feel free to reach out to me at nicktvdd@gmail.com

Happy coding!
