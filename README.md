<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">

</head>
<body>

  <h1>📈 Stock Analysis Dashboard: Tesla and GameStop</h1>
  
  <p>
    This project aims to analyze and visualize stock performance for Tesla (TSLA) and GameStop (GME) in the context of hedge fund short selling, stock price fluctuations, and company profitability. Using data sourced through the <code>y-finance</code> API, we build a dashboard that compares stock price trends against company profits. This dashboard provides insights into stock valuation and trading dynamics, especially in scenarios of speculative trading and short selling.
  </p>

  <h2>🔍 Project Overview</h2>
  <p>
    Stock prices fluctuate based on various factors, including:
    <ul>
      <li><strong>📊 Outstanding Shares</strong>: The number of shares available for trading.</li>
      <li><strong>💹 Profit and Profit Growth</strong>: If a company's profit grows, its stock price usually follows. Investors may choose to buy stock based on positive profit forecasts.</li>
    </ul>
  </p>
  <p>
    Short selling allows investors to profit from declining stock prices:
    <ol>
      <li><strong>💼 Borrowing the Stock</strong>: An investor borrows and sells a stock, betting the price will drop.</li>
      <li><strong>📉 Buying Back the Stock</strong>: If the price decreases, the investor buys the stock back at a lower price and returns it, profiting from the difference.</li>
    </ol>
  </p>
  <p>
    However, if the stock price rises instead, the short seller incurs a loss.
  </p>

  <h3>📝 Case Studies</h3>
  <p>
    <strong>🚗 Tesla</strong>: A few years ago, Tesla attracted many short sellers due to financial instability. However, as Tesla became profitable, its stock price surged, leading to losses for short sellers.
  </p>
  <p>
    <strong>🎮 GameStop</strong>: In 2021, members of the Reddit forum WallStreetBets collectively purchased GameStop shares, driving the price up despite the company’s weak financials. Hedge funds holding short positions on GameStop incurred substantial losses.
  </p>

  <h2>🎯 Objectives</h2>
  <ul>
    <li>Extract stock data for Tesla and GameStop using the <code>y-finance</code> API.</li>
    <li>Analyze the relationship between stock prices and company profits over time.</li>
    <li>Build a dashboard to visualize:
      <ul>
        <li>Stock price trends for Tesla and GameStop</li>
        <li>Profit data and trends overlaid on stock prices</li>
      </ul>
    </li>
  </ul>

  <h2>📁 Project Structure</h2>
  <ul>
    <li><strong>🔄 Data Collection</strong>: Using the <code>y-finance</code> API to retrieve stock prices (ticker data) and financial data for TSLA and GME.</li>
    <li><strong>📊 Visualization</strong>: Graphs and charts showcasing the stock price vs. profit trend.</li>
    <li><strong>📈 Analysis</strong>: Insights into the stock's response to profit growth and other speculative factors.</li>
  </ul>

  <h2>🚀 Installation</h2>
  <ol>
    <li>Clone this repository:
      <pre><code>git clone https://github.com/yourusername/stock-analysis-dashboard.git</code></pre>
    </li>
    <li>Install the required dependencies:
      <pre><code>pip install yfinance matplotlib pandas</code></pre>
    </li>
  </ol>

  <h2>📖 Usage</h2>
  <ol>
    <li>Run the data extraction script to fetch historical stock data and company profits.</li>
    <li>Launch the dashboard to view visualizations comparing stock price and profit trends for Tesla and GameStop.</li>
  </ol>

  <h2>📂 Access the Notebook</h2>
  <p>For further analysis, access the <a href="Gamestop-stock-vs-Tesla-stock--stock-analysis/Final Assignment (2).ipynb" target="_blank"><strong>Jupyter Notebook file</strong></a> located in this repository. This notebook contains code, visualizations, and additional insights into the project.</p>

  <h2>📊 Project Output</h2>
  <img src="Gamestop-stock-vs-Tesla-stock--stock-analysis/image1.png" alt="GME vs Tesla Stock Prices" />
  
  <p><img src="Gamestop-stock-vs-Tesla-stock--stock-analysis/image.png" alt="GME vs Tesla Stock Prices" /></p>
  <p>
    The dashboard allows users to explore the relationship between stock price and profitability over time, especially in cases where external influences drive price changes unrelated to financial fundamentals.
  </p>

  <h2>📜 License</h2>
  <p>
    This project is licensed under the MIT License. See the <a href="LICENSE">LICENSE</a> file for details.
  </p>

</body>
</html>
