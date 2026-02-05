# ✅ Day 03 — Python Fundamentals II + data Handling & Visualization

![Python](https://img.shields.io/badge/Python-Pandas-blue?logo=python)
![Topic](https://img.shields.io/badge/Topic-Data%20Subsetting-green)
![Lecture](https://img.shields.io/badge/Lecture-03-orange)

---


 this lecture covers:

- Subsetting rows using `loc` and `iloc`
- Subsetting columns
- Selecting ranges
- Accessing specific cells
- Grouped statistics (mean)
- Frequency counts
- Data visualization principles
- Types of graphs (Histogram, Scatter, Pie, etc.)

(Source: Lecture 3 Slides) :contentReference[oaicite:1]{index=1}

---

## 📂 Dataset Used: Gapminder

```python
import pandas as pd

url = "https://raw.githubusercontent.com/jennybc/gapminder/main/inst/extdata/gapminder.tsv"
df = pd.read_csv(url, sep="\t")
df.head()
