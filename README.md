# Counting-Claims-A-Statistical-Deep-Dive-into-Dental-Reimbursements
This project analyzes a random sample of dental claims to estimate average reimbursements for 2021. Confidence intervals are constructed at 90%, 95%, and 99% confidence levels using Excel. The analysis blends statistical rigor with practical healthcare finance insights, revealing how data informs reimbursement understanding


# Estimating Average Reimbursement for Dental Claims

## Project Overview
This project focuses on estimating the average reimbursement amount for dental claims in 2021 for Healthy Life, a company with an extensive client base. Due to the impracticality of calculating the population mean directly, a random sample of 49 dental claims was selected using Excel’s Random Number Generator function.

## Objectives
1. **Calculate the Mean and Standard Deviation**: Determine the average reimbursement and the variability in the data.
2. **Construct Confidence Intervals**: Create 90%, 95%, and 99% confidence intervals to estimate the true average reimbursement.
3. **Visualize Data Distribution**: Build a histogram to assess the symmetry and bell-shaped nature of the data distribution.
4. **Apply Statistical Techniques**: Utilize t-distribution for the analysis due to the sample size and potential non-normality.

## Data Analysis Steps

### 1. Data Collection
A sample of 49 dental claims was collected, consisting of various reimbursement amounts. The data includes both individual claim amounts and summary statistics.

### 2. Descriptive Statistics
Using Excel’s Descriptive Statistics function, the following key metrics were calculated:
- **Mean**: $283.54
- **Standard Deviation**: $128.83
- **Standard Error**: $18.40
- **Median**: $250
- **Mode**: $250
- **Range**: $852

### 3. Confidence Intervals
Using the mean and standard error, confidence intervals were calculated as follows:

- **90% Confidence Interval**:
  - Margin of Error: $30.87
  - Confidence Interval: \[ $252.67, $314.41 \]

- **95% Confidence Interval**:
  - Margin of Error: $37.00
  - Confidence Interval: \[ $246.54, $320.54 \]

- **99% Confidence Interval**:
  - Margin of Error: $49.36
  - Confidence Interval: \[ $234.18, $332.90 \]

### 4. Histogram Construction
A histogram was created using specified bin values to visualize the distribution of the dental claims. This allows for an assessment of whether the data is approximately symmetric and bell-shaped, confirming the applicability of the t-distribution for our confidence intervals.

### 5. Interpretation of Results
The constructed confidence intervals provide a range in which the true average reimbursement is likely to fall, with increasing confidence levels allowing for a better understanding of the uncertainty in the estimates. The histogram visualization supports the assumption of normality required for statistical inference.

## Conclusion
This project successfully estimates the average reimbursement amounts for dental claims through rigorous statistical methods, combining practical insights into healthcare finance with solid mathematical foundations. The analysis not only informs Healthy Life about their reimbursement trends but also exemplifies the value of data-driven decision-making in healthcare.

## Skills Utilized
- Mathematical Statistics
- Probability Theory
- Confidence Interval Construction
- Data Visualization

