# API-INTEGRATION-AND-DATA-VISUALIZATION

COMPANY: CODTECH IT SOLUTIONS

"NAME: KINGSTON

"INTERN ID: CTO4DG46

"DOMAIN: PYTHON PROGRAMMING

DURATION: 4 WEEEKS


MENTOR: NEELA SANTOSHStock Market Analysis Dashboard using Streamlit and Alpha Vantage
This Stock Market Analysis Dashboard is a real-time, interactive web application built using Streamlit, integrated with the Alpha Vantage API to provide up-to-date stock market insights. Designed for users who want a quick, clean, and data-driven way to monitor selected high-profile stocks, the dashboard offers both tabular and graphical analysis of recent stock price activity.

Core Technologies
The app is developed with:

Streamlit: For building the interactive UI and rendering charts/tables in a web browser.

Alpha Vantage API: To retrieve hourly stock price data.

Pandas: For data manipulation and structuring.

Seaborn & Matplotlib: For creating insightful visualizations.

User Interface
Upon launching the app, users are greeted with a clean title and a multi-select widget that allows them to choose from a predefined list of well-known companies: Apple (AAPL), Microsoft (MSFT), Google (GOOGL), Amazon (AMZN), and Tesla (TSLA). Users can select one or more of these stocks to analyze. The layout is set to "wide" for better readability and a dashboard-like experience.

Data Retrieval
When users select stocks, the app fetches hourly intraday price data using the Alpha Vantage API. Each stock's data is cached for one hour using Streamlit’s @st.cache_data decorator, optimizing performance and reducing unnecessary API calls. The data includes Open, High, Low, Close, and Volume prices, structured in a pandas DataFrame and sorted by time.

Error handling is also built-in: if a stock has no available data (e.g., due to API limits or incorrect key), the app displays a warning, and if no data is available for any selected stocks, it gracefully halts further execution with an error message.

Data Display
For each valid stock, the latest hourly data is displayed in a scrollable data table. This table helps users quickly view and compare the most recent market performance metrics.

Visual Analysis
The app includes two key visual components:

Line Chart – Closing Price Over Time:
Using Seaborn’s line plot, this visualization shows how each stock’s closing price has evolved over time. It helps users identify short-term trends, volatility, and momentum across multiple stocks on the same chart.

Box Plot – Price Distribution:
This plot shows the distribution of each stock’s closing prices over the recent period. It's particularly useful for identifying median price levels, outliers, and the overall volatility of each stock in a compact form.

Each plot is clearly titled and labeled, ensuring readability and interpretability. Axes are formatted for clarity, and legends help distinguish between multiple stock symbols.

API Integration & Customization
Users must provide their own Alpha Vantage API key for the app to function. The API key is easily set within the code, and the app can be extended to support more stocks or different intervals (e.g., daily, weekly) with minimal changes.



![Image](https://github.com/user-attachments/assets/740ff695-c1c1-4553-8f10-943f67af594e)
![Image](https://github.com/user-attachments/assets/f870185d-a87e-482c-baa6-25548a0927ac)
