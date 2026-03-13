## Stock Price MCP Server

## Overview

A custom Model Context Protocol (MCP) server that integrates Claude Desktop with live Yahoo Finance stock market data using the yfinance Python library.

This project demonstrates how to build and integrate a local MCP server with Claude Desktop. The server exposes tools that allow Claude to:

- Retrieve live stock prices  
- Compare two stock prices  
- Fetch historical stock data in CSV format  

The server runs locally and communicates with Claude Desktop through the MCP standard over standard input and output.

## Features
- `get_stock_price(symbol: str)`  
  Returns the latest closing price of a stock.
  <img width="2557" height="907" alt="image" src="https://github.com/user-attachments/assets/828aca18-0ed5-468a-af33-38bdb81e6076" />


- `get_stock_history(symbol: str, period: str)`  
  Returns historical stock data as a CSV formatted string.
  <img width="2557" height="980" alt="image" src="https://github.com/user-attachments/assets/78eb941a-13bc-4239-93cf-87ed6a6a39be" />


- `compare_stocks(symbol1: str, symbol2: str)`  
  Compares two stock prices and returns a formatted result.
  <img width="2558" height="1002" alt="image" src="https://github.com/user-attachments/assets/925523a0-4884-48df-87d3-a91b1bdde7fe" />


## Technology Stack



- Python 3.14  
- Model Context Protocol (MCP)  
- yfinance  
- uv (Python package manager)  
- Claude Desktop  

<img width="1517" height="1189" alt="image" src="https://github.com/user-attachments/assets/16bac781-3f17-4f56-a61d-304f425c64fc" />
<img width="1610" height="856" alt="image" src="https://github.com/user-attachments/assets/35f9cf66-47ea-4d27-8a11-253b931b9310" />



