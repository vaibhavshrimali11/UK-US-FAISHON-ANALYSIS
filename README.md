# Fashion Data Analysis and Prediction Project

## Project Overview

This project involves analyzing a dataset related to fashion products, including their sales, ratings, and the impact of fashion influencers and magazines. The analysis aims to uncover insights into product performance and the effectiveness of marketing strategies, such as influencer endorsements and magazine features.

## Dataset

The dataset used in this project is `mock_fashion_data_uk_us.csv` and includes the following columns:

- **Price**: Price of the product.
- **Brand**: Brand of the product.
- **Category**: Product category.
- **Rating**: Customer rating of the product.
- **Review Count**: Number of reviews for the product.
- **Age**: Age of the customer.
- **Description**: Description of the product.
- **Style Attributes**: Style attributes of the product.
- **Color**: Color of the product.
- **Fashion Magazines**: Whether the product was featured in fashion magazines.
- **Fashion Influencers**: Whether the product was featured by fashion influencers.
- **Season**: Season in which the product was available.
- **Time Period Highest Purchase**: Time period with the highest purchase for the product.
- **Customer Reviews**: Customer reviews of the product.
- **Social Media Comments**: Comments about the product on social media.
- **feedback**: Additional feedback on the product.

## Exploratory Data Analysis (EDA)

The following visualizations and analyses are performed:

1. **Categorical Data Analysis**:
   - Count plots of categorical columns.
   - Price distribution across categories.
   - Top brands and colors by popularity.

2. **Price and Rating Analysis**:
   - Scatter plot of price vs. rating.
   - Histogram of product ratings.
   - Scatter plot of price vs. review count.

3. **Seasonal and Temporal Analysis**:
   - Count plots of product availability across different seasons.
   - Time period of highest purchase vs. product categories.

4. **Feature Impact Analysis**:
   - Boxplot comparing ratings for featured vs. non-featured products.
   - Sales comparison of featured vs. non-featured products.

5. **Influencer Impact Analysis**:
   - Distribution of ratings by each influencer.
   - Total sales and average ratings by each influencer.
   - Scatter plot of average rating vs. total sales for each influencer.
   - Detailed profiles of top influencers based on total sales.

## Predictive Models

1. **Pricing Optimization**:
   - Linear Regression model to predict the optimal price for maximizing sales.
   - Feature importance analysis to understand the impact of different features on pricing.

2. **Sales Forecasting**:
   - Time Series analysis using ARIMA to forecast future sales.
   - Feature Engineering for time series: lag features and rolling means.

3. **Rating Prediction**:
   - Linear Regression model to predict product ratings based on product attributes and influencer features.

## Code Structure

- **Data Preparation**: Load and preprocess data, handle categorical variables.
- **EDA**: Generate plots and insights from exploratory data analysis.
- **Predictive Modeling**: Build and evaluate predictive models for pricing optimization, sales forecasting, and rating prediction.
- **Influencer Analysis**: Detailed analysis and visualization of the impact of fashion influencers on product performance.

## Installation

To run the code, you need the following Python packages:

```bash
pip install numpy pandas matplotlib seaborn scikit-learn statsmodels plotly
