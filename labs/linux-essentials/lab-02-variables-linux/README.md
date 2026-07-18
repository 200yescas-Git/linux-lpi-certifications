# Lab 02 - Variables

## Objective

Documentar los fundamentos de las variables en Bash, comprendiendo su creación, asignación, expansión, exportación y administración dentro del entorno Linux.

---

## Environment

- OS: Linux (Debian 13.4.0 Trixie )
- Shell: Bash
- User: Non-root user
- Terminal: xfce Terminal / CLI ( Terminator )
- VMware Workstation 16 Player

---

## Commands Used

```bash
set
env
export
echo
unset
```

---

## Syntax

Ejemplo:

```bash
set [options] [arguments]
env
env VARIABLE=value command
export VARIABLE
export VARIABLE=value
echo [options] text
unset VARIABLE
unset -f FUNCTION
```

---

## Main Options

### set

| Option | Description |
|--------|-------------|
| `-a` | Automatically export all created or modified variables. |
| `-b` | Notify immediately when background jobs terminate. |
| `-e` | Exit immediately if a command returns a non-zero status. |
| `-f` | Disable filename expansion (globbing). |
| `-h` | Remember command locations (hashing). |
| `-m` | Enable job control. |
| `-n` | Read commands without executing them. |
| `-u` | Treat unset variables as an error. |
| `-v` | Print shell input lines as they are read. |
| `-x` | Print commands and arguments before execution (debug mode). |
| `+x` | Disable debug mode. |
| `-o` | Display or set shell options. |

### env

| Option | Description |
|--------|-------------|
| `-i` | Start with an empty environment. |
| `-u VARIABLE` | Remove a variable from the environment. |
| `--help` | Display command help information. |
| `--version` | Display the installed version. |

### export

| Option | Description |
|--------|-------------|
| `-n` | Remove the export attribute from a variable. |
| `-p` | Display all exported variables. |
| `-f` | Export shell functions (Bash). |

### echo

| Option | Description |
|--------|-------------|
| `-n` | Do not output the trailing newline. |
| `-e` | Enable interpretation of backslash escape sequences. |
| `-E` | Disable interpretation of escape sequences (default in Bash). |

### unset

| Option | Description |
|--------|-------------|
| `-f` | Remove a shell function. |
| `-v` | Remove a shell variable (default behavior). |

---

## Examples

Ejemplos prácticos realizados durante el laboratorio.

```bash

```

---

## Evidence

Capturas de pantalla del laboratorio.

Ejemplo:

```text
assets/screenshots/
```

---

## Conclusion

Resumen de los conocimientos adquiridos y la importancia del laboratorio dentro de Linux Essentials.

