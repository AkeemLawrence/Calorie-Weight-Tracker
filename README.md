# Calorie & Weight Tracker

## Overview

Calorie & Weight Tracker is an interactive R project for recording daily calorie intake and body weight, reviewing daily summaries, visualizing trends, and optionally exporting tracking data to Google Sheets.

The project demonstrates practical use of R for data collection, persistent local storage, data manipulation, visualization, user input validation, and external service integration.

## View the Project

- [Rendered HTML](Akeem-Calorie-Tracker.html)
- [RMarkdown Source](Akeem-Calorie-Tracker.Rmd)

## Features

- Log meals and calorie intake
- Log body weight
- Automatically save records between sessions
- Reload historical tracking data
- Calculate daily calorie totals
- View calorie and weight histories
- Visualize calorie intake over time
- Visualize body-weight trends
- Validate interactive user input
- Optionally export data to Google Sheets

## Technologies

- R
- RMarkdown
- tidyverse
- dplyr
- readr
- ggplot2
- googlesheets4
- Google Sheets

## Running the Tracker

Open `Akeem-Calorie-Tracker.Rmd` in RStudio.

Install the primary dependency if needed:

```r
install.packages("tidyverse")
