# Clustering Analysis on Small Business Data

## Project Overview

This repository contains an analysis focused on identifying patterns and grouping states in the U.S. based on their small business economic data. Small businesses represent a crucial part of the U.S. economy, comprising 99% of all businesses and almost 50% of employment. Our goal is to use clustering techniques to better understand the small business landscape and provide insights for potential policy-making.

## Data Source

The dataset used in this project is derived from the U.S. Small Business Administration’s annual report. It includes economic indicators for small businesses across 51 U.S. states. The dataset consists of 16 variables and contains missing values (represented as asterisks). A detailed description of each variable can be found in the accompanying data dictionary.

## Getting Started

### Prerequisites

To run this project, you will need the following software and packages:

- **R** (version 4.0 or higher)
- **tidyverse** package
- **cluster** package
- **factoextra** package

Install the required R packages by running:

```r
install.packages(c("tidyverse", "cluster", "factoextra"))
