# Lab 01 - Command Line Basics

## Objetive

Aprender el uso de los comandos fundamentales de la línea de comandos de Linux para navegar por el sistema de archivos, visualizar información básica del sistema, imprimir información en la terminal e identificar la ubicación y el tipo de los comandos disponibles en el entorno Bash.

---

## Environment

- OS: Linux (Debian 13.4.0 Trixie )
- Shell: Bash
- User: Non-root user
- Terminal: xfce Terminal / CLI ( Terminator )
- VMware Workstation 16 Player

---

## Commands Used

- pwd
- ls
- cd
- echo
- type
- which
- uname

---

## Syntax

```bash
pwd [OPTION]
ls [OPTION] [FILE]
cd [DIRECTORY]
echo [OPTION] [STRING]
type [OPTION] NAME
which [OPTION] PROGRAM
uname [OPTION]
```

---

## Main Options

### pwd

| Option | Description |
|--------|-------------|
| -L | Shows logical path (follows symbolic links) |
| -P | Shows physical path (resolves symbolic links) |

## ls

| Option | Description |
|--------|-------------|
| -l | Long listing format |
| -a | Show hidden files |
| -h | Human readable file sizes |
| -R | Recursive listing |
| -t | Sort by modification time |
| -S | Sort by file size |

## cd

| Option | Description |
|--------|-------------|
| - | Switch to previous directory |
| ~ | Switch to home directory |

# echo

## Main Options

| Option | Description |
|--------|-------------|
| -n | Do not output trailing newline |
| -e | Enable interpretation of backslash escapes |

## type

| Option | Description |
|--------|-------------|
| -a | Show all locations of command |
| -t | Show type of command (alias, builtin, file) |
| -p | Show path of executable |

## which

| Option | Description |
|--------|-------------|
| -a | Show all matches in PATH |

## uname

| Option | Description |
|--------|-------------|
| -a | Show all system information |
| -r | Kernel version |
| -m | Machine hardware name |
| -n | Network node hostname |
| -s | Kernel name |


