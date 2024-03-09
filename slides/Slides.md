---
marp: true
theme: custom-default
footer: 'https://www.upyesp.org'
---

# My Presentation
![bg right](https://picsum.photos/800/600)

---

<!-- Speaker Notes -->
## Slide 1

- Item 1
- Item 2
- Item 3
<!-- Can have multiple on a slide -->

---

## Slide 2
<!-- Can also do a multiline
comment that will show in notes -->

![Image](https://picsum.photos/800/600)

---

## Slide 3

> This is a quote.

---

## Slide 4

| Column 1 | Column 2 |
| -------- | -------- |
| Item 1   | Item 2   |
| Item 3   | Item 4   |

---

![bg opacity](https://picsum.photos/800/600?image=53)

## Slide 5

Two columns:

<div class="columns">
<div>

## Left

- 1
- 2

</div>
<div>

## Right

- 3
- 4

</div>
</div>

---

## Slide 6

Socials:

<i class="fa-brands fa-mastodon"></i> Mastodon: https://fosstodon.org/@upyesp
<i class="fa fa-window-maximize"></i> Blog: https://www.upyesp.org
<i class="fa-brands fa-github"></i> GitHub: https://github.com/upyesp

---

# <!--fit--> Large Text

---

<!-- Needed for mermaid, can be anywhere in file except frontmatter -->
<script type="module">
  import mermaid from 'https://cdn.jsdelivr.net/npm/mermaid@10/dist/mermaid.esm.min.mjs';
  mermaid.initialize({ startOnLoad: true });
</script>

# Mermaid

<div class="mermaid">
graph TD;
    A-->B;
    A-->C;
    B-->D;
    C-->D;
</div>

# PlantUML


![PlantUMLDiagram](https://www.plantuml.com/plantuml/svg/SoWkIImgAStDuNBAJrBGjLDmpCbCJbMmKiX8pSd9vt98pKi1IW80)
