# Stocks vs Inflation in R

## Overview
This project analyzes the relationship between **stock returns** and **inflation** using a **mock dataset** (`cpi_stock_data.csv`). The dataset contains annual CPI inflation rates and corresponding stock returns for 14 years (2010–2023). The analysis explores how inflation impacts investment returns and highlights the difference between **nominal** and **real** returns.

---

## Dataset
The dataset `cpi_stock_data.csv` includes the following columns:

| Column Name     | Description                              |
|-----------------|------------------------------------------|
| Year            | Calendar year                             |
| CPI_Inflation   | Annual CPI inflation (%)                  |
| Stock_Return    | Annual stock market return (%)            |

> **Note:** This dataset is **mock data created for educational and analytical purposes**.

---

## Objective
- Understand how inflation affects the real value of stock returns.
- Compare nominal vs inflation-adjusted returns.
- Visualize trends over the years to extract investment insights.

---

## Tools & Libraries
- **R Programming Language**
- **Tidyverse** for data manipulation and visualization
- **ggplot2** for plotting trends

```r
# Load libraries
library(tidyverse)
