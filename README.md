# Mortgage Refinance and Investment Simulation Tool

This project is a web-based tool developed with Python and Flask to help users evaluate the financial impact of refinancing loans and simulate investment performance. It is designed to be accessible for users without a technical background.

## Features

### Graphical User Interface
- Built using **Python and Flask**, allowing users to easily input:
  - Interest rate
  - Loan term
  - Loan amount
- Provides:
  - Estimated breakeven point
  - Long-term savings from refinancing
  - Monthly payment comparisons

### ETF Data Integration
- Collects and integrates ETF data from public financial websites.
- Enables simulation of periodic investments (e.g., weekly, biweekly, monthly) using historical ETF price trends.
- Helps users understand how investment strategies perform under various market conditions.

### Simulation Capabilities
- Calculates:
  - Cumulative investment value over time
  - Expected returns and growth rate
  - Profitability and cost comparisons between current and new loan terms

## Technologies Used

- `Python` – core application logic
- `Flask` – backend framework and web routing
- `Pandas` – data handling and calculations
- `BeautifulSoup` – scraping ETF data from websites
- `Matplotlib` – optional chart visualization (if included)
