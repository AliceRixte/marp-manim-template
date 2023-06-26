# marp-manim-template

A template for my presentations using [Marp](https://github.com/marp-team/marp) and [Manim](https://www.manim.community). Please note that this is sketchy code that I use for my own presentations. The best way to use it is to look at [marp-manim-beamer.css](themes/marp-manim-beamer.css) for some inspiration.

The tutorial  [First Steps with Manim](First%20Steps%20with%20Manim.ipynb)  comes from the repository [Jupyter Examples](https://github.com/ManimCommunity/jupyter_examples).

## How to use

To use this marp theme in vscode, use the following in your vscode settings (see this [Stackoverflow question](https://stackoverflow.com/questions/63102715/marp-cli-how-to-use-a-custom-theme-that-imports-the-default-theme)) :

```json
"markdown.marp.themes": [
  "https://github.com/autonym8/marp-manim-template/blob/main/marp-manim-beamer.css"
]
```

or locally :

```json
"markdown.marp.themes": [
  "./themes/marp-manim-beamer.css"
]
```
