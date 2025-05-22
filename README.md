# YouTube Channels Analysis with Clustering and Regression

## Project Overview

This project analyzes data on the most subscribed YouTube channels to uncover patterns and build predictive models. It uses Python and popular libraries like Pandas, Scikit-learn, and Plotly for data processing, visualization, clustering, and regression.

---

## Dataset

The dataset contains information about YouTube channels, including:

- Channel name
- Number of subscribers
- Video views
- Video count
- Category of the channel
- Year the channel started

---

## What This Project Does

1. **Data Cleaning and Feature Engineering**  
   The raw data is cleaned (removing commas and converting strings to numbers). New features are created to better describe channels, such as:
   - Channel age (how many years since it started)
   - Average views per video
   - Ratio of subscribers to views

2. **Clustering (Unsupervised Learning)**  
   Channels are grouped into clusters based on similar characteristics (like subscriber count, views, and channel age) using K-Means clustering. This helps identify groups like highly popular channels versus smaller or newer channels.

3. **Regression (Supervised Learning)**  
   A regression model is trained to predict the number of subscribers a channel has based on features like video views, video count, and channel age.

4. **Visualizations**  
   The project includes various plots to visualize the data distribution, clusters, and model performance.

---

## Technologies Used

- Python  
- Pandas (data manipulation)  
- Scikit-learn (machine learning algorithms)  
- Plotly and Matplotlib (interactive and static visualizations)  
- Jupyter Notebook (for development and presentation)

---

## How to Run

1. Install the required Python libraries:
   ```bash
   pip install pandas scikit-learn matplotlib plotly
