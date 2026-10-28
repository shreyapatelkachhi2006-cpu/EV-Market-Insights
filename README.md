# EV Market Insights

## Project Overview

EV Market Insights is a data visualization project that explores electric vehicle market performance using Tableau Public. A Python Flask web application integrates the published dashboard and story into a single website.

## Project Objectives

* Analyze electric vehicle manufacturers and market share.
* Explore annual EV sales trends.
* Understand battery type distribution.
* Examine customer ratings across manufacturers and EV categories.
* Present interactive visualizations through a web application.

## Technologies Used

* Python
* Flask
* HTML
* CSS
* Tableau Public

## Project Structure

```text
EVMarket/
├── app.py
├── requirements.txt
├── README.md
└── templates/
    └── index.html
```

## Tableau Visualizations

### Dashboard

[View EV Market Dashboard](https://public.tableau.com/views/EVMarket_17930873345680/Dashboard1)

### Story

[View EV Market Story](https://public.tableau.com/views/EVMarket_17930873345680/Story1)

## How to Run the Project Locally

1. Install Python.

2. Open a terminal in the project folder.

3. Install the required dependency:

   `python -m pip install -r requirements.txt`

4. Run the Flask application:

   `python app.py`

5. Open `http://127.0.0.1:5000` in your browser.

## Web Integration

The Flask application displays the published Tableau Dashboard and Story using embedded views.

## Conclusion

This project combines data visualization and web development to make electric vehicle market insights accessible through an interactive website.
