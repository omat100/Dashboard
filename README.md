# Dashboard App

A desktop data analysis tool built with Python and PyQt6. Load any CSV, explore it across 4 interactive graphs simultaneously, filter your data on the fly, and export everything to PDF.

---

## What it does

You load a CSV file and get a 2x2 grid of graphs — each one independently configurable. Pick your X axis, Y axis, chart type, and how you want the data aggregated. Change one graph without touching the others.

On the left is a filter sidebar that auto-generates based on your data. Categorical columns get a multi-select list. Numeric columns get a min/max range picker. Every filter you apply updates all four graphs instantly.

When you're done, hit Export PDF and all four graphs go into a single file.

---

## Features

- **Multi-graph view** — 4 panels side by side, each with its own settings
- **Chart types** — line, bar, scatter
- **Aggregations** — sum, mean, median, count
- **Dynamic filters** — auto-built from your CSV's columns (categorical + numeric)
- **Load any CSV** — not locked to one dataset
- **PDF export** — saves all 4 graphs in one go

---

## Getting started

**Requirements**
```
Python 3.10+
PyQt6
pandas
matplotlib
```

**Install dependencies**
```bash
pip install PyQt6 pandas matplotlib
```

**Run**
```bash
python main.py
```

Then hit **Load CSV** to open your own dataset, or drop a CSV in the project folder and update the default path in `main.py`.

---

## Project structure

```
dashboard_app/
├── main.py          # Entry point, App window, filter logic
├── README.md
└── your_data.csv    # Drop your CSV here
```

---

## Built with

- [PyQt6](https://pypi.org/project/PyQt6/) — GUI framework
- [pandas](https://pandas.pydata.org/) — data handling and aggregation
- [matplotlib](https://matplotlib.org/) — graph rendering

---

## Author

**Om Thakur**  
[github.com/omat100](https://github.com/omat100)
