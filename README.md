# BDA400 Assignment 6 - Technical Analysis using R

Student: Hurram Hameed

## Contents
- `app.R` - complete R Shiny portfolio visualization dashboard.
- `BDA400_Assignment6_Cover_Page.docx` - LMS cover page.
- `README.md` - setup and submission notes.

## How to run
1. Install R and RStudio.
2. Open `app.R` in RStudio.
3. Install the required packages if needed:
   `install.packages(c("shiny","ggplot2","quantmod","dplyr","tidyr","zoo","scales"))`
4. Run the application with `shiny::runApp()`.

## Dashboard features
- Yahoo Finance historical stock data.
- User-selectable ticker and date range.
- Daily, weekly, and monthly time frames.
- Line, candlestick, and area charts.
- Moving Average overlay with customizable periods.
- RSI and MACD indicator panels with on/off controls.
- Moving-average crossover BUY/SELL/HOLD rules.
- BUY and SELL chart annotations.
- Signal and latest-market-data tables.
- Error handling for invalid symbols, dates, and insufficient data.

## Repository link
Paste the final public GitHub repository URL on the cover page before LMS submission.

## Academic note
This project is for educational technical-analysis practice. BUY/SELL signals are rule-based demonstrations and are not investment advice.
