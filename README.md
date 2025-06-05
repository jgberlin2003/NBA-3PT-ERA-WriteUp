# NBA Statistics Over the 3-Point Era

This brief write up explores how various aspects of NBA gameplay have changed since the introduction of the 3-point line in 1980. As a basketball fan, I was curious to see whether the rise in 3-point shooting has influenced other parts of the game, including scoring, free throws, and personal fouls.

## 📊 Project Overview

Using team-level NBA box score statistics from 1980 to 2024, I analyzed trends in:

- 3-point attempts per game
- Free throws attempted per game
- Personal fouls per game
- Points scored per game

The goal was to visualize how the game has evolved over time, and whether there are correlations between the rise in 3-point attempts and other game dynamics.

## 🗂️ Files Included

- `NBA_3PT_ERA_Analysis.Rmd`: The R Markdown source file with all code and commentary.
- `NBA_3PT_ERA_Analysis.pdf`: A rendered PDF version of the final report.
- `data/nba_team_stats.csv`: The dataset used in this analysis (source: Kaggle / Basketball-Reference).
- `README.md`: This file.

## 📌 Key Findings

- The number of 3-point attempts has steadily increased every year since 1980.
- Points per game dipped in the late 90s and early 2000s, despite moderate 3-point growth and decent free throw volume.
- Both free throws and personal fouls per game have decreased over time—likely a result of the shift toward more perimeter-oriented play.

## 🔍 Data Source

The data was downloaded from [Kaggle](https://www.kaggle.com/) but originally sourced from [Basketball-Reference](https://www.basketball-reference.com/), a trusted resource for basketball statistics.

## ▶️ How to Run

To reproduce the analysis:

1. Open the `.Rmd` file in RStudio.
2. Make sure the `Team Stats Per Game.csv` file is placed in a `data/` subfolder.
3. Install the required packages (see below).
4. Knit the file to PDF or HTML.

### Required R Packages

- `tidyverse`
- `ggplot2`
- `dplyr`
- `readr`

You can install them using:
```r
install.packages(c("tidyverse", "ggplot2", "dplyr", "readr"))
