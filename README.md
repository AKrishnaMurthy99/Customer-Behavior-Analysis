# Customer-Behavior-Analysis

## Project Description

This project explores customer behavior on an online shopping website, specifically focusing on the browsing habits and purchasing patterns of new and returning customers. By employing statistical and probability techniques, the goal is to uncover differences between these two customer groups and provide actionable insights to enhance marketing strategies. The analysis centers on data collected over the last year, with a particular focus on November and December, the busiest months for online shopping. The marketing team is interested in understanding customer engagement and determining the potential success of a new marketing campaign.

## Objectives

1. **Analyze Purchase Rates:**
   - Determine the purchase rates for online shopping sessions by customer type (new vs. returning) for November and December.

2. **Correlation Analysis:**
   - Identify the strongest correlation in total time spent among different page types for returning customers during November and December.

3. **Campaign Effectiveness:**
   - Estimate the likelihood of achieving at least 100 sales out of 500 online shopping sessions for returning customers, given a 15% boost in the purchase rate due to a new marketing campaign.

## Methodology

1. **Data Analysis:**
   - Clean and preprocess the dataset to focus on relevant features for November and December.
   - Compute and compare purchase rates between new and returning customers.

2. **Correlation Analysis:**
   - Analyze the correlation between total time spent and various page types for returning customers.
   - Identify the most significant correlations.

3. **Probability Estimation:**
   - Use statistical methods to estimate the likelihood of achieving the sales target with the proposed campaign boost.

## Dataset

The dataset includes the following columns:

| Column                   | Description                                                         |
|--------------------------|---------------------------------------------------------------------|
| `SessionID`              | Unique session ID                                                   |
| `Administrative`         | Number of pages visited related to the customer account             |
| `Administrative_Duration`| Total amount of time spent (in seconds) on administrative pages     |
| `Informational`          | Number of pages visited related to the website and the company      |
| `Informational_Duration` | Total amount of time spent (in seconds) on informational pages      |
| `ProductRelated`         | Number of pages visited related to available products               |
| `ProductRelated_Duration`| Total amount of time spent (in seconds) on product-related pages    |
| `BounceRates`            | Average bounce rate of pages visited by the customer                |
| `ExitRates`              | Average exit rate of pages visited by the customer                  |
| `PageValues`             | Average page value of pages visited by the customer                 |
| `SpecialDay`             | Closeness of the site visiting time to a specific special day        |
| `Weekend`                | Indicator whether the session is on a weekend                       |
| `Month`                  | Month of the session date                                           |
| `CustomerType`           | Customer type (new or returning)                                     |
| `Purchase`               | Class label indicating whether the customer made a purchase         |


## Conclusion

The findings provide valuable insights into customer behavior and can guide the marketing team in optimizing their strategies for the upcoming year. The analysis highlights key differences between new and returning customers and offers a statistical basis for evaluating the effectiveness of marketing campaigns.


