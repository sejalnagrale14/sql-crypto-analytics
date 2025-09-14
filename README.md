  Cryptocurrency Trading Analysis

This project contains a SQL database schema and data related to cryptocurrency trading. It includes tables for members, cryptocurrency prices (specifically for Ethereum, or ETH), and transaction logs. The SQL script defines the database structure, populates it with sample data, and includes queries for performing analysis on this data.

Project Structure
The project consists of a single SQL file: Cryptocurrency Project.sql.

Cryptocurrency Project.sql: This file creates the trading schema and three tables:

members: Stores information about trading members, including a member_id, first_name, and region.

prices: Contains historical price data for a cryptocurrency ticker, with columns for market_date, price, open, high, low, volume, and changes. The provided data is for Ethereum (ETH).

transactions: Logs all buy and sell transactions, including a txn_id, member_id, ticker, txn_date, txn_type, quantity, percentage_fee, and txn_time.

The file also includes INSERT statements to populate the tables with sample data and SELECT statements to preview the data. Additionally, there are a few commented-out queries that perform more complex analysis, such as calculating Dollar Cost Average (DCA) and ranking regions based on DCA.
