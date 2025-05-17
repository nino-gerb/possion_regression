# 🧮 Poisson Regression Analysis of Apprentice Migration

This repository contains an applied statistical analysis investigating factors influencing the number of apprentices migrating from various Scottish counties to Edinburgh between 1775 and 1799.

## 📄 Report Downloads

You can access the full report in the following formats:

- 📘 [View report (HTML version)](./poisson_apprentice_report.html)
- 📕 [Download report (PDF version)](./poisson_apprentice_report.pdf)

The report includes:
- Exploratory Data Analysis (EDA)
- Poisson and Zero-Inflated Poisson modeling
- Model diagnostics and overdispersion assessment
- Final model interpretation
- Visualizations of marginal effects

## 📊 Dataset

The dataset used is publicly available from the University of Florida Statistics archive:

📁 **[apprentice.txt](http://users.stat.ufl.edu/~winner/data/apprentice.txt)**  
It contains:
- `region`: County name  
- `apprentices`: Number of apprentices migrating to Edinburgh  
- `distance`: Distance from Edinburgh (miles)  
- `population`: Regional population (in thousands)  
- `urban`: Urbanization index  
- `direction`: Cardinal direction relative to Edinburgh (North, West, South)  

The dataset consists of 33 historical Scottish counties.

## 📊 Methods

The analysis was conducted using R and R Markdown, leveraging the following packages:
- `ggplot2`
- `dplyr`
- `MASS`
- `pscl`
- `broom`
- `patchwork`

Statistical modeling follows:
- **Lovett & Flowerdew (1989)**: *Analysis of Count Data Using Poisson Regression*
- **Agresti (2007)**: *Categorical Data Analysis*
- **Dobson & Barnett (2018)**: *Generalized Linear Models*

## 📁 Files in this repo

| File                          | Description                           |
|-------------------------------|---------------------------------------|
| `poisson_apprentice_report.Rmd` | R Markdown source file                |
| `poisson_apprentice_report.html` | HTML version of the report (viewable) |
| `poisson_apprentice_report.pdf` | PDF version of the report (printable) |
| `README.md`                  | This file                              |

## 📚 Citation

If referencing this project, please cite:
> Gerber, N. (2025). *Poisson Regression Analysis of Apprentice Migration*. Master’s coursework project, EPFL.

---

Feel free to open an issue if you have questions about the models or methodology.