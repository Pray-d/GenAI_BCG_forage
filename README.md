# Financial Analysis Chatbot

This is an interactive financial analysis chatbot built in Python using `pandas` and `ipywidgets`. The chatbot allows users to query company financial data, such as **Total Revenue**, **Net Income**, **Total Assets**, and **Average Assets**. 

The chatbot supports a range of predefined queries and is capable of handling year inputs in various formats (e.g., `21`, `2021`, `22`, `2022`, `23`, `2023`).

## Features

- **Query for Financial Data**: Retrieve data for various companies (Apple, Microsoft, Tesla) across different years.
- **Flexible Query Input**: The chatbot is case-insensitive and can handle common typos in user queries.
- **Company and Year Extraction**: Extracts company names and years from user input using regular expressions.
- **Predefined Queries**: Supports predefined queries like:
    - "What is the total revenue of Apple in 21?"
    - "How much was the net income of Microsoft in 22?"
    - "What is the average assets of Tesla?"

## Setup Instructions

1. Clone this repository:
   ```bash
   git clone https://github.com/Pray-d/GenAI_BCG_forage.git
   ```

2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Run the chatbot:
   ```bash
   python chatbot.py
   ```

## Example Queries

- "What is the total revenue of Apple in 21?"
- "How much was the net income of Microsoft in 22?"
- "What is the average assets of Tesla?"

## Limitations

- The chatbot can only answer questions based on predefined data in the `pandas` DataFrame.
- Currently, it only supports three companies: Apple, Microsoft, and Tesla.
