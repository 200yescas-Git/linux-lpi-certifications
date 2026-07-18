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

### `set`

```bash
# Display all shell variables and functions
set

# Display current shell options
set -o

# Enable debug mode
set -x

echo "Hello World"

# Disable debug mode
set +x

# Exit immediately if a command fails
set -e

# Print shell input lines as they are read
set -v

# Treat unset variables as an error
set -u
```

---

### `env`

```bash
# Display all environment variables
env

# Display the HOME environment variable
env | grep HOME

# Execute Bash with a temporary environment variable
env USERNAME=Brayan bash

# Start Bash with an empty environment
env -i bash

# Execute Bash without the HOME variable
env -u HOME bash
```

---

### `export`

```bash
# Export a variable
export USERNAME=Brayan

# Verify the exported variable
echo $USERNAME

# Export the default editor
export EDITOR=nano

# Add a directory to PATH
export PATH=$PATH:/opt/scripts

# Display exported variables
export -p

# Remove the export attribute
export -n USERNAME
```

---

### `echo`

```bash
# Display text
echo "Hello World"

# Display the current user
echo $USER

# Display the home directory
echo $HOME

# Display the current working directory
echo $PWD

# Print with a newline
echo -e "Linux\nEssentials"

# Print with a tab
echo -e "Name\tAge"

# Print without a trailing newline
echo -n "Loading..."
```

---

### `unset`

```bash
# Create a variable
VARIABLE=Linux

# Display the variable
echo $VARIABLE

# Remove the variable
unset VARIABLE

# Verify it has been removed
echo $VARIABLE

# Create a function
my_function() {
    echo "Hello"
}

# Execute the function
my_function

# Remove the function
unset -f my_function
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

