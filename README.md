

# YouTube Data Analysis Project

## Overview
This project involves a comprehensive statistical analysis of a dataset containing information about the top 1000 YouTubers. The dataset includes variables such as **Rank**, **Username**, **Categories**, **Subscribers**, **Country**, **Visits**, **Likes**, and **Comments**. The analysis is divided into four modules: **Normal Distribution**, **Estimation**, **Hypothesis Testing**, and **Multiple Linear Regression Analysis**.

The goal of this project is to uncover insights into YouTube performance metrics, such as subscriber counts, views, likes, and comments, and to understand how these variables influence the success of YouTubers.

---

## Dataset
The dataset used in this project was obtained from **Kaggle**. You can access the dataset here:  
[Top 1000 YouTubers Dataset](https://www.kaggle.com/datasets/mabelhsu/api-clean-top-1000-youtubers-statistics)

---

## Project Modules

### 1. **Normal Distribution**
- **Objective**: Determine the probability of YouTubers having more than 20 million subscribers.
- **Key Findings**:
  - The dataset is assumed to be normally distributed.
  - The probability of YouTubers having more than 20 million subscribers is **54%**.
- **Tools Used**: Excel, Z-score calculation.

---

### 2. **Estimation**
- **Objective**: Calculate the 95% confidence interval for the average number of subscribers.
- **Key Findings**:
  - The 95% confidence interval for the average number of subscribers is between **20,951,930** and **23,045,470**.
- **Tools Used**: T-distribution, Excel.

---

### 3. **Hypothesis Testing**
- **Objective**: Test whether the average number of comments across different YouTube categories is greater than 2400.
- **Hypotheses**:
  - **Null Hypothesis (H0)**: The average number of comments is equal to 2400.
  - **Alternative Hypothesis (H1)**: The average number of comments is greater than 2400.
- **Key Findings**:
  - The null hypothesis cannot be rejected at the 0.05 significance level.
  - There is no sufficient evidence to conclude that the average number of comments is greater than 2400.
- **Tools Used**: T-test, Excel.

---

### 4. **Multiple Linear Regression Analysis**
- **Objective**: Analyze the impact of subscribers, likes, and comments on the number of views/visits.
- **Hypotheses**:
  - **Null Hypothesis (H0)**: Subscribers, likes, and comments do not significantly influence the number of views.
  - **Alternative Hypothesis (H1)**: At least one of these variables has a significant impact on views.
- **Key Findings**:
  - The regression model is statistically significant (p-value < 0.05).
  - Subscribers, likes, and comments collectively have a significant impact on views.
  - The regression equation is:
    ```
    Estimated Visits = -428,620 + (0.0091 * Subscribers) + (21.62 * Likes) + (72.03 * Comments)
    ```
  - Example prediction: For a YouTuber with 59,700,000 subscribers, 156,500 likes, and 4,200 comments, the estimated number of visits is **3,801,464**.
- **Tools Used**: Multiple Linear Regression, Excel.

---

## Key Insights
1. **Subscriber Count**: There is a 54% probability that a YouTuber in the dataset has more than 20 million subscribers.
2. **Confidence Interval**: The average number of subscribers for the top 1000 YouTubers lies between 20.95 million and 23.05 million with 95% confidence.
3. **Comments Analysis**: There is no significant evidence that the average number of comments exceeds 2400 across different categories.
4. **Regression Analysis**: Subscribers, likes, and comments significantly influence the number of views, with comments having the highest individual impact.

---

## Tools and Technologies
- **Programming Languages**: Python (for data analysis and visualization).
- **Tools**: Excel (for statistical calculations and regression analysis).
- **Libraries**: Pandas, NumPy (for data manipulation and analysis).
- **Statistical Methods**: Normal Distribution, Confidence Intervals, Hypothesis Testing, Multiple Linear Regression.



## Future Enhancements
- Perform advanced visualizations using Python libraries like Matplotlib and Seaborn.
- Expand the analysis to include more variables, such as video length and upload frequency.
- Build a predictive model to estimate views based on historical data.

---



---

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
