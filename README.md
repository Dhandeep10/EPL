# English Premier League Prediction (EPL Prediction)

This project aims to predict English Premier League (EPL) football match outcomes using data scraped from fbref.com.

## Overview

The English Premier League Prediction (EPL Prediction) project utilizes web scraping techniques to gather historical football match data from fbref.com. This data is then used to train machine learning models that predict match outcomes based on various features such as team performance metrics, player statistics, and match conditions.

## Features

- **Web Scraping:** Data is collected from fbref.com using Python's BeautifulSoup library.
- **Machine Learning Models:** Predictive models are trained using historical match data.
- **Performance Metrics:** Evaluation of model accuracy and performance.
- **Visualization:** Results and insights are visualized to enhance understanding.

## Installation

To run the project locally, follow these steps:

1. Clone the repository:
   ```
   git clone https://github.com/Dhandeep10/EPL.git
   ```

2. Install dependencies:
   ```
   pip install -r requirements.txt
   ```

3. Run the prediction script:
   ```
   python predict.py
   ```

## Usage

- **Data Collection:** Modify `eplData.ipynb` to scrape additional data or update existing data.
- **Model Training:** Explore different machine learning algorithms in `eplPredict.ipynb`.
- **Prediction:** Use `eplPredict.ipynb` to predict match outcomes based on current season data.

## Contributing

Contributions are welcome! If you have suggestions or improvements, please fork the repository and submit a pull request.

