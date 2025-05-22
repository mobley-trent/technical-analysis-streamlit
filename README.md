# TECHNICAL INDICATORS WEB APP

This repo hosts a web app for technical indicators used in quantitative finance, built using Streamlit.
The technical indicators include:
- Simple Moving Average (SMA)
- Bollinger Bands
- Relative Strength Index (RSI)

You can access the web app using this [link](https://technical-analysis-app-n8mwwimq2yzhrv8g2guaib.streamlit.app/)

## Local Setup
To run the app locally, follow these steps:
1. Clone the repository:
   ```bash
   git clone https://github.com/mobley-trent/technical-analysis-streamlit.git
   cd technical-analysis-streamlit
    ```
2. Create a virtual environment (optional but recommended):
    ```bash
    python -m venv .venv
    source .venv/bin/activate  # On Windows use `venv\Scripts\activate`
    ```
3. Install the required packages:
    ```bash
    pip install -r requirements.txt
    ```
4. Run the app:
    ```bash
    streamlit run technical_analysis_app.py
    ``` 
5. Open your web browser and go to `http://localhost:8501` to view the app.

- Note: Make sure you have Python 3.7 to run this app optimally.