# Customer_Segmentation_Analysis

## Project Overview

This repository contains a **Customer Segmentation** analysis using **K-Means clustering** and the **Power BI** tool for visualization. The goal of this project is to divide a set of customers into distinct groups based on their **income** and **spending behavior**. The clustering model helps in understanding customer patterns and supports decision-making for targeted marketing and customer retention.

## Project Objectives

- Perform **K-Means clustering** on customer data to segment them into different clusters based on attributes like  income, and spending score.
- Visualize the segmentation results using **Power BI** for insightful analysis.
- Interpret the patterns and characteristics of each segment to create actionable insights for businesses.

## Data Overview

The dataset contains information about customers, including the following features:

- **CustomerID**: ID of the customer.
- **Age**: Age group of the custome
- **Gender**: Gender of the custome
- **Annual Income**: The annual income of the customer (in k$).
- **Spending Score**: A score representing how much a customer spends on average, based on their purchasing behavior.

## Methodology

### 1. **Data Preprocessing**:
   - Cleaned the data by handling missing values.

### 2. **EDA**:
   - Performed EDA(Exploratory Data Analysis) on data to get more information about data sets.
   
### 3. **K-Means Clustering**:
   - Applied the **K-Means clustering algorithm** to segment the customers into **5 distinct clusters**.
   - Evaluated the optimal number of clusters using the **Elbow Method**.
   - Assigned each customer to one of the 5 clusters based on the clustering results.

### 4. **Power BI Visualization**:
   - Visualized the segmentation results in **Power BI** with various charts and graphs.
   - Created interactive dashboards with slicers for filtering clusters, income groups, and age ranges.


## Power BI Dashboard

The Power BI dashboard visualizes customer segments and their attributes in an interactive format. Key features of the dashboard:
- **Scatter plots** to visualize the relationship between income and spending score.
- **Bar charts** showing the distribution of each cluster.
- **Slicers** to filter by age group, income range, or cluster number.
- **Matrix** to showc cluster profile.

![Customer Segmentation Power BI Report](https://github.com/yourusername/yourrepositoryname/blob/main/images/customer-segmentation-dashboard.png)


## Getting Started

To replicate the analysis or run this project locally, follow these steps:

### Prerequisites
- **Python 3.x** (for clustering analysis).
- **Jupyter Notebook** (for running the clustering analysis).
- **Power BI Desktop** (for visualizing the results).

### Setup and Installation

1. Clone this repository:
   git clone https://github.com/14guptapriya/Customer_Segmentation_Analysis.git
2. Install the necessary Python packages:
3. Run the K-Means clustering analysis in the Jupyter notebook:
   jupyter notebook analysis/kmeans-clustering-analysis.ipynb
4. Open the Customer_Segmentation.pbix file in Power BI Desktop to view the interactive dashboard.


