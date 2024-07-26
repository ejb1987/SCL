# CAPM Analysis Project

## Overview

The Capital Asset Pricing Model (CAPM) Analysis project aims to evaluate the performance of selected stocks in relation to market risk. This project leverages historical stock prices, market returns, and risk-free rates to compute expected returns, alpha, beta, and visualize the relationships through scatter plots and the CAPM line.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Features](#features)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/ejb1987/CAPM.git
   cd CAPM
## Install required packages:
Make sure you have pip installed. Then run:
   ```   pip install -r requirements.txt ``

## Usage
Open the Jupyter Notebook:
jupyter notebook CAPM.ipynb
Input your selected stock ticker (e.g., AAPL for Apple Inc.) and the market index (e.g., ^GSPC for S&P 500). If the stock is a UK company, use the format ticker.L (e.g., BP.L for BP).

Run the cells in the notebook to perform the CAPM analysis. You will see:

Average annual returns and variance for both the selected stock and the market index.
The calculation of CAPM beta and alpha.
A scatter plot comparing weekly returns of the stock and the index, along with the CAPM line.

## Features
Average Annual Return Calculation: Computes the expected annual return for the selected stock and market index.
Risk-Free Rate Adjustment: Automatically selects the appropriate risk-free rate based on the stock's market.
Beta and Alpha Calculation: Analyzes the stock’s sensitivity to market movements and calculates its excess return.
Visualizations: Displays scatter plots of weekly returns and the CAPM line for better insights.
Contributing
Contributions are welcome! Please feel free to fork the repository and submit a pull request. If you have any suggestions or find any bugs, please open an issue.

## License
This project is licensed under the MIT License. See the LICENSE file for details.

# Contact

Ehsan - ehsan.j.b.66@gmail.com
Project Link: https://github.com/ejb1987/CAPM
