+++
title = "Line and Numbering"
date = 2026-05-13
updated = 2026-05-16
+++

Pengetahuan.
<!-- more -->


# Informasi

Artikel ini berisi berbagai format penulisan Markdown untuk pengujian tampilan dan penyesuaian desain Pointaris.



---

## Paragraf Biasa

Markdown secara otomatis mengubah teks biasa menjadi paragraf HTML. Anda dapat menulis artikel panjang, refleksi, maupun penjelasan teknis menggunakan format ini.

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vestibulum sed quam vitae dui dictum vehicula eget vel ligula. Nam vulputate rhoncus sem vel tristique.

---

## Heading

# Heading 1

## Heading 2

### Heading 3

#### Heading 4

##### Heading 5

###### Heading 6

---

## Bold dan Italic

**Bold Text**

*Italic Text*

***Bold Italic Text***

---

## Blockquote

> Ini adalah blockquote biasa.
>
> Cocok untuk kutipan, refleksi, atau catatan penting.

> “In a world obsessed with the big picture, we focus on the point.”

---

## Bullet List

* Science
* Technology
* Reflection
* Philosophy
* Independent Research

### Nested Bullet List

* Physics

  * Wave Phenomena
  * Electromagnetism
  * Quantum Mechanics
* Mathematics

  * Calculus
  * Statistics
  * Numerical Methods

---

## Ordered List

1. Install Zola
2. Create templates
3. Configure CSS
4. Write Markdown articles
5. Deploy website

---

## Inline Code

Gunakan perintah `zola serve` untuk menjalankan server lokal.

---

## Code Block

```python
import numpy as np

x = np.linspace(0, 10, 100)
y = np.sin(x)

print(y)
```

```cpp
#include <iostream>

int main() {
    std::cout << "Hello World";
    return 0;
}
```

```bash
zola serve
```

---

## Link

[Zola Website](https://www.getzola.org)

---

## Image

```md
![Deskripsi Gambar](/images/example.jpg)
```

Contoh gambar:

![Example Image](/images/rect13364.jpg)

---

## Table

| Topic       | Description                      |
| ----------- | -------------------------------- |
| Physics     | Study of matter and energy       |
| Mathematics | Study of patterns and structures |
| Philosophy  | Study of knowledge and existence |

---

## Horizontal Rule

---

Teks di atas dan bawah dipisahkan menggunakan horizontal rule.

---

## KaTeX Inline Equation

Persamaan energi relativistik adalah $E = mc^2$.

Persamaan gelombang:

$y(x,t) = A \sin(kx - \omega t)$

---

## KaTeX Block Equation

$$
\int_a^b f(x),dx
$$

$$
\nabla^2 \psi = 0
$$

$$
\frac{d^2x}{dt^2} + \omega^2 x = 0
$$

---

## Task List

* [x] Install Zola
* [x] Create homepage
* [x] Create article template
* [ ] Add pagination
* [ ] Add dark mode

---

## Definition Style Paragraph

Term

: Penjelasan singkat mengenai istilah tertentu.

---

## Long Paragraph Test

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ligula mauris, hendrerit nec lobortis quis, suscipit vel sapien. Phasellus commodo, sem ut eleifend dapibus, mauris erat hendrerit neque, id posuere massa nisl id augue. Class aptent taciti sociosqu ad litora torquent per conubia nostra, per inceptos himenaeos. Integer vel lorem efficitur, sagittis tellus quis, imperdiet magna. Curabitur lacinia sed risus vitae ullamcorper. Nunc quis tincidunt risus. Cras faucibus, nibh sit amet auctor efficitur, lectus quam porta magna, vestibulum blandit orci erat vulputate magna.

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vestibulum sed quam vitae dui dictum vehicula eget vel ligula. Nam vulputate rhoncus sem vel tristique. Vestibulum ante ipsum primis in faucibus orci luctus et ultrices posuere cubilia curae.

---

## Escaped Characters

*Ini bukan italic*

# Ini bukan heading

---

## HTML Inline

<div>
Ini contoh HTML langsung di dalam Markdown.
</div>

---

## Penutup

Dokumen ini digunakan untuk menguji:

* typography
* spacing
* heading
* bullet list
* KaTeX
* syntax highlighting
* responsive layout
* image rendering
* table rendering
* readability

pada tema Pointaris.
