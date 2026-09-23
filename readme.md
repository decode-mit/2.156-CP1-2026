## Linkage Synthesis Challenge Problem

This challenge problem is focused on synthesizing planar linkage mechanisms such that a specific output curve is traced using the mechanism. For this project you are tasked with synthesizing linkage mechanisms to trace 3 different output shapes. Further you are tasked with synthesizing mechanisms such that the total material used for the mechanisms in minimized. 

<img src="https://i.ibb.co/qsPC0gC/2021-09-13-0hl-Kleki.png" alt="Numbered Mechanism" border="0">

The three target shapes to trace are shown below:

| Kangaroo | Round | No ear / tail |
|:---:|:---:|:---:|
| <img src="kangaroo.png" alt="Kangaroo" width="250"> | <img src="kangaroo_round.png" alt="Kangaroo (round)" width="250"> | <img src="kangaroo_no_ear_no_tail.png" alt="Kangaroo (no ear, no tail)" width="250"> |

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
