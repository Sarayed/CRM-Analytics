# Customer CLTV Prediction and Segmentation

## Overview

This repository contains a Jupyter notebook for predicting Customer Lifetime Value (CLTV) and segmenting customers to enhance marketing strategies. By estimating CLTV over a six-month period and analyzing customer behavior, this project aims to improve marketing targeting and potentially boost ROI by 20%.

## Table of Contents

- [Introduction](#introduction)
- [Methodology](#methodology)
  - [Data Preparation](#data-preparation)
  - [RFM Analysis](#rfm-analysis)
  - [CLTV Estimation](#cltv-estimation)
  - [Model Refinement](#model-refinement)
  - [Segmentation](#segmentation)
- [Results](#results)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Introduction

In this project, we developed a method to predict Customer Lifetime Value (CLTV) and segment customers to enhance marketing strategies. By integrating customer behavioral analysis with predictive modeling, we aim to enable precise marketing targeting and strategic decision-making.

## Methodology

### Data Preparation

1. **Data Collection**: Gathered data for over 1 million customers.
2. **Normalization**: Normalized the CLTV results and merged them with existing customer data.

### RFM Analysis

- **Recency (R)**: Time since the last purchase.
- **Frequency (F)**: Number of purchases in a given period.
- **Monetary Value (M)**: Total amount spent by the customer.

RFM analysis helps in understanding customer behavior and segmenting them based on their purchase patterns.

### CLTV Estimation

- **Modeling Frequency and Recency**: Used BG/NBD (Beta Geometric/Negative Binomial Distribution) model.
- **Modeling Transaction Value**: Applied Gamma-Gamma model.

These models predict the number of future transactions and the monetary value of these transactions, respectively, allowing for CLTV estimation over a six-month period.

### Model Refinement

Refined the CLTV model with insights from RFM analysis to enhance accuracy, potentially leading to a 20% increase in ROI.

### Segmentation

Using the predicted CLTV and RFM scores, customers were segmented for targeted marketing and strategic decision-making.

## Results

The refined CLTV model empowered precise customer segmentation, enhancing marketing targeting and potentially boosting ROI by 20%.

## Usage

To reproduce the results or apply the methodology to your own dataset:

1. **Clone the repository**:
    ```bash
    git clone https://github.com/Sarayed/CRM-Analytics.git
    ```
2. **Navigate to the repository**:
    ```bash
    cd CRM-Analytics
    ```
3. **Open the Jupyter notebook**:
    ```bash
    jupyter notebook crm-analytics.ipynb
    ```
4. **Run the cells in the notebook** to perform the analysis.

## Contributing

Contributions are welcome! Please read the [CONTRIBUTING](CONTRIBUTING.md) document for guidelines.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

Feel free to reach out with any questions or feedback. Happy coding!
