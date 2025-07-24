# 📈 AI Investment Strategist

## Introduction

**AI Investment Strategist** is a Streamlit-based web application that leverages advanced AI agents and real-time financial data to generate personalized investment reports. It combines the power of Google Gemini models, Yahoo Finance data, and interactive visualizations to help investors make informed decisions. This tool is designed for retail investors, financial analysts, and anyone seeking data-driven investment insights.

---

## Methodology

The app follows a modular, agent-based approach:

1. **Stock Data Retrieval:**  
   Utilizes the `yfinance` library to fetch historical stock prices, compute performance metrics, and gather company information and news.

2. **AI Agents for Analysis:**  
   - **Market Analyst:** Analyzes and compares the 6-month performance of selected stocks.
   - **Company Researcher:** Summarizes company profiles, financials, and the latest news.
   - **Stock Strategist:** Synthesizes performance and company fundamentals to recommend top stocks.
   - **Team Lead:** Aggregates all insights into a structured, investor-friendly report.

3. **Interactive Visualization:**  
   Uses Plotly to display interactive stock performance charts, making trend analysis intuitive.

4. **User Input:**  
   Investors can input one or more stock symbols and (optionally) their own API key for enhanced security and customization.

---

## How It Works

1. **Configuration:**  
   - Enter the stock symbols you wish to analyze in the sidebar (e.g., `AAPL, MSFT, TSLA`).
   - (Optionally) Enter your Google API key for the Gemini model.

2. **Report Generation:**  
   - Click the "Generate Investment Report" button.
   - The app retrieves the relevant stock data and sends it to AI agents for analysis.

3. **Report Output:**  
   - The final output includes:
     - **Market Analysis:** Comparative performance of selected stocks.
     - **Company Analyses:** Profiles, sector summaries, and latest news for each company.
     - **Investment Recommendations:** Ranked list of stocks to consider, based on combined analysis.
     - **Interactive Chart:** 6-month price trends for selected stocks.

---

## Conclusion

AI Investment Strategist provides a seamless blend of real-time data, AI-driven analysis, and investor-friendly reporting. By automating the process of financial research and recommendation, it empowers users to make smarter, faster, and evidence-based investment decisions. Whether you're a beginner or a seasoned investor, this tool offers valuable insights to guide your stock selection strategy.

---

> **Note:**  
> For production use, ensure your API keys are securely managed and not hard-coded in the source files.
