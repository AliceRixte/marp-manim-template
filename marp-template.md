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

# Three columns example

<div class="container">

<div class="col">

# **Left**

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Phasellus quis ex quis quam porta consequat. Pellentesque hendrerit, orci eu rhoncus fringilla, leo ligula fermentum libero, vitae tincidunt nulla lorem pretium diam.

</div>

<div class="col">

# **Middle**

- Normal item
- Normal item
* This item will be fragmented
- Normal item
- Normal item

</div>

<div class="col">

# **Right**

- Normal item
- Normal item
* Another fragment 
- Normal item
- Normal item

</div>
</div>

---

<!-- _class: manim -->

<video  autoplay loop src="./media/videos/marp-template/720p30/CircleToSquare.mp4">

---
# Manim videos

- Sadly, they only render properly in HTML, pdf doesn't like them :cry:

---
# Beamer-like boxes
<div class="container">
<div class="col">

<div class="infobox">
<div class="boxhead"> Some info box</div>
<div class="boxcontent">

- Some interesting point

</div>
</div>

<div class="alertbox">
<div class="boxhead">Alert box</div>
<div class="boxcontent">

- Something that is utterly not boring
- Even less boring stuff

</div>
</div>
</div>

<div class="col">
<div class="examplebox">
<div class="boxhead">Example box with a way way too long title</div>
<div class="boxcontent">

- Maybe there's not enough room in this. We'll see.

Some LaTeX : $\sqrt{x}$

- I feel quite bad about indentation not being possible because of markdown thinking it's code, HTML looks ugly.
</div>
</div>



</div>
