# Course Enrollment Visualization and Dropout Rate Prediction

This project leverages machine learning and data visualization techniques to predict dropout rates in courses and provide insights into course performance and difficulty. By analyzing course enrollment data, this project predicts dropout rates using a Quantile Gradient Boosting Regressor and visualizes key insights with an interactive Power BI dashboard.

## Features
- **Dropout Rate Prediction:** 
  - Developed a Quantile Gradient Boosting Regressor using `sklearn` to predict dropout rates based on class enrollment.
  - Improved the model’s performance from an R² score of 0.04 using linear regression to 0.56 using the boosting regressor.
  
- **Data Scraping and Cleaning:** 
  - Scraped data of 950+ courses using `Selenium` and `BeautifulSoup`.
  - Cleaned and organized the scraped data with `Pandas` in Jupyter Notebooks for further analysis.
  
- **Interactive Power BI Dashboard:**
  - Created a dynamic Power BI dashboard to visualize course performance, model predictions, and course difficulty.
  - Facilitates data-driven insights and enables deeper understanding of course enrollment trends.

## Power BI Dashboard

Here is a preview of the Power BI dashboard showcasing the course performance and dropout predictions:

![Power BI Dashboard](https://i.imgur.com/wM43WNX.jpg)

The dashboard provides interactive visualizations that help in analyzing course enrollment trends, model predictions, and course difficulty. It allows you to explore different aspects of course data and understand how factors like enrollment numbers affect dropout rates.

### Key Features of the Dashboard:
- Visual representation of course performance metrics.
- Model predictions for dropout rates.
- Interactive filters to explore different course categories and enrollment trends.


## Technologies Used
- **Python:**
  - Libraries: `sklearn`, `pandas`
  
- **Machine Learning:**
  - Quantile Gradient Boosting Regressor (from `sklearn`)
  
- **Data Visualization:**
  - Power BI (Interactive Dashboard)

## Installation

To get started, clone the repository to your local machine:

```bash
git clone https://github.com/AlphaCloudX/UOG-Course-Difficulty.git
```

## Dependencies

To install the required dependencies for this project, you can use the following `requirements.txt` file.

### Install Dependencies:

Run the following command to install all necessary Python libraries:

```bash
pip install -r requirements.txt
