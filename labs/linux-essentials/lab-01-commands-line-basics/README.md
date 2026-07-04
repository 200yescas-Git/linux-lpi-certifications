# Lab 01 - Commands Line Basics

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

### ls

| Option | Description |
|--------|-------------|
| -l | Long listing format |
| -a | Show hidden files |
| -h | Human readable file sizes |
| -R | Recursive listing |
| -t | Sort by modification time |
| -S | Sort by file size |

### cd

| Option | Description |
|--------|-------------|
| - | Switch to previous directory |
| ~ | Switch to home directory |

### echo

| Option | Description |
|--------|-------------|
| -n | Do not output trailing newline |
| -e | Enable interpretation of backslash escapes |

### type

| Option | Description |
|--------|-------------|
| -a | Show all locations of command |
| -t | Show type of command (alias, builtin, file) |
| -p | Show path of executable |

### which

| Option | Description |
|--------|-------------|
| -a | Show all matches in PATH |

### uname

| Option | Description |
|--------|-------------|
| -a | Show all system information |
| -r | Kernel version |
| -m | Machine hardware name |
| -n | Network node hostname |
| -s | Kernel name |

---

## Examples

### Navigation

```bash
pwd
ls
cd /
ls -l /etc
```

### System Information

```bash
uname -a
uname -r
uname -m
```

### Command Identification

```bash
type ls
which ls
type -a ls
```

### Text Output

```bash
echo "Hello Linux"
echo $HOME
echo -n "No newline"
```

---

## Evidence

Agrego evidencias de la práctica realizada.se encuentran en el siguiente directorio:

`assets/linux-essentials/screenshots/labs/lab-01-command-line-basics`

## Conclusion

La realización de este laboratorio permitió adquirir una comprensión práctica de los conceptos fundamentales de la línea de comandos en Linux. Durante el desarrollo de las actividades se reforzó el uso de comandos básicos para la navegación del sistema de archivos, la exploración de directorios y la obtención de información del sistema, estableciendo una base sólida para laboratorios de mayor complejidad.

Este laboratorio representa el inicio de una ruta de formación enfocada en la administración de sistemas Linux, donde cada práctica documentada fortalece tanto las habilidades técnicas como la capacidad de documentar procesos de manera profesional, siguiendo buenas prácticas utilizadas en entornos empresariales.

