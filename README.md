# Fund Managers' Performance Visualization

## Overview
This project visualizes the distribution of performance for actively managed funds in the U.S. compared to the S&P500 index. The representation employs a skewed bell curve, which provides a more intuitive grasp of the dataset's asymmetry, particularly highlighting the tiny percentage of true "Outliers".

## Requirements

- Jupyter Notebook
- Python
- Libraries: `numpy`, `matplotlib`, `scipy`

## Methodology

1. **Curve Fitting**: A skewed bell curve (or skew normal distribution) is fitted based on three primary conditions:
   - On average, the S&P500 has returned 10% over a 20-year period.
   - 85% of the fund managers underperform the index.
   - Only 0.5% of the fund managers consistently outperform the index by more than 3%.

2. **Visualization**: The fitted curve is plotted, segmented into three categories:
   - **Underperformers**: Those lagging behind the index.
   - **Outperformers**: Those beating the index but not by a significant margin.
   - **Outliers**: An elite group that consistently outperforms the index by over 3%.

3. **Interactivity in Jupyter**: The code is designed to run seamlessly in a Jupyter notebook, allowing users to execute cells and visualize the output immediately.

## Usage

1. Clone the repository.
2. Open the provided Jupyter notebook.
3. Run all cells to generate the visualization.

## Insights
The visualization underscores the rare phenomenon of consistent outperformance. It accentuates how most fund managers trail the S&P500 and how truly challenging it is to consistently beat the index by a considerable margin. Outliers like Warren Buffet, with their stellar returns, are not even part of the regular distribution.

## Acknowledgment
The project was inspired by key takeaways from the Drew Investment Management Annual Meeting.
