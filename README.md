# Space Data Analysis Project

This repository contains code and data for scraping spaceflight data from [nextspaceflight.com](https://nextspaceflight.com/) using Python, and visualizing the results using Matplotlib, Seaborn, and Plotly in a Google Colab notebook.

## Usage

1. Open the provided Google Colab notebook ('Space_Missions_Analysis_(start).ipynb') to visualize the analysis, to view ploty plots open the notebook in Google Colab.

## Data Scraping

The `main.py` script uses Beautiful Soup to scrape data from [nextspaceflight.com](https://nextspaceflight.com/) and saves it as a CSV file.

### Reproducible Code Steps

To run the Web Scraping on your local machine, follow these steps:

1. **Clone the Repository**: Clone the Breakout Game repository to your local machine:

    ```bash
    git clone https://github.com/dieegogutierrez/SpaceRaceAnalysis.git
    ```

2. **Navigate to the Project Directory**: Change your current directory to the root of the cloned repository:

    ```bash
    cd SpaceRace
    ```

3. **Install Python Dependencies**: Make sure you have Python installed on your machine. Then, install the required dependencies using pip:

    ```bash
    python3.9 -m venv venv
    source venv/bin/activate
    pip install -r requirements.txt
    ```

4. **Run the Code**: Execute the main Python script to start scraping (it will take some time to finish):

    ```bash
    python main.py
    ```

## Data Visualization

The 'Space_Missions_Analysis_(start).ipynb' notebook in Google Colab contains code to visualize the scraped data:

- Line charts using Matplotlib and Seaborn to show trends over time.
- Interactive Plotly graphs for detailed data exploration. Note that Plotly graphs are visible only when accessing the Google Colab notebook.

## Results

The visualizations provide insights into spaceflight data trends and patterns, helping us understand various aspects of space exploration.
