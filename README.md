# Stock Analysis

## Overview
Stock Analyser is a Shiny application that provides visualizations and analysis of stock performance using data from the S&P 500 companies. The app allows users to select a stock ticker and view its price trends, industry performance, and historical returns.
![full](https://i.ibb.co/dbDHGWW/image.png)

## Features
- **Price Chart**: Visualize the stock price over 10 year time.
![price](https://i.ibb.co/n0rs2zM/image.png)
- **Industry Chart**: Compare the stock's performance against its industry peers.
- **Performance Summary**: Analyze the stock's annualized returns over various time periods.
![industry_and_performance](https://i.ibb.co/QCvT5qy/image.png)

## Technologies Used
- R
- Shiny
- ggplot2
- dplyr
- tidyr
- rvest

## Setup Instructions
1.Clone this repository or download the source code.
```bash
https://github.com/AyushSharma567/Stock-Analysis.git
```
2. Set your working directory in R-studio to the location of the downloaded files.
3. Install required R packages if you haven't already:
   ```R
   install.packages(c("shiny", "shinydashboard", "ggplot2", "dplyr", "tidyr", "rvest", "readr"))
   ```
4.Run the application in r studios

## Data Sources
- S&P 500 Company data is scraped from the Wikipedia page.
- Historical stock prices are obtained from Yahoo Finance.

## File Descriptions
- ui.R: Contains the user interface layout of the Shiny application.
- server.R: Contains the server logic to render plots based on user input.
- Import_and_Clean.R: Script for importing, cleaning, and processing stock data.
- Plots.R: Script for generating various plots used in the application.

## Reference playlist 
  [here](https://www.youtube.com/watch?v=fXxS8Jf-j9w&list=PLx7Gb_TO6Z0TAJdYr4mUYeE9xLzF3CAr4)
