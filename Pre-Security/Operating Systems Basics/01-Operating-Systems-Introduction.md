# Operating Systems: Introduction

**Status:** Completed

This room introduced the operating system (OS) as the software layer that manages computer hardware and software resources and provides an environment for applications and users.

## What Is an Operating System?

An OS gives users and applications a consistent way to work with a computer. It coordinates access to hardware and provides common services, so each application does not need to manage devices and system resources directly.

Applications request OS services through defined interfaces. The OS then manages the resources and permissions needed to carry out those requests.

## Kernel and User Space

- The **kernel** is the core component of the OS. It manages hardware and system resources and controls important system operations.
- **User space** is where ordinary applications and user processes run. Applications do not directly perform privileged operations; they request them through OS interfaces.
- **System calls** provide a mechanism for applications to request services from the kernel.

## Operating-System Responsibilities

1. **Process management:** Coordinates the execution of running programs and allocates processor time.
2. **Memory management:** Allocates and manages memory used by processes.
3. **File-system management:** Organizes files and directories and manages access to stored data.
4. **User management:** Supports user accounts and the permissions associated with them.
5. **Device management:** Coordinates communication between software and connected hardware.

## Operating-System Security

Authentication establishes which user or process is requesting access. Permissions determine which resources that identity may use. Isolation helps keep processes and users from improperly affecting one another, while protection mechanisms control access to system resources and help prevent unauthorized operations.

## GUI and CLI

- A **Graphical User Interface (GUI)** presents visual elements such as windows, icons, and menus, typically operated with a pointer.
- A **Command-Line Interface (CLI)** accepts text commands through a terminal or shell.

Both provide ways to interact with an OS; the room introduced their different interaction styles.

## Operating-System Categories and Families

The lesson covered operating-system categories and families, but the specific names and descriptions were not retained in the recovered notes. They are therefore not listed here.

## Practical Activities

The room included questions and hands-on tasks to:

- Identify the Ubuntu MATE version.
- Check the system's memory.
- Identify the filesystem type of `/dev/root`.
- Count directories in a user's directory.
- Find Alex's `Documents/note.txt` and retrieve a flag.

The submitted version, memory and filesystem values, directory count, and flag were not retained. No answers or command outputs are inferred here.

## Learning Summary

The OS acts as an intermediary between users, applications, and hardware. Kernel responsibilities make shared use of system resources possible, while authentication, permissions, isolation, and protection help keep that access controlled.
