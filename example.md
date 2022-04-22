# Note 1 - 21.04.2022

## 1. Equation example

### Steps for solving quadratic equations

- Start with an equation of this form

$$
ax^2 + bx + c = 0
$$

- Compute $\Delta$ using

$$
\Delta = b^2 - 4ac
$$

- If $\Delta > 0$, then solve the 2 unknowns as

$$
x_1 = \frac{-b + \sqrt{\Delta}}{2a} \qquad \text{and} \qquad x_2 = \frac{-b - \sqrt{\Delta}}{2a}
$$

- If $\Delta = 0$, then solve for one solution as

$$
x = -\frac{b}{2a}
$$

- If $\Delta < 0$, then no real solution exists, or compute the complex solutions as

$$
x_1 = -\frac{b}{2a} + \frac{\sqrt{|\Delta|}}{2a}j \qquad \text{and} \qquad x_2 = -\frac{b}{2a} - \frac{\sqrt{|\Delta|}}{2a}j
$$

$$
\text{where} \qquad j^2 = -1
$$

Note: If you want to write multiple lines of equations, then wrap the equations inside the Latex environments "align*" or "align" instead of the $$ pairs.

### Latex macros example

\newcommand{\der}[1]{\frac{d #1}{dt}}
\newcommand{\Der}[1]{\frac{d}{dt} \left[ #1 \right]}

Latex-style macros can be defined for efficient writing in math mode. For example,

```latex
\newcommand{\der}[1]{\frac{d #1}{dt}}
```

defines the derivative of a variable symbol which is supplied as an argument. So that one can write `\der{x}` in math mode to give $\der{x}$.

Another example, define

```latex
\newcommand{\Der}[1]{\frac{d}{dt} \left[ #1 \right]}
```

and then write

```latex
\Der{\frac{1}{x^2} + \frac{1}{x}}
```

to render $\Der{\frac{1}{x^2} + \frac{1}{x}}$.

## 2. Table example

| Syntax      | Description | Test Text     |
| :---        |    :----:   |          ---: |
| Header      | Title       | Here's this   |
| Paragraph   | Text        | And more      |

## 3. Code example

C Hello world:

```c
#include <stdio.h>
int main()
{
    printf("Hello world\n");
    return 0;
}
```

Python hello world:

```python
print("Hello world");
```

## 4. Figure example

Example picture.

![Mountain](./mountain.jpg)
