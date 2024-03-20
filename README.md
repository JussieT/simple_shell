
**ALX Simple Shell Team Project**

This project aims to develop a simple shell (`hsh`) that mimics the behavior of the Bash shell. It's an ALX collaboration project focusing on understanding shell operations, environment variables, and system calls.

**Key Points:**
- The shell is developed in C, following the principles of the Bourne Shell (`sh`).
- The project emphasizes understanding core concepts such as the environment, system calls, and process creation using `execve`.
- Development follows specific requirements including adherence to the Betty coding style, avoiding memory leaks, and limiting functions per file.

**Functionality:**
- `hsh` works by displaying a prompt, waiting for user commands, and executing them.
- It supports built-in commands like `cd`, `alias`, `exit`, `env`, `setenv`, and `unsetenv`.
- The shell handles command execution, including built-ins, aliases, and executable programs.
- Users can interactively run commands or provide a file containing commands for non-interactive mode.

**Environment Variables:**
- `hsh` copies the environment of the parent process, including variables like `HOME`, `PWD`, `OLDPWD`, and `PATH`.

**Authors:**
- The project is developed by Emmanuel Ugwuagbo

---


