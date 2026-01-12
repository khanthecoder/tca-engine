# tca-engine
### Transaction Cost Analysis Engine

This project implements a lightweight transaction cost analysis TCA engine to evaluate how execution quality impacts trading performance.

It focuses on measuring slippage, spread costs, and benchmark comparisons such as VWAP using historical trade and quote data.

### Why this exists

In real trading systems, strategy returns are often dominated by execution costs rather than signal quality.
This project is built to quantify where and how money is lost during trade execution.

### Core features

• Trade and quote data ingestion
• Mid price computation from bid ask data
• Slippage and spread cost measurement
• VWAP based execution benchmarking
• Aggregation of execution metrics by symbol and time

### Tech stack

• Python
• Pandas
• NumPy

### Design philosophy

This is an infrastructure focused project.
No prediction models, no machine learning, and no trading strategies are included.

The goal is to build clean, testable analytics that mirror real world quant and hedge fund engineering workflows.

### Status

Work in progress. Incrementally adding execution metrics and robustness.
