# Code for Portland slides

Temporary home for Code for Portland presentations.

## Usage

Clone it

```
git clone git@github.com:ngoldman/jekyll-reveal.git slides
```

Create a slide

```
cd slides
touch _slides/prism-bloopers.md
$EDITOR _slides/prism-bloopers.md
```

```md
---
title: Prism Bloopers
---

# Surveillance Lols!

---

![](http://cdn3.vox-cdn.com/assets/4717906/VpmftGR__2_.gif)

haha we have fun here

---

## but seriously
```

To test locally, run `jekyll serve` and visit `http://localhost:4000/slides/`.

Open a pull request to submit slides!

## License

[MIT](LICENSE.md)
