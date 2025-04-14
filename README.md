# Banking-Analysis
# Key Insights from Visualizations
### 🔹 Distributions (Histograms & Boxplots)
Age, Balance, Duration, Pdays, Previous show right-skewed distributions, indicating most values are on the lower end, but some outliers are much higher.

Campaign is also skewed: Most people were contacted only a few times.

### 🔹 Outliers (Boxplots)
Balance has numerous high outliers—some clients have extremely high account balances.

Duration and Pdays also have noticeable outliers.

Previous has spikes, suggesting some clients were contacted many times in the past.

### 🔹 Nominal Attributes (Bar & Pie Charts)
Most common jobs: blue-collar, management, and technician.

Marital status: married people dominate.

Pie charts confirmed the same patterns with visual proportions.

### 🔹 Binary Attributes (Bar Charts)
Default: Vast majority do not have credit in default.

Housing & Loan: Most have housing loans, fewer have personal loans.

Target (y): Majority of clients did not subscribe to a term deposit.

### 🔹 Correlation Matrix
Most numeric variables have weak correlations.

Slight positive correlation between pdays and previous.

Duration shows a moderate correlation with the target variable y, which may imply longer calls are associated with positive outcomes.

## 📈 Patterns Observed
Longer call duration is often associated with a higher chance of a positive response (y = yes).

Individuals with multiple contacts in past campaigns (previous > 0) might be more likely to respond positively.

Clients who are unmarried or younger may show different behavior trends—needs deeper segmentation.

### ⚠️ Outliers and Data Issues
Balance has extreme values—consider log transformation or outlier capping.

Pdays includes -1 values, which often means the client was not previously contacted—this needs special treatment in analysis.

## 📦 Data Quality
Very few missing values (mostly handled).

Categorical attributes like job, education, and marital are clearly classified and visualized.
