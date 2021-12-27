# Risk-Return Analysis of Large Funds

This analysis looks at four funds to determine the one with the most desirable risk-reward profile based on: daily returns, standard deviations, Sharpe ratios, and betas. A secondary notebook expands the analysis to include the Sortino, Calmar, Information, and M2 Ratios.

## Technologies

This project leverages python 3.7 and [pandas](https://pandas.pydata.org/). The analysis is carried out in a [jupyter](https://jupyter.org/) notebook.

## Installation Guide

Clone the repository and confirm that python 3.7 or greater, pandas, and jupyter are installed.

```python
$ python -V
Python 3.7.x
$ pip install pandas
$ pip install jupyterlab
```

## Usage

To view the analysis carried out in the notebooks click `risk_return_analysis.ipynb` or `additional_risk_return_ratios.ipynb` in the file directory of this repo, or click [here](https://github.com/jmischung/Bitcoin-Arbitration-Analysis/blob/main/crypto_arbitrage.ipynb) or [here](https://github.com/jmischung/Portfolio-Risk-Analysis/blob/main/additional_risk_return_ratios.ipynb) respectively. To interact with the notebooks run `jupyter lab` from the directory where the notebooks are stored.  

## Notebooks  

**risk\_return\_analysis.ipynb**  
This is the primary notebook where the full analysis of the funds is carried out.

**additional\_risk\_return\_ratios.ipynb**  
This notebook is supplementary to the primary notebook. It explores additional risk-adjusted return metrics to see if they provide additional context and might have changed our conclusion in the primary notebook.  

## Files & Directories  

**Resources**  
Contains CSV file provided for this analysis.  

**whale_navs.csv**  
Daily closing prices from 2014-10-01 to 2020-09-11 for:  
 - Soros Fund Management LLC  
 - Paulson & Co. Inc.  
 - Tiger Global Management LLC  
 - Berkshire Hathaway Inc.  
 - S&P 500

## Contributors

Josh Mischung: [josh@knoasis.io](josh@knoasis.io), [LinkedIn](https://www.linkedin.com/in/joshmischung/)

## License

MIT License

Copyright (c) [2022] [Joshua Mischung]

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
