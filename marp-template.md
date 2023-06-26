---
marp: true
theme: default
title: Mon titre
author: Alice Rixte
_class: lead
paginate: true
backgroundColor: #fff


---

<style>
h1 {
  text-align : center;
}

div.twocols {
  margin-top: 35px;
  column-count: 2;
}
div.twocols p:first-child,
div.twocols h1:first-child,
div.twocols h2:first-child,
div.twocols ul:first-child,
div.twocols ul li:first-child,
div.twocols ul li p:first-child {
  margin-top: 0 !important;
}
div.twocols p.break {
  break-before: column;
  margin-top: 0;
}


.infobox {
  position: relative;
  margin-right: 15px;
  border: solid 1px #77C8F6;
  margin-bottom: 15px;
}

.alertbox {
  position: relative;
  margin-right: 15px;
  border: solid 1px #ff8080;
  margin-bottom: 15px;
}

.examplebox {
  position: relative;
  margin-right: 15px;
  border: solid 1px #70db70;
  margin-bottom: 15px;
}



.boxhead {
  padding: 15px;
  font-weight : bold;
}

.infobox .boxhead{
  background: #77C8F688;
}

.alertbox .boxhead{
  background: #ff808088;
}

.examplebox .boxhead{
  background: #85e08588;
}


.boxcontent {
  padding: 15px;
}

.infobox .boxcontent{
  background: #77C8F633;
}

.alertbox .boxcontent{
  background: #ff808033;
}

.examplebox .boxcontent{
  background: #85e08533;
}

</style>

<style>
section.title {
  --title-height: 130px;
  --subtitle-height: 80px;
  --author-height: 50px;

  overflow: visible;
  display: grid;
  grid-template-columns: 1fr;
  grid-template-rows: 1fr var(--title-height) var(--subtitle-height) var(--author-height) 1fr;
  grid-template-areas: "." "title" "subtitle" "author" ".";
}

section.title h1,
section.title h2,
section.title h3 {
  margin: 0;
  padding: 0;
  text-align: center;
  height: var(--area-height);
  line-height: var(--area-height);
  font-size: calc(var(--area-height) * 0.7);
}

section.title h1 {
  grid-area: title;
  --area-height: var(--title-height);
}

section.title h2 {
  grid-area: subtitle;
  --area-height: var(--subtitle-height);
}
section.title h3 {
  margin-top:60px;
  grid-area: author;
  --area-height: var(--author-height);
}
</style>



<!-- _class: title -->
# Titre

## **Sous-titre**

### Alice Rixte, Université de Bordeaux


---

# How to write slides


Split pages by horizontal ruler (`---`). It's very simple! :satisfied:

ezfq


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


# bnoiuferghb
<div class="twocols">

1. hedsuifh
A. ezhfbeuzyf
1. zdjhaz_dha
  1. juiofezjfezi


<p class="break"></p>

- zdnuifez
- dzabuizadb
* ejkhzfdnlzfe
- ezfiofezjhez
- za,dzedzsfe

</div>

---
<style scoped>
  section {
  padding : 0
}
</style>

<video autoplay="true" position="absolute" right="0" min-width="100%" min-height = "100%" loop="true" src="./media/videos/marp-template/720p30/CircleToSquare.mp4">

---


<div class="infobox">
<div class="boxhead">Some info box</div>
  <div class="boxcontent">

   * eznfuifez

  </div>
</div>
</div>

<div class="alertbox">
<div class="boxhead">Alert box</div>
  <div class="boxcontent">

  - eznfuifez
  -  efzhfzeçfh
  </div>
</div>
</div>

<div class="examplebox">
<div class="boxhead">Example box</div>
  <div class="boxcontent">

   - eznfuifez

  </div>
</div>
</div>

$\sqrt{x}$