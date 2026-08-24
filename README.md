# AMD

A professional multi-page interactive website that teaches the complete core concepts of **NumPy**, **Pandas**, **Matplotlib**, and **Seaborn** with clear explanations and working code examples.

![Dark Theme](https://img.shields.io/badge/Theme-Dark-12131A?style=flat-square)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)

---

## Overview

**AMD** is a beautifully designed, multi-page learning platform that covers the essential Python data science stack. It is **not** a single-page website — each library has its own dedicated page with a table of contents, detailed explanations, and ready-to-use code examples.

### Pages Included

| Page | Description |
|------|-------------|
| **Home** | Introduction + learning path + library overview cards |
| **NumPy** | Complete guide to arrays, broadcasting, ufuncs, linear algebra, random, etc. |
| **Pandas** | Series, DataFrame, GroupBy, merge, time series, missing data, and more |
| **Matplotlib** | Figures, axes, all major plot types, customization, 3D, animation |
| **Seaborn** | Statistical plots, themes, palettes, FacetGrid, PairGrid, and more |

---

## Features

- Dark professional theme with custom color palette
- 3D card tilt effect on hover
- Animated fluid background orbs
- Particle network canvas background
- Smooth scroll fade-in animations
- Sticky table of contents on content pages
- Copy-to-clipboard buttons for every code block
- Fully responsive design (mobile + desktop)
- Clean navigation between all pages

---

## Color Palette

| Element | HEX | Description |
|---------|-----|-------------|
| Primary Background | `#12131A` | Very Dark Navy / Charcoal Black |
| Card Gradient Start | `#2C2D24` | Muted Olive Green / Brown |
| Card Gradient End | `#4D4E3A` | Muted Olive Green / Brown |
| Accent Text | `#848B9E` | Muted Slate Gray |
| Primary Text | `#FFFFFF` | Pure White |
| Neon Blue / Lilac | `#B8C5F2` | Light Blue / Lilac Sparks |
| Neon Pink / Magenta | `#D95B83` | Magenta / Pink Crystals |

---

## Folder Structure

```
data-science-guide/
├── index.html              # Home page
├── numpy.html              # NumPy complete guide
├── pandas.html             # Pandas complete guide
├── matplotlib.html         # Matplotlib complete guide
├── seaborn.html            # Seaborn complete guide
├── css/
│   └── style.css           # All styles, colors, animations
├── js/
│   └── main.js             # Interactions, particles, tilt, copy buttons
├── assets/                 # (optional images / icons)
└── README.md               # This file
```

---

## How to Run

### Option 1 – Open directly
1. Download or clone the repository
2. Open `index.html` in any modern browser (Chrome, Edge, Firefox)

### Option 2 – Local server (recommended)
```bash
# Using Python
cd data-science-guide
python -m http.server 8080
```
Then open: [http://localhost:8080](http://localhost:8080)

### Option 3 – Live Server (VS Code)
1. Install the **Live Server** extension
2. Right-click `index.html` → **Open with Live Server**

---

## Technologies Used

- **HTML5** – Semantic structure
- **CSS3** – Custom properties, gradients, 3D transforms, animations
- **Vanilla JavaScript** – Particle system, 3D tilt, intersection observers, clipboard API
- **Google Fonts** – Inter + JetBrains Mono

No frameworks or build tools required — pure frontend.

---

## Topics Covered

### NumPy
- ndarray fundamentals
- Array creation methods
- Indexing, slicing, fancy indexing
- Reshaping, views & copies
- Universal functions (ufuncs)
- Broadcasting rules
- Aggregation
- Boolean logic & masking
- Linear algebra (`numpy.linalg`)
- Random number generation
- File I/O
- Structured & masked arrays

### Pandas
- Series & DataFrame
- Reading / writing data (CSV, Excel, SQL, Parquet…)
- Indexing (`.loc`, `.iloc`, `query`)
- Missing data handling
- GroupBy & aggregation
- Merge, join, concatenate
- Reshaping (pivot, melt, stack)
- Time series
- Categorical data
- Styling & display options

### Matplotlib
- Pyplot vs Object-Oriented API
- Figure & Axes
- Line, scatter, bar, histogram, pie, box, violin, contour, imshow
- Customization (spines, ticks, annotations, grids)
- Subplots & GridSpec
- 3D plots
- Animation
- Styles & `rcParams`
- Saving figures

### Seaborn
- Themes & styles
- Color palettes
- Relational plots (`relplot`, `scatterplot`, `lineplot`)
- Distribution plots (`histplot`, `kdeplot`, `displot`, `jointplot`, `pairplot`)
- Categorical plots (`catplot`, box, violin, bar, count…)
- Regression plots
- Matrix plots (heatmap, clustermap)
- Multi-plot grids (FacetGrid, PairGrid, JointGrid)
- Context & scaling

---

## Browser Support

Works best on modern browsers:
- Google Chrome
- Microsoft Edge
- Mozilla Firefox
- Safari

---

## Author

Created as a professional learning resource for the Python data science visualization stack.

---

## License

This project is open source and free to use for learning and personal projects.
```
