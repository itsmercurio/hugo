+++
title = 'Sintaxis Extras'
date = 2024-10-03T16:55:34+02:00
draft = false
+++

# Sintaxis Avanzada de Markdown

Aquí te dejo algunas sintaxis adicionales de Markdown que puedes usar para ampliar las funcionalidades de tus archivos:

## Tareas (Checkboxes)

Puedes crear listas de tareas utilizando corchetes con espacios `[ ]` o con una "x" `[x]` para marcar completadas.

```markdown
- [ ] Tarea incompleta
- [x] Tarea completada
```

Esto se verá así:

- [ ] Tarea incompleta  
- [x] Tarea completada

## Comentarios

Los comentarios en Markdown no se muestran en el renderizado final. Para agregarlos, puedes usar HTML:

```html
<!-- Este es un comentario que no se verá en el archivo final -->
```

## Enlaces internos (Anchors)

Puedes crear enlaces dentro del mismo documento apuntando a encabezados. Los enlaces deben usar el texto del encabezado en minúsculas y reemplazando los espacios por guiones (`-`).

```markdown
[Ir a la sección Encabezados](#encabezados)
```

Si el archivo tiene una sección como esta:

```markdown
## Encabezados
```

El enlace te llevará allí.

## Subíndices y Superíndices

Markdown no tiene una sintaxis directa para subíndices o superíndices, pero puedes hacerlo con HTML:

```markdown
Agua es H<sub>2</sub>O.
```

Se verá así:  
Agua es H₂O.

Para superíndices:

```markdown
El área de un cuadrado es A = L<sup>2</sup>.
```

Se verá así:  
El área de un cuadrado es A = L².

## Alineación de texto en tablas

Para alinear el texto en tablas, puedes usar dos puntos `:` en la fila de separación de columnas:

```markdown
| Izquierda   | Centro    | Derecha   |
|:----------- |:---------:| ---------:|
| Texto       | Texto     | Texto     |
```

Se verá así:

| Izquierda   | Centro    | Derecha   |
|:----------- |:---------:| ---------:|
| Texto       | Texto     | Texto     |

## Saltos de línea

Si necesitas un salto de línea en Markdown, puedes insertar dos espacios al final de la línea o usar `<br>`:

```markdown
Línea 1 (con dos espacios al final)  
Línea 2
```

O

```markdown
Línea 1<br>Línea 2
```

Ambos se verán así:

Línea 1  
Línea 2

## Escapando caracteres

Si necesitas usar un carácter reservado de Markdown, como el `#` o `*`, pero no quieres que se interprete, puedes escapar los caracteres con una barra invertida `\`.

```markdown
\# Esto no será un encabezado
\*Texto que no será cursiva*
```

Esto se verá así:

\# Esto no será un encabezado  
\*Texto que no será cursiva*

## Definiciones (Glossary)

Puedes crear un glosario de términos utilizando la siguiente estructura, aunque no todos los renderizadores de Markdown la soportan:

```markdown
Término 1
: Definición de término 1

Término 2
: Definición de término 2
```

Esto se verá así en los renderizadores compatibles:

**Término 1**  
Definición de término 1

**Término 2**  
Definición de término 2

## Notas al pie

Para crear notas al pie, utiliza \`[^nombre]\` en el texto, y luego agrega la nota al final del documento:

```markdown
Este es un ejemplo de una nota al pie.[^nota1]

[^nota1]: Este es el texto de la nota al pie.
```

Se verá así:

Este es un ejemplo de una nota al pie.[^nota1]

[^nota1]: Este es el texto de la nota al pie.

---

Estas sintaxis adicionales pueden ayudarte a enriquecer tus documentos en Markdown con más funcionalidades y un mejor formato.
