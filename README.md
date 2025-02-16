# stock-market

![image](https://github.com/user-attachments/assets/a052c937-14d2-4426-9c4f-bc409f6dd2e1)

Stock Market Financial Dashboard
This is a Project that I created in my free time. I made a simple financial dashboard using Python and the Bokeh Python library. The dashboard can display the stock prices of a company over time using Yahoo Finance Python Package, and the user can also add Indicators to help them make better investment decisions. The indicators include 100 Day SMA, 30 Day SMA, Linear Regression Line, 50 Day EMA, RSI, MACD, Bollinger Bands.

Features:
Real-Time Stock Data: Fetch and display the latest stock prices and market data for various stocks.

Historical Data Visualization: View historical stock prices with interactive charts to analyze trends over time.

Stock Comparison: Compare multiple stocks side-by-side to evaluate performance metrics.

Technical Indicators: Calculate and visualize common technical indicators (e.g., moving averages, RSI) to assist in trading decisions.

More Visualization Tools: Added more visualization tools such as heatmaps, scatter plots, and bar charts to provide a more comprehensive view of the Stocks.

Responsive Design: Access the dashboard from various devices with a user-friendly interface.

Data Export: Export portfolio data and charts in a PNG Format for offline analysis.

Installation
To download this Repository You can download the zip file or Clone the Project Repository using Git with the below command:

git clone https://github.com/DhruvAthaide/StockMarketFinancialDashboard.git
Move the Command Line to the Project Directory:

cd '.\StockMarketFinancialDashboard\'
Then Run the following commands to install the Script Requirements:

pip install -r requirements.txt
Then you can go ahead and run the Dashboard using the command:

bokeh serve --show main.py
