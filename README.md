# Extracting Stock Data Using Python

This project demonstrates how to **extract, analyze, and visualize stock market data** using the `yfinance` Python library.  
It was developed as part of the IBM Developer Skills Network course on **Data Analysis with Python**.

---

## Project Overview

As a data scientist working for a hedge fund, your task is to detect suspicious or unusual stock activity by analyzing historical stock data.  
This notebook uses the **Yahoo Finance API** (via the `yfinance` library) to:

- Retrieve detailed stock information
- Extract and analyze **historical share prices**
- Extract and plot **dividend data**
- Visualize trends using `matplotlib`

The main example uses **Apple Inc. (AAPL)** as the stock of interest.

---

## Table of Contents

1. [Introduction](#-introduction)  
2. [Libraries Used](#-libraries-used)  
3. [Extracting Stock Data](#-extracting-stock-data)  
4. [Analyzing Historical Data](#-analyzing-historical-data)  
5. [Extracting Dividend Information](#-extracting-dividend-information)  
6. [Exercises](#-exercises)  
7. [Results](#-results)  
8. [References](#-references)

---

## Libraries Used

This notebook uses the following Python libraries:

```bash
pip install yfinance pandas matplotlib
