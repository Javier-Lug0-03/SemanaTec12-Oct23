# SemanaTec12-Oct23
# Nombre: Francisco Javier Lugo Gutierrez
# Matricula: A01571142
# Carrera: ITC
# Semestre: 5to semestre
## Practica de GitHub


# Nombre Dana Sanchez A01723361


**Bold Semana Tec 12**

*Italic*

<<<<<<< HEAD
1. Hot-cakes :pancakes
2. Tacos Barbacoa :taco
3. Chilaquiles :chile
4. Galletas :cookies
5. Huevo estrellado :egg

- Piano
- Guitarra
- Mandolina
- Bajo
- Flauta

```python

"""Illusion

Exercises:

1. Change the size of the squares.
2. Change the number of rows and lines.
"""

from itertools import cycle
from turtle import *

from freegames import line, square

size = 25


def draw_row(x, y):
    for i in range(0, 10):
        offset = x + (i * size * 2)
        square(offset, y, size, 'black')


def draw_rows():
    offsets = [-200, -190, -180, -190]
    pairs = zip(cycle(offsets), range(150, -176, -25))
    for offset, y in pairs:
        draw_row(offset, y)


def draw_lines():
    x = -200
    y = 150
    for i in range(0, 14):
        line(x, y - i * size, x + 16 * size, y - i * size)


setup(420, 400, 30, 0)
hideturtle()
tracer(False)
listen()
draw_rows()
draw_lines()
done()
```
![Dia_Medico](https://tvazteca.brightspotcdn.com/ae/f1/24e99d784d6ab98d4a365ca8bac1/dia-del-medico-23-octubre.jpg)

[link a markdown](https://www.markdownguide.org/cheat-sheet/)

| Nombre | Actividad |
| ------- | -------- |
| Yeseli | Dibujar auto |
| Carolina | Dibujar pastel |

- [x] Javier, dibujar otro auto
