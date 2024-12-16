# AI-Powered Company Evaluation and Stock Trend Analysis

Discover **InvestiGate**: An AI-powered tool that fetches real-time data from Google News, analyzes company growth trends, and offers insightful investment guidance. It combines data precision and analytics to empower informed investment decisions.

---

## Features:
- **Real-Time Data Retrieval**: Fetches the latest news and financial information.
- **Growth Trend Analysis**: Analyzes company performance over time.
- **AI Insights**: Uses OpenAI to generate data-driven conclusions.
- **Streamlined Interface**: Built with Streamlit for an interactive user experience.

---

## Steps to Run the Project:
1. **Download Required Files**: Ensure you have both `finance.py` and `stream.py`.
2. **Generate API Keys**:
   - Go to [SerpAPI](https://serpapi.com/) to create an account and generate an API key.
   - Visit [OpenAI](https://openai.com/) to create an account (if you don’t have one) and generate an API key.
3. **Add API Keys**: Paste the respective API keys into the `finance.py` file.
4. **Run the Streamlit App**:
   - Save the files and run `stream.py` using the terminal.
   - Example command:  
     ```bash
     streamlit run path_to_folder/stream.py
     ```
   - Replace `path_to_folder` with the actual path to your project folder.
5. **Access the App**: The app will open in your browser, ready to assist with your investments.

---

## Notes:
- Ensure that the folder containing the files has no spaces in its name to avoid terminal errors.
- For any queries, feel free to reach out!

---

## Libraries Used:
- **SerpAPI**: For efficient web scraping.
- **yahooquery**: Fetches comprehensive financial data from Yahoo Finance.
- **Streamlit**: Creates an interactive web app for user-friendly analysis.
- **OpenAI**: Generates conclusions based on collected data.

---

