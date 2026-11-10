# Linux CLI Basics

**Status:** Completed

This practical room introduced the Linux command-line interface (CLI), where users interact with the operating system by entering commands in a terminal.

## Navigation and File Commands

### `pwd`

```text
pwd
```

Displays the current working directory.

### `ls`

```text
ls
```

Lists files and directories in the current directory.

### `ls -l`

```text
ls -l
```

Displays a detailed listing, including permissions, ownership, file size, and modification information.

### `ls -al`

```text
ls -al
```

Displays a detailed listing that also includes hidden files and directories.

### `cd`

```text
cd
```

Changes the current working directory. With no directory argument, it normally returns the user to their home directory.

### `cd ..`

```text
cd ..
```

Moves one directory level upward.

### `find`

```text
find ~ -name mission_brief.txt
```

Searches the user's home directory for a file named `mission_brief.txt`.

### `cat`

```text
cat filename
```

Displays the contents of a file in the terminal. The mission used `cat` to read files.

## System-Information Commands

### `whoami`

```text
whoami
```

Displays the current username.

### `uname -a`

```text
uname -a
```

Displays detailed kernel and system information.

### `uname`

```text
uname
```

Displays the operating-system kernel name.

### `df -h`

```text
df -h
```

Displays filesystem disk-space usage in human-readable units.

### Distribution release information

```text
cat /etc/os-release
```

Displays information about the Linux distribution and operating-system release.

## Mission Activity

The exercise involved locating and reading `mission_brief.txt` and `day1_report.txt`. The documented workflow was:

1. Inspect the current directory with `pwd`.
2. List files with `ls`, then use `ls -l` or `ls -al` for more detail.
3. Navigate with `cd` and move to the parent directory with `cd ..`.
4. Search the home directory for `mission_brief.txt` using `find`.
5. Read the mission file with `cat`.
6. Inspect the current user, kernel, disk usage, and release information with `whoami`, `uname`, `df -h`, and `cat /etc/os-release`.
7. Continue the mission by locating and reading `day1_report.txt`.

The exact paths found, file contents, flags, kernel values, disk values, and report answers were not retained.

## Key Takeaways

The room practiced directory navigation, listing and searching for files, reading file contents, and checking basic system information. These CLI skills are useful for understanding and administering Linux systems.
