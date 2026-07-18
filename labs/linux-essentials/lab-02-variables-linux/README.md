# Lab 02 - Variables

## Objective

Descripción breve del objetivo del laboratorio.

---

## Environment

- OS: Linux (Debian 13.4.0 Trixie )
- Shell: Bash
- User: Non-root user
- Terminal: xfce Terminal / CLI ( Terminator )
- VMware Workstation 16 Player

---

## Commands Used

Listado de todos los comandos utilizados durante el laboratorio.

```bash
echo
printenv
env
export
unset
set
```

---

## Syntax

Explicación de la sintaxis utilizada.

Ejemplo:

```bash
VARIABLE=value

echo $VARIABLE

export VARIABLE

unset VARIABLE
```

---

## Main Options

Explicación de las opciones más importantes de cada comando utilizado.

Ejemplo:

### printenv

| Option | Description |
|---------|-------------|
| VARIABLE | Display a specific environment variable. |

### env

| Option | Description |
|---------|-------------|
| -i | Start with an empty environment. |

### export

Uso del comando y explicación.

---

## Examples

Ejemplos prácticos realizados durante el laboratorio.

```bash
MY_VAR="Linux"

echo $MY_VAR

export MY_VAR

printenv MY_VAR

unset MY_VAR
```

Puedes agregar varios ejemplos conforme avance el laboratorio.

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

