# 🐚 AminaShell

A minimalist and elegant UNIX-like shell written in C, developed to understand the internal workings of command interpreters and system-level process management.

---

## 📌 Table of Contents

- [Overview](#overview)  
- [Key Functionalities](#key-functionalities)  
- [Installation](#installation)  
- [Example Commands](#example-commands)  
- [Shell Preview](#shell-preview)  
- [Learning Objectives](#learning-objectives)  
- [Known Limitations](#known-limitations)  
- [Future Improvements](#future-improvements)  
- [Author](#author)  
- [License](#license)

---

## Overview

**AminaShell** is a custom terminal shell that mimics UNIX behavior using core system calls. It supports basic command execution, redirection, pipes, and built-in commands with a clean user interface and prompt design.

---

## Key Functionalities

- ✅ Execution of standard UNIX commands: `ls`, `pwd`, `cat`, etc.  
- ✅ Built-in commands:
  - `cd <dir>` – Change working directory
  - `exit` – Exit the shell
  - `help` – Display command information  
- ✅ Input/output redirection: `>`, `>>`, `<`  
- ✅ Simple piping: `|`  
- ✅ Command history recall: `!!`  
- ✅ Custom prompt with timestamp, username, and path  
- ✅ Signal handling for `Ctrl+C`  
- ✅ Stylish terminal UI with colors

---

## Installation

### Requirements

- Linux OS  
- `gcc` compiler  
- `make` utility  
- Git (optional)



### 🖼️ Shell Preview

A screenshot of **AminaShell** running in the terminal, showcasing its prompt and colors.

![image](https://github.com/user-attachments/assets/31796516-cd7d-4632-9f89-4085410a7475)


---

## 🎯 Learning Objectives

Through this project, I learned to:

- Use system-level calls like `fork()`, `execvp()`, `wait()`, `dup2()`
- Build a functional command parser and process controller
- Implement pipes and redirections manually
- Handle terminal I/O and color formatting using ANSI escape codes
- Structure a clean C project with modularity and a `Makefile`
- Manage Git version control and understand large file constraints

---

## 🚀 Future Improvements

- [ ] Add support for command chaining (`;`) and background execution (`&`)
- [ ] Implement arrow key navigation for command history
- [ ] Support environment variable expansion
- [ ] Improve input validation and error messages
- [ ] Add unit tests for core command execution
- [ ] Integrate a config system for prompt themes
- [ ] Add Git LFS support for managing large assets

---

## 👩‍💻 Author

**Amina Bajdouri**  
🎓 *Data & Software Engineering Student at INSEA*  

🔗 [GitHub: @16Amina07](https://github.com/16Amina07)
