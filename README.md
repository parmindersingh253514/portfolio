# Data Visualisation e-Portfolio

Harper Adams University | SQ4012 Data Visualisation | Deadline: 15 January 2026

## Overview

E-portfolio demonstrating data visualisation theory and practice using the Grammar of Graphics framework.

## Contents

- **Task 1**: Planning a Graphic (SPEC) - `tasks/01-spec.qmd`
- **Task 2**: Grammar of Graphics Theory - `tasks/02-grammar-of-graphics.qmd`
- **Task 3**: Complex Graphics with Design Variants - `tasks/03-complex-graphics.qmd`
- **Task 4**: Animation with gganimate - `tasks/04-animation.qmd`
- **Task 5**: Quarto Portfolio Website (this site)

## Quick Start

```bash
# Install packages
install.packages(c("ggplot2", "gganimate", "tidyverse", "gapminder", "viridis", "scales"))

# Render the website
quarto render

# Preview locally
quarto preview
```

## Project Structure

```
portfolio/
├── _quarto.yml
├── index.qmd
├── styles.css
├── tasks/
│   ├── 01-spec.qmd
│   ├── 02-grammar-of-graphics.qmd
│   ├── 03-complex-graphics.qmd
│   ├── 04-animation.qmd
│   └── about.qmd
└── README.md
```

## Key Datasets

- **faithfuld** (Tasks 1-3): Old Faithful geyser data from ggplot2
- **gapminder** (Task 4): Global health and wealth data

## References

- Wilkinson, L. (2005). *The Grammar of Graphics*. Springer.
- Wickham, H. (2016). *ggplot2: Elegant Graphics for Data Analysis*. Springer.
- Heer, J., & Bostock, M. (2010). Animated transitions in statistical data graphics. *IEEE TVCG*, 16(6), 989–997.

