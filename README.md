# Case Study: How Does a Bike-Share Navigate Speedy Success

## Overview
This project is a case study analysis conducted in R to showcase data-driven marketing strategy development, specifically for a bike-share company. It explores ways to increase membership by analyzing the behaviors of casual riders and annual members.

## Objectives
The main objective of this case study is to:
1. Design marketing strategies aimed at converting casual riders into annual members.
   
To achieve this, we aim to understand:
   - How annual members and casual riders differ.
   - Why casual riders might be interested in purchasing a membership.
   - How digital media can be leveraged to improve marketing efforts.

## Data
- **Source**: The dataset was downloaded from [Divvy Trip Data](https://divvy-tripdata.s3.amazonaws.com/index.html), provided by Motivate International Inc.
- **Description**: The data includes trip information such as rider type, trip duration, and trip dates, offering insights into how different rider segments use the bike-share service.

## Methodology
This analysis follows a structured workflow, with the following key steps:
1. **Data Cleaning**: Addressed missing values, formatted variables, and removed duplicates.
2. **Exploratory Data Analysis (EDA)**: Generated summary statistics and visualizations to identify patterns in rider behavior.
3. **Descriptive Analysis**: Calculated aggregate data and performed calculations to reveal differences between casual riders and annual members.
4. **Visualization**: Created plots to illustrate key insights, focusing on trends that could inform marketing strategies.
5. **Interpretation**: Provided actionable insights based on the findings, with recommendations for targeting casual riders.

## Results and Conclusions
- **Key Finding 1**: Marketing campaigns could be most effective on weekends, when casual riders book the highest number of rides.
- **Key Finding 2**: Thursday also represents a strong opportunity for marketing, as casual riders tend to have longer trip durations on this day.

## Repository Structure
```
├── data/
│   ├── data.csv                      # Dataset used for analysis
├── scripts/
│   ├── Capstone_1.R                  # Main analysis script
├── output/
│   └── Case Study Findings- 1.pdf    # Final report with findings
├── README.md                         # Project overview and instructions
└── requirements.txt                  # List of required packages
```

## How to Run the Code
1. Clone this repository:
   ```bash
   git clone https://github.com/justinsajanfrancis/case-study-1.git
   ```
2. Open the project in RStudio or your preferred R environment.
3. Install necessary packages by running:
   ```R
   install.packages(c("tidyverse", "conflicted"))
   ```
4. Run the analysis by executing the `Capstone_1.R` script.

## Requirements
- **R version**: [version, e.g., "4.1.0"]
- **Packages**: 
  - `tidyverse`: for data manipulation and visualization
  - `conflicted`: to manage package conflicts and ensure clean namespace usage

## Contact
For questions or collaboration, feel free to reach out to me at justinsajanfrancis@gmail.com


