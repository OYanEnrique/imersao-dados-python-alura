# imersao-dados-python-alura
Data analysis project created during the event

# Real Estate Market Analysis Dashboard

This project is an interactive web dashboard for analyzing real estate data, developed as the final project for the **Alura Data Immersion**. The application was built using Python with Streamlit, Pandas for data manipulation, and Plotly for creating interactive visualizations.

The dashboard allows users to explore insights from a dataset of property listings, filtering data and visualizing key market metrics.

[![Streamlit App](https://static.streamlit.io/badges/streamlit_badge_black_white.svg)](https://imersao-dados-python-alura-2025-yanenrique.streamlit.app/)

## Live Dashboard

You can access and interact with the live dashboard here:
**https://imersao-dados-python-alura-2025-yanenrique.streamlit.app/**

## Features

-   **Interactive Filtering:** Users can filter the entire dashboard by country using a sidebar selector.
-   **Key Metrics:** Displays high-level statistics, such as the total number of properties analyzed.
-   **Geospatial Distribution:** A bar chart showing the number of property listings per country.
-   **Top Properties Analysis:** A table showcasing the top 10 most expensive properties in the selected country.
-   **Feature Analysis:** An interactive pie chart visualizing the proportion of properties with and without a swimming pool.
-   **Price Distribution:** A histogram showing the distribution of property prices, helping to understand the market's price range.

## Dataset

The analysis is based on the `dados-imersao-final.csv` dataset. This dataset contains cleaned information about property listings, including fields such as:
- `country`
- `city`
- `property_type`
- `price`
- `currency`
- `swimming_pool`
- `size_in_m2`

The data cleaning and preparation steps were performed during the Alura Data Immersion course.

## Technologies Used

-   **Language:** Python
-   **Data Manipulation:** Pandas
-   **Web Framework / Dashboarding:** Streamlit
-   **Data Visualization:** Plotly

## How to Run This Project Locally

To run this application on your own machine, follow the steps below.

### Prerequisites

-   Python 3.8+
-   `pip` package manager

### Setup

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/your-username/your-repository-name.git](https://github.com/your-username/your-repository-name.git)
    cd your-repository-name
    ```

2.  **(Optional but Recommended) Create a virtual environment:**
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
    ```

3.  **Install the required dependencies:**
    The project's dependencies are listed in the `requirements.txt` file. Install them with pip:
    ```bash
    pip install -r requirements.txt
    ```

4.  **Run the Streamlit application:**
    Once the dependencies are installed, you can launch the app using the following command in your terminal:
    ```bash
    streamlit run app.py
    ```
    Your web browser should open a new tab with the local application running.

## Project Structure

```
.
├── app.py                  # The main Streamlit application script
├── dados-imersao-final.csv # The dataset used for the analysis
├── requirements.txt        # A list of Python dependencies for the project
└── README.md               # This README file
```

## Acknowledgements

This project was developed as part of the **[Imersão Dados](https://www.alura.com.br/imersao-dados)** (Data Immersion) program offered by **Alura**. Special thanks to the instructors and the community for their support and guidance.
