# EDA OBJECTIVE
# Finding features of customer profiles that have a tendancy to churn
# Dataset taken after Shavie's dataset clean at commit e9d186a20fbf4ebf48f40e0eef0ca02c751f7d29

# Method
# Find the most dominant customer profile that churned with all features
# Find all profiles like dominant churn in non-churn subset
# Highlight dominant features that lead to churn

# Findings
# With senior citizens excluded,
# The number of churns represents 23.6% of the whole dataset.
# Seniors make up 25.5% of all churns.
# Of those, a majority left after 1 month
# 0.2% more female churns than male
# 66.2% of customers that churned do not have partners
# 78.2% of customers that churned do not have dependents
# Month-to-Month contract type represents 87.2% of all churns, roughly 1'200 people
# 71.9% of the customers who churned used paperless billing
# 54.1% of customers that we on Electronic check payment method churned on high end 
#    \vs. 12.2% paying by automatic credit card payment on low end

# General observations
# Single females with no children on a monthly contract receiving paperless bills and paying via electronic check churned most.
# Their service profile is primarily phone service and fiber optic internet.
# About 3/4th had no online security, tech support, device protection or online backup services.



# Corrections
# Defer rows where seniors == yes
# Renamed labels for representation accuracy

# To do
# Tenure illustration needed
# MonthlyCharges illustration needed

# Other comments
# Column names need to be cleaned here and there
