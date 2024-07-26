# SCL Analysis Project

## Overview

The Capital Asset Pricing Model (CAPM) Analysis project aims to evaluate the performance of selected stocks in relation to market risk. This project leverages historical stock prices, market returns, and risk-free rates to compute expected returns, alpha, and beta, and visualizes the relationships through scatter plots and the Security Characteristic Line (SCL).


## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Features](#features)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Installation

1. **Clone the repository**:
   ```
   git clone https://github.com/ejb1987/CAPM.git
   cd CAPM
## Install required packages:
Make sure you have pip installed. Then run:
   ```
   pip install -r requirements.txt
   ```
## Usage
Open the Jupyter Notebook:
```
jupyter notebook CAPM.ipynb
```

Input your selected stock ticker (e.g., AAPL for Apple Inc.). For UK companies, use the format ticker.L (e.g., BP.L for BP).

Run the cells in the notebook to perform the CAPM analysis. You will obtain:

1. Average annual returns and variance for the selected stock and the corresponding market index (US or UK).
2. The computation of CAPM beta and Jensen's alpha, which quantify the sensitivity of the stock's returns to market movements and the stock's excess return, respectively.
3. A scatter plot comparing the weekly returns of the stock and the market index, along with the Security Characteristic Line (SCL), which represents the relationship between the excess return of the stock and the excess return of the market.

## Features
* Average Annual Return Calculation: Computes the expected annual return for the selected stock and its corresponding market index.
* Risk-Free Rate Adjustment: Automatically selects the appropriate market index and risk-free rate based on the stock market.
* Beta and Alpha Calculation: Analyzes the stock's sensitivity to market movements and calculates its excess return, enabling an understanding of its risk-adjusted performance.
* Visualizations: Displays scatter plots of weekly returns and the Security Characteristic Line (SCL), providing insights into the stock's risk-return profile.

## Contributing
Contributions are welcome! Please feel free to fork the repository and submit a pull request. If you have any suggestions or find any bugs, please open an issue.

## License
This project is licensed under the MIT License. See the LICENSE file for details.

# Contact

Ehsan - ehsan.j.b.66@gmail.com

Project Link: https://github.com/ejb1987/CAPM
