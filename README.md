# Applied Terminals

Essential terminal skills, including navigating file systems, running commands, and using terminal tools across Windows, macOS, and Linux. 
This guide is designed to cover the basics of terminal use on different operating systems.

## Why This is Important

- Terminal commands offer quick and efficient ways to navigate and manage files, especially when graphical tools fall short.  
- Many programming and system tasks require running commands in a terminal, such as installing software or checking configurations.  
- Knowing terminal basics makes it easier to work across different operating systems, including Windows, macOS, and Linux.
- Terminals are integrated into powerful developer tools like VS Code, GitHub Codespaces, Shinylive, and more.

## What is a Terminal?

 A graphical program that opens a command-line interface (CLI), allowing interaction with a shell. 
 It acts as a container in which the shell runs and often includes features like tabs or panes to host multiple processes simultaneously. 
 Examples include Windows Terminal, macOS Terminal, and GNOME Terminal on Linux.

## Terminal vs. Shell

- Terminal - The interface where commands are typed (e.g., Windows Terminal, macOS Terminal).
- Shell - the engine that processes the commands and executes them (e.g., PowerShell, Bash, Zsh).

## Popular Shells

- Windows PowerShell - The default shell on Windows, offering enhanced scripting capabilities.  
- PowerShell Core (pwsh) - A cross-platform version of PowerShell for Windows, macOS, and Linux.  
- Bash (Bourne Again Shell) - A common shell used on Linux and macOS.  
- Zsh (Z Shell) - A modern shell available on macOS by default and often used on Linux.
- Git Bash -  A lightweight version of Bash that runs on Windows after installing Git, providing Unix-like commands for Windows users.  
- WSL (Windows Subsystem for Linux) - A compatibility layer that allows Windows users to run a full Linux distribution, including Bash or Zsh, alongside Windows applications. Used to run Apache Spark, Apache Kafka, and more on a Windows machine. 

Shells can be identified by the prompt - the visual indicator where we type our commands. 

1. PowerShell `PS C:\>`  
2. pwsh       `PS /home/user>` (cross-platform, with Linux-style paths on macOS/Linux)  
3. Bash       `user@hostname:~$`  
4. Zsh        `user@hostname ~%` (varies with customization, but `%` is a common default)  
5. Git Bash   `user@hostname MINGW64 ~/`  
6. WSL        `user@hostname:/mnt/c/Users/username$` (Linux-style paths for Windows directories)  

### Task-Specific Guides

- [How to Open a Terminal in Your Documents Folder](open-terminal-in-Documents.md)
- [Terminal File Management](terminal-file-management.md)

## Know These Terms

- Administrator - A user with elevated permissions to create, delete, or modify settings and items.  
- Command-line interface (CLI) - A text-based interface used to interact with the operating system.  
- Command - A specific instruction you type into the terminal to perform an action (e.g., `cd`, `ls`).  
- Flag/Option - Additional input that modifies how a command runs (e.g., `-l` for detailed output in `ls -l`).  
- Path - The location of a file or directory in the file system (e.g., `C:\Users\John\Documents` or `/home/john/Documents`).  
- Prompt - A text indicator where commands are typed (e.g., `C:\>` or `john@mac:~$`).  
