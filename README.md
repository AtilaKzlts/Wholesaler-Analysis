![image](https://github.com/AtilaKzlts/Wholesaler-Analysis/blob/main/assets/bar.png)


<div align="center">
  <h1>Wholesaler Weekday&Weekend Sales Analysis</h1>
 </p>
</div>


## Table of Contents

- Project Introduction
    - Executive summary
    - About the Data Set
    - Objective
- Analysis Outputs
    - Hypothesis testing

## Project Introduction

This project aims to analyze the differences between weekday and weekend sales of our wholesale company in 2024. The distribution of weekday and weekend sales of key products, performance differences by category and annual sales trends will be analyzed. Statistical tests and visualizations will be used to identify which products and categories are more in demand on weekdays or weekends and to take the necessary steps to increase sales through proper marketing.


## Executive Summary:

- **Overall Sales Distribution:**  
  - Weekday sales account for the majority of total weekly sales.  
  - **Total weekly sales exceed 700,000 units, while weekend sales remain around 250,000**, showing higher volatility.  
  - Weekend sales are **lower and more inconsistent**, indicating greater demand fluctuations.  

- **Category Breakdown:**  
  - **Books had the highest sales**, with **251,783 units on weekdays** and **76,199 units on weekends**.  
  - **Clothing, home furnishings, and sporting goods** performed well on weekdays, while **electronics had the lowest sales overall**.  
  - **Weekday book sales were three times higher than on weekends**, emphasizing a strong weekday demand.  

- **Weekday vs. Weekend Sales Ratio:**  
  - **Weekday sales are 3x higher than weekend sales** across multiple categories.  
  - The book category exhibits the **largest gap**, highlighting the need for optimized inventory and supply chain strategies.  

- **Product-Level Insights:**  
  - **P006 shows high weekday variation**, requiring a **dynamic marketing and inventory strategy** to manage fluctuating demand.  
  - **P094 maintains stable sales across both periods**, making it suitable for a **low-risk inventory approach**.  
  - Some products display **significant differences between weekday and weekend sales**, while others remain more stable, requiring tailored strategies.  

- **Recommendations & Strategic Takeaways:**  
  - **Optimize inventory and supply chain management for strong weekday demand.**  
  - **Implement weekend-specific promotions, discounts, and campaigns to boost weekend sales.**  
  - **Use dynamic pricing and flexible inventory strategies for high-variability products like P006.**  
  - **Maintain cost-efficient stock levels for stable products like P094 to reduce inventory risks.**  


## About the Data Set

| Column Name    | Description                                              |
|----------------|----------------------------------------------------------|
| date           | Date of the transaction                                  |
| product_id     | Unique identifier for each product                       |
| category       | The category to which the product belongs                |
| price          | The price of the product                                  |
| sales          | Number of units sold for each product                     |
| stock          | Number of units available in stock for each product      |



## Objectives:

 - Comparing weekday and weekend sales distribution

 - Perform statistical tests to determine whether the differences between sales are significant
 
 - Which categories sell the most on weekdays and weekends?
 - Which categories are most affected by day type (weekday/weekend)?
 - The 10 best-selling products on weekdays and weekends
 - Analyzing weekday and weekend sales trends during the year and identifying trends

[See the Notebook](https://github.com/AtilaKzlts/Wholesaler-Analysis/blob/main/assets/wholoesaler.ipynb)
## Analysis Outputs

![image](https://github.com/AtilaKzlts/Wholesaler-Analysis/blob/main/assets/1.png)

Sales are mainly concentrated in the 0-20 range, while sales of 40 and above are very rare.
Stock levels are generally kept in the range of 0-50, but for some products, stocks can exceed 100.
The majority of product prices are between £0-500, with a particular concentration around £250. There are certain clusters in higher price ranges.
The category with the highest sales is books, followed by clothing and home. Electronics and sports products have lower sales volumes.

ㅤㅤㅤㅤㅤㅤㅤ
![image](https://github.com/AtilaKzlts/Wholesaler-Analysis/blob/main/assets/2.png)

While the distribution of sales on weekdays and weekends is broadly similar, the majority of sales are concentrated in the 0-40 range. Maximum sales values can exceed 100, but these values are quite rare. Weekend sales show more variability, with some days experiencing low sales more frequently. Weekday sales are significantly higher than weekend sales, with total sales of over 700,000 on weekdays and around 250,000 on weekends. According to the data, sales are predominantly on weekdays, with fluctuations in individual orders on weekends. The lower total sales compared to weekdays suggests that the business is in high demand on weekdays and that it may be beneficial to organize sales-boosting campaigns or promotions on weekends.

![image](https://github.com/AtilaKzlts/Wholesaler-Analysis/blob/main/assets/3.png)

When we analyze weekday and weekend sales by category, books stand out as the best-selling product category in both periods. Book sales are around 250,000 on weekdays and 75,000 on weekends. Although apparel is the category with the highest sales on weekends, weekday sales are lower than those of books. Household goods and sporting goods have moderate sales volumes in both periods. Electronic products stand out as the category with the lowest sales figures. In general, sales volumes are higher in all categories on weekdays, with book sales in particular increasing significantly on weekdays. This suggests that it may be beneficial to implement campaign or discount strategies for books and electronic products to increase sales on weekends.

![image](https://github.com/AtilaKzlts/Wholesaler-Analysis/blob/main/assets/4.png)
ㅤㅤ
Weekday vs Weekend Comparison:

+ Book
Weekday: 251,783 | Weekend: 76,199
Weekdays are 3.3 times higher than weekends.
+ Clothing:
Weekday: 157,897 | Weekend: 83,274
On weekdays, about twice as many as on weekends.
+ Electronics:
Weekday: 60,210 | Weekend: 21,834
Weekdays significantly more than weekends.
+ Household Goods:
Weekdays: 147,416 | Weekend: 44,342
Weekdays 3.3 times as many as weekends.
+ Sports Products:
Weekday: 100,327 | Weekend: 53,635
Weekdays are almost twice as long as weekends.

ㅤㅤㅤㅤㅤㅤ
![image](https://github.com/AtilaKzlts/Wholesaler-Analysis/blob/main/assets/5.png)

Sales Differences by Category:


+ Books: -175,584 (Against weekdays)
+ Clothing: -74,623 (Against weekdays)
+ Electronics: -38,376 (Against weekdays)
+ Home Furnishings: -103,074 (Against weekdays)
+ Sport: -46,692 (Against weekdays)

Overall Sales Differences:
Sales differences range between 47% and 70%.
The most affected categories are Books and Housewares.
Consumers' shopping behavior is generally shaped in favor of business days.
Weekday sales work against each category, with a significant decline especially in the Books category.

![image](https://github.com/AtilaKzlts/Wholesaler-Analysis/blob/main/assets/6.png)

**Low Sales Differential Products:**
- Product Codes:** F051, F008, F082, F076, F081, F081, F020, F017, F074
- Minimal change is observed in weekday and weekend sales.
- Stable and constant demand regardless of the day.
  
**High Sales Differential Products:**
- **Product Codes:** F089, F004, F029, F047, F010, F091, F033, F005, F025, F006
- There are significant sales differences between weekdays and weekends.
- They show high sensitivity to day type (working day and weekend).

**Key Findings:**
- Some products maintain their sales patterns and remain stable.
- Other products experience dramatic changes depending on the day.

**Critical Product Details:**

- **P006:** 
  - The product with the highest sales variability.
  - There are serious sales differences between weekdays and weekends.
  - Should be prioritized in marketing and inventory management. Because its sales show a high degree of variability and a strategy should be developed accordingly.
  
- **P094:** 
  - There is a sales pattern independent of days.
  - Minimal change in sales between weekdays and weekends.
  - Exhibits a low-risk and predictable sales trend with a stable demand profile.

In this analysis, it can be concluded that given the high variability of P006, marketing and inventory management should be more dynamic, while P094 can be managed with a low-risk strategy as it offers a stable and predictable sales process.

**Top 10 Products**
![image](https://github.com/AtilaKzlts/Wholesaler-Analysis/blob/main/assets/7.png)


**Yearly Trends**
![image](https://github.com/AtilaKzlts/Wholesaler-Analysis/blob/main/assets/8.png)

We can summarize the observations obtained from the analysis of monthly product sales patterns as follows:

**P006 Characteristics:**
- There is a clear peak in weekday sales, meaning that the product is mostly sold on working days.
- Sales peak in **August** and reach around **approximately 2250 units**.
- Weekday sales continue steadily in the other months.
- Weekend sales are quite low.

**P018 and P019 Observations:**
- Weekend sales are more balanced and stable.
- Compared to P006, there is an increase in P018 and P019 sales in **June**.
- Although sales fluctuate by month, the overall trend is stable.

**Critical Implications:**
- **P006**: This product can be defined as a product that focuses on business days and shows seasonal fluctuations. It peaks in August.
- **P018/P019**: Products with higher weekend consumption. Their sales are more balanced and consistent than during the week.
  

-----

### **Hypothesis testing**

+ H₀ (Null Hypothesis): There is no statistically significant difference between the medians of weekday and weekend sales. In other words, sales have similar distribution on weekdays and weekends.

+ H₁ (Alternative Hypothesis): There is a statistically significant difference between the medians of weekday and weekend sales. In other words, sales vary on different days of the week.

Hypothesis Test Result:


```
Normality Test for Weekday Sales:
NormaltestResult(statistic=5939.771752813036, pvalue=0.0)

Normality Test for Weekend Sales:
NormaltestResult(statistic=2073.919896685083, pvalue=0.0)

Levene Test (Homogeneity of Variance):
Statistic: 60.7659
p-value: 0.0000

Mann-Whitney U Test Results:
Statistic: 146544714.0000
p-value: 0.0000

Hypothesis Test Result:
p-value (0.0000) < 0.05, thus the null hypothesis (H0) is rejected.
```

There is a statistically **significant difference** between weekday and weekend sales.

-------

#### Post-Hoc
+ No normal distribution.
+ Variance is not homogeneous.

In this case we used the non-parametric Kruskal-Wallis test

Since Kruskal-Wallis found a significant difference, we used Dunn's Test to determine which days were different.

``` 
posthoc = sp.posthoc_dunn(df_hypo, val_col='sales', group_col='day_of_week', p_adjust='bonferroni')
print(posthoc)

              0             1             2             3             4  \
0  1.000000e+00  1.000000e+00  1.000000e+00  1.000000e+00  1.000000e+00   
1  1.000000e+00  1.000000e+00  1.000000e+00  1.000000e+00  1.000000e+00   
2  1.000000e+00  1.000000e+00  1.000000e+00  1.000000e+00  1.000000e+00   
3  1.000000e+00  1.000000e+00  1.000000e+00  1.000000e+00  1.000000e+00   
4  1.000000e+00  1.000000e+00  1.000000e+00  1.000000e+00  1.000000e+00   
5  4.140573e-10  1.230872e-09  1.875968e-09  1.183575e-10  2.080132e-10   
6  3.998982e-09  1.132433e-08  1.693210e-08  1.206819e-09  2.070223e-09   

              5             6  
0  4.140573e-10  3.998982e-09  
1  1.230872e-09  1.132433e-08  
2  1.875968e-09  1.693210e-08  
3  1.183575e-10  1.206819e-09  
4  2.080132e-10  2.070223e-09  
5  1.000000e+00  1.000000e+00  
6  1.000000e+00  1.000000e+00  
```

+ Monday - Friday Similar to each other
+ Saturday & Sunday Significantly different from weekdays
+ Saturday - Sunday Similar to each other


### [**Return to Portfolio**](https://github.com/AtilaKzlts/Atilla-Portfolio)
