---
permalink: /jupyter/
author_profile: true
---

## Introduction to Jupyter Notebook

In code cells you can write standard Python:



```python
import math
import csv
```


```python
x = 4*math.pi
math.sqrt(2**x)
```

## Cell Types

In these cells you can use:

* Markdown
* LaTeX

So you can add comments to your code explaining it. For example:

$m = \frac{m_0}{\sqrt{1-v^2/c^2}}$

## Two modes

Command mode and Edit mode


```python
import requests
resp = requests.get("https://quentinsf.com")
resp.content
```

## Some basic operations and keystrokes:

Toggling toolbars.

* Return and Esc
* A and B (New cell Above OR Below)
* X, C, V (Cut, Copy, Paste)
* DD (Delete)

The different types of Return:

* Shift-Return (Execute and Exit)
* Ctrl-Return (Execute and Stay in place)
* Alt-Return (Execute and Create new cell below)
