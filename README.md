
# Real Time Use Case To Analyse vehicle's Fuel Efficiency based on vehicle characteristics correlation in python
-----

## Use Case :
**To Analyse vehicle's Fuel Efficiency based on vehicle characteristics correlation in python**

  . The dataset of vehicle fuel efficiency is from university of california. 
  . The vehicle characteristics can help explain fuel consumption (mpg).
  
Lets Start with Correlating the vehicle characteristics

### Correlation
The term "correlation" refers to a mutual relationship or association between quantities. In almost any business, it is useful to express one quantity in terms of its relationship with others.

### So, why is correlation a useful metric?
• Correlation can help in predicting one quantity from another
• Correlation can (but often does not, as we will see in some examples below) indicate the presence of a causal relationship
• Correlation is used as a basic quantity and foundation for many other modeling techniques

### Covariance
Covariance is a statistical measure of association between two variables X and Y.

Pearson Correlation Coefficient:
Pearson is the most widely used correlation coefficient. Pearson correlation measures the linear association between continuous variables. In other words, this coefficient quantifies the degree to which a relationship between two variables can be described by a line. 

### Spearman's Correlation:
Spearman's rank correlation coefficient can be defined as a special case of Pearson ρ applied to ranked (sorted) variables. Unlike Pearson, Spearman's correlation is not restricted to linear relationships. Instead, it measures monotonic association (only strictly increasing or decreasing, but not mixed) between two variables and relies on the rank order of values. In other words, rather than comparing means and variances, Spearman's coefficient looks at the relative order of values for each variable. This makes it appropriate to use with both continuous and discrete data.

### Kendall's Tau:
The third correlation coefficient we will discuss is also based on variable ranks. However, unlike Spearman's coefficient, Kendalls' τ does not take into account the difference between ranks — only directional agreement. Therefore, this coefficient is more appropriate for discrete data.
