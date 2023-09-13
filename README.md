# Extracting-and-Visualizing-Stock-Data

In this project, I analyzed the stock prices and revenues of two popular companies: Tesla and GameStop. Tesla is an American electric vehicle and clean energy company, while GameStop is an American video game and consumer electronics retailer. Both companies have attracted a lot of attention from investors and the public in recent years.

The main steps I followed in this project were:

- Step 1: I used yfinance to extract stock data for Tesla. yfinance is a Python library that allows me to access historical and real-time financial data from Yahoo Finance. I specified the ticker symbol (TSLA), the start and end dates, and the frequency of the data I wanted to retrieve.
- Step 2: I used webscraping to extract Tesla revenue data from Microtrends. Microtrends is a website that provides financial data and statistics for various companies. I used the requests and BeautifulSoup libraries to get and parse the HTML content of the Microtrends page that contains Tesla's quarterly revenue data.
- Step 3: I repeated step 1 for GameStop, using the ticker symbol (GME).
- Step 4: I repeated step 2 for GameStop, using the Microtrends page that contains GameStop's quarterly revenue data.
- Step 5: I plotted Tesla stock graph using matplotlib and seaborn libraries. matplotlib and seaborn are Python libraries that allow me to create various types of graphs and charts. I plotted the Tesla stock price over time, along with some indicators such as moving average, volume, and daily returns.
- Step 6: I plotted GameStop stock graph using matplotlib and seaborn libraries. I plotted the GameStop stock price over time, along with some indicators such as moving average, volume, and daily returns.

This project was part of the IBM Data Science Specialization on Coursera, which is a course that teaches me how to apply data science skills and tools to real-world problems. This project helped me to practice and improve my skills in data extraction, manipulation, analysis, and visualization.
