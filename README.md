# tesla-gamestop-analysis
Analyzing Historical Stock/Revenue Data and Building a Dashboard
This project is part of the IBM Data Science course lab. It uses yfinance and web scraping techniques to extract, clean, and visualize stock and revenue data for Tesla (TSLA) and GameStop (GME).

**✅ Project Objectives**
1. Extract historical stock price data using yfinance
2. Scrape revenue data from static HTML pages using BeautifulSoup or pandas.read_html()
3. Clean and preprocess both datasets
4. Visualize stock price vs revenue using interactive Plotly graphs
5. Share findings via a Jupyter Notebook

**📁 Files Included**
1. stock_revenue_analysis.ipynb – Main notebook with all code, outputs, and visualizations
2. README.md – You’re reading it!

**📦 Libraries Used**
1. yfinance
2. pandas
3. requests
4. BeautifulSoup (bs4)
5. plotly
6. matplotlib 

**📌 Instructions**
To run this notebook:
1. Clone the repo or download the .ipynb file
2. Install required libraries:
-yfinance pandas bs4 plotly
3. Open in Jupyter or VS Code and run all cells

**🧪 Example Use Cases:**
1. yfinance: tesla = yf.Ticker("TSLA")
2. pandas: df = pd.DataFrame(...)
3. bs4: soup = BeautifulSoup(html, 'html.parser')
4. plotly: Used in make_graph() to generate interactive graphs

**✍️ Author**
Hong Yaw (IBM Skills Network Course Participant)
