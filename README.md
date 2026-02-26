# EightPaint

![EightPaint Screenshot](./image_2026-02-26_05-02-30.png)

EightPaint is a very small hex-grid painting experiment written in plain HTML and JavaScript.

Click anywhere on the grid and it colors the selected hex plus its neighbors with a random color.  
That's the whole idea.

No framework, no build system, no dependencies. Just a canvas and some hex math.

---

## What It Does

- Draws a full-screen grid of pointy-top hexagons
- Clicking a hex colors that hex and its neighbors
- Each click generates a random color cluster
- The grid resizes with the browser window

That's it. It's basically a colorful hex click toy.

---

## How To Run

Clone the repo and open the HTML file.

```bash
git clone https://github.com/yourusername/eightpaint
cd eightpaint
open index.html
