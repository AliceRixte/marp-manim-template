---
marp: true
theme: marp-manim-beamer
title: Mon titre
author: Alice Rixte
_class: lead
paginate: true
backgroundColor: #fff
---

<!-- _class: title -->

# Titre

## **Sous-titre**

### Alice Rixte, Université de Bordeaux

---

# How to write slides

Split pages by horizontal ruler (`---`). It's very simple! :satisfied:

The following code will appear in the next slide :
<div data-marpit-fragment>

```markdown
# Slide 1

foobar


---

# Slide 2

foobar
```

</div>

---

# Two columns example

<div class="twocols">

<p>

## Left

1. hedsuifh
1. zdjhaz_dha
1. juiofezjfezi

</p>

<p class="break">

## Right

- Normal item
- Normal item

* This item will be fragmented

- Normal item
- Normal item

</p>

</div>

---

<!-- _class: manim -->

<video  autoplay loop src="./media/videos/marp-template/720p30/CircleToSquare.mp4">

---
# Manim videos

- For now, they only render properly in HTML.

---
# Beamer like boxes
<div class="twocols">
<p>
<div class="infobox">
<div class="boxhead"> Some info box</div>
<div class="boxcontent">

- Some interesting point

  </div>
</div>
</p>

<div class="alertbox">
<div class="boxhead">Alert box</div>
  <div class="boxcontent">

- Something that is utterly not boring
- Even less boring stuff

  </div>
</div>

<p class="break">
<div class="examplebox">
<div class="boxhead">Example box with a way too long title</div>
  <div class="boxcontent">

- Maybe there's not enough room in this. We'll see.

Some LaTeX : $\sqrt{x}$
  </div>
</div>

This feels a bit empty, right ?



