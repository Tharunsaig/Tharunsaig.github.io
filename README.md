# My Data Science Portfolio

Welcome to my data science portfolio! Here you can find a collection of my projects, certificates, and ways to connect with me.

## About

I am passionate about leveraging data to gain insights and solve problems. Check out my [resume](link-to-resume) to learn more about my experience and skills.

## Projects

## Machine Learning Projects

### 1. Exploring Online Retail Purchase Patterns

**Objective:** 
The aim of this analysis is to delve into the diverse purchasing behaviors of customers within an online retail store. Through evidence-based insights, we seek to unravel significant patterns in customer transactions.

**Dataset Overview:**
The dataset comprises 541,909 entries across 8 columns, encompassing purchase data spanning from 2010 to 2011.

**Key Findings from Exploratory Data Analysis:**
- Notably, the United Kingdom exhibits the highest frequency of order cancellations within the dataset.
- "WHITE HANGING HEART T-LIGHT HOLDER" emerges as the most commonly purchased item.
- Interestingly, Thursday, Wednesday, and Tuesday collectively account for approximately 52% of shopping days.
- November stands out as the month with the highest proportion of purchases, constituting 16% of the total orders.

**Insightful Data Visualizations:**
<table>
  <tr>
    <td>
      <img src="/images/monthly%20purchases.jpg" alt="Monthly Purchases" style="width: 300px; float: left; margin-right: 20px;">
    </td>
    <td>
      <img src="/images/percentage%20of%20shopping%20by%20day.jpg" alt="Shopping Day Distribution" style="width: 300px; float: right; margin-left: 20px;">
    </td>
  </tr>
  <tr>
    <td>
      <em>Figure 1: Distribution of Monthly Purchases</em>
    </td>
    <td>
      <em>Figure 2: Percentage of Shopping by Day</em>
    </td>
  </tr>
</table>

<table>
  <tr>
    <td>
      <img src="/images/top%2010%20customers%20.jpg" alt="Top 10 Customers" style="width: 300px; float: left; margin-right: 20px;">
    </td>
    <td>
      <img src="/images/clustering%20images.jpg" alt="Customer Segmentation" style="width: 300px; float: left; margin-right: 20px;">
    </td>
  </tr>
  <tr>
    <td>
      <em>Figure 3: Top 10 Customers by Amount Spent</em>
    </td>
    <td>
      <em>Figure 4: Segmented Customers by RFM Values</em>
    </td>
  </tr>
</table>

**Utilized Algorithms:** 
Our analysis employed Kmeans clustering and AgglomerativeClustering techniques to discern customer segments effectively.

**Project Notebook:** 
For a comprehensive review of the analysis process, refer to the [Online Retail Sales project notebook](https://github.com/Tharunsaig/Online-retail-clustering-project/blob/main/online_retail%20project.ipynb). Notably, the segmentation of customers based on Recency, Frequency, and Monetary values was conducted, with Kmeans clustering yielding the most insightful results.

### 2. Walmart capstone

**Objective:** 
A retail store that has multiple outlets across the country are facing issues in managing the inventory - to match the demand with respect to supply. You are a data scientist, who must come up with useful
insights using the data and make prediction models to forecast the sales for X number of months/years

**Dataset Overview:**
The dataset comprises 6435 entries across 8 columns sales data from 2010 t0 2013.

**Key Insights from Exploratory Data Analysis:**
- January registers less than 10% of the average total sales, while December sees a 15% surge.
- The 51st week stands out with the highest sales.
- The top-performing store, Store 20, boasts an average sales figure of $2,107,676.87, while the worst-performing store, Store 33, lags significantly with an average sales figure of $259,861.69.
- A discernible negative correlation exists between temperature and weekly sales, indicating that higher temperatures correlate with lower sales volumes.
- Analysis of scatter plots and regression lines confirms a slight downward slope, indicative of a mildly negative relationship.
- The regression line's negative slope suggests an inverse correlation between the unemployment rate and weekly sales.

**Insightful Data Visualizations:**
<table>
  <tr>
    <td>
      <img src="/images/Monthwise.jpg" alt="% of Montly Average sales" style="width: 300px; margin-right: 20px;">
    </td>
    <td>
      <img src="/images/averagesalesperstore.jpg" alt="Average sales per store" style="width: 300px; margin-left: 20px;">
    </td>
  </tr>
  <tr>
    <td>
      <em>Figure 1: Monthly Average sales </em>
    </td>
    <td>
      <em>Figure 2: Average sales per store</em>
    </td>
  </tr>
</table>
<table>
  <tr>
    <td>
      <img src="/images/salespattern.jpg" alt="% of Montly Average sales" style="width: 620px;margin-left: 20px;">
    </td>
  </tr>
  <tr>
    <td>
      <em>Figure 3: Seasonal sales pattern</em>
    </td>
  </tr>
</table>

**Utilized Algorithms:** 
ARIMA, SARIMA, and Random Forest were used for the sales prediction

**Project Notebook:** 
The analysis involved data sampling, stationarity checks using the Dickey-Fuller test, and forecasting using time series algorithms such as ARIMA, AutoARIMA, and SARIMA, as well as tree algorithms. Random Forest yielded favorable results.For more detailed overview, refer to the [Walmart sales forecasting](https://github.com/Tharunsaig/Walmart-sales-analysis-project/blob/main/Walmart%20project.ipynb).


### 3. Census capstone

**Objective:** 
This project involves comprehensive preprocessing and exploration of the Census Income dataset, aimed at understanding its features through thorough analysis and visualization. Following this exploration, various classification algorithms will be deployed to predict whether an individual earns over $50,000 annually or less. 

**Dataset Overview:**
The dataset, drawn from the UCI Machine Learning Repository, encompasses income details of over 30,000 individuals from the 1994 US census.

**Key Insights from Exploratory Analysis:**
- Within the census data, a significant majority, accounting for 74%, are classified under the "Private" working class.
- Notably, the "Self-employed" category exhibits the highest mean capital gain, whereas those classified as "withoutpay" have the lowest.
- Approximately 52% of individuals from the United States work in the private sector and earn an annual income of less than $50,000.
- Surprisingly, only about 5% of high school graduates manage to surpass the $50,000 annual income threshold.

**Insightful Data Visualizations:**
<table>
  <tr>
    <td>
      <img src="/images/distribution%20of%20occupation%20by%20annual_income.jpg" alt="Occupation Distribution by Annual Income" style="width: 300px;">
    </td>
    <td>
      <img src="/images/Mean%20capital%20gain%20by%20workclass.jpg" alt="Distribution of Workclass" style="width: 300px;">
    </td>
    <td>
      <img src="/images/Mean%20capital%20gain%20by%20workclass%20and%20sex.jpg" alt="Mean Capital Gain by Workclass and Gender" style="width: 300px;">
    </td>
  </tr>
  <tr>
    <td align="center"><strong>Occupation Distribution by Annual Income</strong></td>
    <td align="center"><strong>Distribution of Workclass</strong></td>
    <td align="center"><strong>Mean Capital Gain by Workclass and Gender</strong></td>
  </tr>
</table>

**Utilized Algorithms:** 
The project incorporates a variety of algorithms, including Random Forest, Decision Tree, Linear Regression, and Logistic Regression.

**Project Notebook:** 
For a detailed exploration of the data preprocessing, manipulation, visualization, and classification modeling processes, refer to the [Census project notebook](https://github.com/Tharunsaig/Census-Income-binary-classification/blob/main/Census%20project%20(1).ipynb).




## Certificates

Explore my [certificates](link-to-certificates) to see the courses and certifications I have completed.

## Socials and Email

Connect with me on [LinkedIn](link-to-linkedin) and [Twitter](link-to-twitter), or shoot me an [email](mailto:your-email@example.com) for any inquiries or collaborations.


