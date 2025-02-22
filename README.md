# CS5565: Statistical Data Analysis

## Description
This repository contains datasets and R project files for statistical analysis and machine learning tasks, primarily used in **CS5565** coursework. The datasets include information on credit, income, advertising, and more. The repository also contains an R project file and associated history/log files for reproducibility.

## Repository Structure
- **`Credit.csv`** → Dataset related to credit data analysis.
- **`Income1.csv`** → Dataset related to income analysis.
- **`Advertising.csv`** → Dataset related to advertising and marketing data.
- **`CS5565_HW1.Rproj`** → R project file for organizing scripts and analyses.
- **`intro_to_R_lab`** → Lab materials introducing R programming.
- **`.RData`** → Saved R workspace for quick access to previous sessions.
- **`.Rhistory`** → Command history from R sessions.

## Setup Instructions
### Prerequisites
Ensure you have **R** and **RStudio** installed along with necessary packages. You can install dependencies using:

install.packages(c("tidyverse", "ggplot2", "dplyr", "caret"))

## Running the Analysis

### Clone this repository:

git clone https://github.com/your-username/CS5565-Data-Analysis.git
cd CS5565-Data-Analysis

### Open `CS5565_HW1.Rproj` in RStudio.

### Load datasets and start analysis using:
credit_data <- read.csv("Credit.csv")
income_data <- read.csv("Income1.csv")
advertising_data <- read.csv("Advertising.csv")

head(credit_data)  # Preview data

## Data Overview

### Credit Data (`Credit.csv`)
- Contains financial and credit-related variables.
- Can be used for regression or classification models.

### Income Data (`Income1.csv`)
- Provides income details with possible demographic attributes.
- Useful for exploratory data analysis and predictive modeling.

### Advertising Data (`Advertising.csv`)
- Contains advertising spend and sales data.
- Suitable for marketing analytics and regression models.

## Contributions
Contributions are welcome! Feel free to fork this repository and submit pull requests.

## Author
- **Alexander Dowell**

## License
This project is for educational purposes and does not require a license.
