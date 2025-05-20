# Air Quality Analysis and Forecasting System

A Streamlit web application to analyze historical air quality data, visualize trends, and provide forecasts using Prophet and OpenAI GPT-4.

## Features

*   Loads and preprocesses air quality data (specifically Indirapuram, Ghaziabad data).
*   Displays current pollutant levels and 7-day averages in the sidebar.
*   Allows users to chat with an AI assistant (powered by OpenAI) to ask questions about the data.
*   Provides insights on pollutant trends, correlations, health implications, and forecasts.
*   Generates visualizations like pollutant trends, correlation heatmaps, and AQI forecasts.

## Setup

1.  **Clone the repository:**
    ```bash
    git clone <url_of_your_github_repo>
    cd air-quality-app # Or whatever your folder name is
    ```
2.  **(Recommended) Create a virtual environment:**
    ```bash
    python -m venv venv
    # On Windows:
    # .\venv\Scripts\activate
    # On macOS/Linux:
    # source venv/bin/activate
    ```
3.  **Install dependencies:**
    ```bash
    pip install -r requirements.txt
    ```
4.  **Set up environment variables:**
    Create a file named `.env` in the root directory of the project. Add your OpenAI API key:
    ```
    OPENAI_API_KEY=your_actual_openai_api_key_here
    ```
    **NOTE:** Do NOT share your API key or commit the `.env` file to Git. The `.gitignore` file should prevent this.

## Running the App

Make sure your virtual environment is activated (if using one).
Run the Streamlit application from your terminal:
```bash
streamlit run app.py # Or the name of your Python script