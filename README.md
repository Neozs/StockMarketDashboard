# Stock Market Dashboard Project

## Overview
This project aims to extract financial data for popular stocks (Tesla, Amazon, AMD, GameStop) and visualize it in a dashboard to identify patterns and trends. I am assuming the role of a Data Scientist/Analyst for a startup investment firm.

## Status
* Initial setup complete.
* Data extraction for Apple and AMD complete.
* Dashboard visualization in progress.

## Technologies
* Python
* JupyterLab
* Plotly
* y-finance API
* pandas
* matplotlib

## Project Structure
```
InvestmentFirm.ipynb      # Main notebook with all analysis and code
apple.json                # Downloaded Apple stock info
amd.json                  # Downloaded AMD stock info
README.md                 # Project documentation
```

## Installation
1. Clone this repository:
   ```sh
   git clone <your-repo-url>
   cd Stock-Market-Dashboard
   ```
2. Install required Python packages (in Jupyter or terminal):
   ```sh
   pip install yfinance matplotlib pandas requests plotly
   ```

## Usage
- Open `InvestmentFirm.ipynb` in JupyterLab or VS Code.
- Run each cell in order to:
  - Download and inspect stock data for Apple and AMD
  - Visualize share prices and dividends
  - Analyze key metrics for investment decisions

## Example Outputs
- Extracted country and sector for each stock
- Plots of historical share prices and dividends
- DataFrames with stock price history

## Results
- Successfully extracted and visualized data for Apple and AMD
- Ready to extend to other stocks (Tesla, Amazon, GameStop)

## Next Steps
- Add more stocks and KPIs
- Build interactive dashboard with Plotly
- Automate data updates

---

# How to Contribute
Feel free to fork the repo, open issues, or submit pull requests!