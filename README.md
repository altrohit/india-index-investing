# Investment Analysis Project

## Overview

This project analyzes investment funds, specifically focusing on the Nifty Next 50 index. It utilizes historical data from Yahoo Finance and CSV files to provide insights into various funds' performance metrics.

## Requirements

- Python 3.x
- Pandas

## Installation

To set up the project, ensure you have the required libraries installed. You can install them using pip:

```bash
pip install pandas
```

## Data Sources

- **Nifty Next 50 Fund Data**: Loaded from a CSV file located in the `data` directory.
- **Market Data**: Historical data for Nifty 50 and Nifty Next 50 is fetched using the `yfinance` library.

## Usage

1. **Load Data**: The project begins by loading the Nifty Next 50 fund data from a CSV file.
2. **Fetch Historical Data**: It fetches historical market data for Nifty 50 and Nifty Next 50 indices over the last 10 years.
3. **Analyze Performance**: The project includes benchmarks for various indices, allowing for performance comparisons.

## Output

The analysis will generate tables displaying fund performance metrics, including:

- Expense ratios
- Tracking errors
- Annualized returns over different periods

## Future Improvements

- Collect data for all funds using APIs.
- Use more sophisticated statistical models to analyze the data.

## Contributing

Contributions are welcome! Please submit a pull request or open an issue for any enhancements or bug fixes.

## License

This project is licensed under the MIT License.
