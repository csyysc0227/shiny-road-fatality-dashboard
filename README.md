# shiny-road-fatality-dashboard
Road Fatality Shiny Dashboard for City Size Analysis

# Road Fatality Shiny Dashboard

This Shiny application analyzes road fatality rates across different Belgian cities categorized by city size.  
It includes:

### Features
- Trend analysis by city size (Large, Medium, Small, National)
- Distribution visualization (boxplots + jitter)
- Optional linear trend lines
- Fully automated Excel loading and cleaning

### Files
- global.R – loads data, cleans, classifies city size  
- ui.R – defines layout and navigation  
- server.R – creates plots and backend logic  

### How to Run This App
1. Ensure R and RStudio are installed.
2. Install required packages:

```R
pkg <- c("readxl","dplyr","tidyr","ggplot2","stringr","shiny","bslib")
install.packages(pkg)
