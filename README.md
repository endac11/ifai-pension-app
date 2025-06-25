# ifai-pension-app
# IFAI - Independent Financial Advisor AI

![IFAI Screenshot](screenshot.png)
*(To add a screenshot: Run the app, take a picture of it, save it as `screenshot.png` in this folder, and commit it to your repository.)*

IFAI is an easy-to-use financial advice application aimed at UK pension planning and advice. It provides users aged 45-65 with a clear interface to input their financial status and run various retirement scenarios. The app projects pension pot growth, simulates retirement drawdown, and integrates UK State Pension rules to provide a holistic view of retirement readiness.

---

### 🌟 Core Features

*   **Clean & Simple Interface:** Built with Streamlit for maximum clarity and ease of use.
*   **Personalised Inputs:** Users can enter their date of birth, current pension pot, monthly contributions, and retirement goals.
*   **UK State Pension Integration:** Automatically calculates the user's State Pension Age and incorporates the State Pension into projections.
*   **Dynamic Scenario Modelling:** Projects pension pot growth up to a chosen retirement age and simulates how long the funds will last.
*   **Rich Visualisations:** Outputs include a clear text summary and interactive charts for pot growth, income sources, and retirement drawdown.

### ⚠️ Disclaimer

IFAI is an AI-powered informational tool, not a registered financial advisor. The projections are based on the data you provide and standard financial assumptions. **Always consult with a qualified, independent financial advisor before making any financial decisions.** Investment growth is not guaranteed.

---

### 🚀 Getting Started

Follow these instructions to run the application on your local machine.

#### Prerequisites

*   Python 3.8 or newer
*   pip (Python package installer)

#### Installation & Setup

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/your-username/ifai-pension-app.git
    cd ifai-pension-app
    ```

2.  **Create and activate a virtual environment (recommended):**
    *   **On Windows:**
        ```bash
        python -m venv venv
        .\venv\Scripts\activate
        ```
    *   **On macOS/Linux:**
        ```bash
        python3 -m venv venv
        source venv/bin/activate
        ```

3.  **Install the required libraries:**
    ```bash
    pip install -r requirements.txt
    ```

4.  **Run the application:**
    ```bash
    streamlit run ifai_app.py
    ```

The application will open automatically in your default web browser.

---

### 💻 Technology Stack

*   **[Streamlit](https://streamlit.io/):** The core framework for the web application interface.
*   **[Pandas](https://pandas.pydata.org/):** Used for data manipulation and creating dataframes for projections.
*   **[Plotly](https://plotly.com/python/):** Used for generating interactive charts and graphs.
Independent financial advice app
