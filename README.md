# Google Trends Data Analysis using Python

##Project Overview

This project analyzes global Google search trends using the PyTrends API. The objective is to explore public interest in emerging technologies such as Artificial Intelligence, Cloud Computing, Data Science, and Machine Learning by analyzing search behavior across different countries and over time.

Using Python and data visualization libraries, the project extracts trend data from Google Trends, performs exploratory data analysis (EDA), and generates visual insights through charts and interactive maps.

---

## Project Objectives

* Collect Google Trends data using the PyTrends API
* Analyze country-wise search interest
* Visualize global search trends
* Study search interest over time
* Compare multiple technology-related keywords
* Generate insights from trend data

---

## Technologies Used

### Programming Language

* Python

### Libraries

* Pandas
* PyTrends
* Matplotlib
* Seaborn
* Plotly

### Data Science Concepts

* Data Collection
* Exploratory Data Analysis (EDA)
* Data Visualization
* Trend Analysis
* Time Series Analysis
* Comparative Analysis

---

## Project Workflow

### Step 1: Data Collection

Google Trends data was collected using the PyTrends API.

```python
from pytrends.request import TrendReq

pytrends = TrendReq(hl='en-US', tz=360)
```

The following trend datasets were retrieved:

* Interest by Region
* Interest Over Time
* Keyword Comparison Data

---

### Step 2: Regional Interest Analysis

The search interest of "Artificial Intelligence" was analyzed across different countries.

Tasks performed:

* Retrieved regional trend data
* Sorted countries by search interest
* Selected the top 15 countries
* Visualized results using Seaborn bar charts

Visualization:

* Top Countries Searching for Artificial Intelligence

---

### Step 3: Global Trend Mapping

An interactive world map was created using Plotly Choropleth Maps.

Features:

* Country-wise trend visualization
* Interactive geographic analysis
* Global search distribution

Visualization:

* Search Interest for Artificial Intelligence by Country

---

### Step 4: Time Series Analysis

Search interest was analyzed over the last 12 months.

Tasks performed:

* Retrieved trend data over time
* Created time-series line charts
* Identified fluctuations in search popularity

Visualization:

* Search Interest Over Time

---

### Step 5: Keyword Comparison

Multiple technology-related keywords were compared.

Keywords:

* Cloud Computing
* Data Science
* Machine Learning

Tasks performed:

* Retrieved trend data for multiple keywords
* Compared popularity over time
* Visualized trends using multi-line charts

Visualization:

* Keyword Comparison Over Time

---

## Key Features

* Google Trends API Integration
* Country-wise Trend Analysis
* Global Search Visualization
* Interactive World Map
* Time Series Analysis
* Multi-Keyword Comparison
* Data-Driven Insights

---

## Results

### Top Countries Searching for Artificial Intelligence

![Top Countries](outputs/top_countries.png)

### Global Search Interest Map

![World Map](outputs/world_map.png)

### Search Interest Over Time

![Trend Over Time](outputs/trend_over_time.png)

### Keyword Comparison

![Keyword Comparison](outputs/keyword_comparison.png)

---

## Skills Demonstrated

### Technical Skills

* Python Programming
* Pandas
* PyTrends API
* Matplotlib
* Seaborn
* Plotly
* Data Visualization
* Exploratory Data Analysis (EDA)
* Time Series Analysis

### Analytical Skills

* Trend Analysis
* Comparative Analysis
* Data Interpretation
* Insight Generation
* Data-Driven Decision Making

---

## Project Structure

google-trends-analysis/

├── Google_Trends_Analysis.ipynb

├── main.py

├── requirements.txt

├── README.md

└── outputs/

    ├── top_countries.png

    ├── world_map.png

    ├── trend_over_time.png

    └── keyword_comparison.png

---

## Installation

Install required libraries:

```bash
pip install pytrends pandas matplotlib seaborn plotly
```

---

## How to Run

```bash
python main.py
```

---

## Key Insights

* Artificial Intelligence shows significant global search interest.
* Search behavior varies across countries and regions.
* Technology-related keywords exhibit different popularity patterns.
* Trend analysis helps identify emerging technologies and user interests.


## Future Improvements

* Build an interactive dashboard using Streamlit
* Export reports automatically
* Analyze related search queries
* Add trend forecasting using machine learning
* Create a real-time trend monitoring dashboard

---

## Author

Krishna Prasad Sahu

Data Science Student

GitHub: [https://github.com/krishnaprasad9083-code]

LinkedIn:  [https://www.linkedin.com/in/krishna-prasad-sahu-a758a92b4?utm_source=share_via&utm_content=profile&utm_medium=member_android]


## Conclusion

This project demonstrates practical applications of Python, Google Trends data, exploratory data analysis, and data visualization techniques to understand public search behavior and technology adoption trends worldwide.
