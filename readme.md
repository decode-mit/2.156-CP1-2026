## Linkage Synthesis Challenge Problem

This challenge problem focuses on synthesizing planar linkage mechanisms that trace specified output curves. You are tasked with designing mechanisms for three different target shapes.

Our ultimate goal is to reproduce the kangaroo meme, but we also provide two easier versions with progressively increasing difficulty. Through these three targets, you will see how the difficulty of linkage synthesis changes as the contour becomes less smooth and more geometrically complex.


<img src="https://i.ibb.co/qsPC0gC/2021-09-13-0hl-Kleki.png" alt="Numbered Mechanism" border="0">

The three target shapes to trace are shown below:

|  Smooth front view version | No ear / tail version | Kangaroo (original meme) |
|:---:|:---:|:---:|
| <img src="kangaroo_round.png" alt="Kangaroo (round)" width="250"> | <img src="kangaroo_no_ear_no_tail.png" alt="Kangaroo (no ear, no tail)" width="250">  | <img src="kangaroo.png" alt="Kangaroo" width="250"> |

with increasing difficulty.
## Pull the code
You can open the two notebook files in colab to run. If you want to run locally, pull the code to your computer:
```bash
git clone git@github.com:decode-mit/2.156-CP1-2026.git
cd 2.156-CP1-2026
```
## Create a Python 3.10 Environment with `uv`

This guide shows how to create a fresh Python 3.10 virtual environment using `uv` and install dependencies from `requirements.txt`.

```bash
uv venv --python 3.10 .venv
source .venv/bin/activate
```

##  Install dependencies
```bash
uv pip install -r requirements.txt
```
