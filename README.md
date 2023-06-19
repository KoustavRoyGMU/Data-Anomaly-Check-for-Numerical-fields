# Data-Anomaly-Check-for-Numerical-fields
Effective way to find data anomaly for numerical variables while importing data in R

# Problem Statement:
When we import files in R, the numerical fields often imported as Character due to some junk value entry in the source. As the field is imported as character, we can not perform numerical operations. If we convert the field forcefully to numerical, all the junk values are converted to null. if we analyze the data, sometimes we find the junk value is created by typo errors and that can be rectified.

# Solution:
When the R code passed with the proper parameter, we can check if any particular value is corrupted due to a typo error. If found, we can mass transform and then convert the field forcefully to numerical.

# Sample Output:
![image](https://github.com/KoustavRoyGMU/Data-Anomaly-Check-for-Numerical-fields/assets/113814191/69163f69-c52e-4b83-b9c1-6fdeeb14102d)



