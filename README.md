# Stock-analysis-of-Tesla-organization

PowerBi Report

By looking at the dataset we have the columns such as:
1. Date : Data of stock
2. Open : Opening cost of stock 
3. High : Cost of stock when it was high
4. Low : Cost of stock when it was low
5. Close : closing of stock
6. Volume : Quantity of stock 
7. Adj Close : Adjustment of close

All the above was the defult column i have added few columns such as 

8. year : Extracted from date
9. Difference_high_low : Difference between the highest cost and lowest cost.
10. Difference_open_close : Difference between the opening cost and closing cost.
11. month: From Date 

# All the formulas to obtain the above columns 

```
1. =(Date.Year([year])) --> year column
2. =([High] - [Low])    --> Difference_high_low
3. =([open] - [close])  --> Difference_open_close
4. =(Date.Month([year])) --> month
```

# Let's start developing the dashboards and the question for the reports are:

![image](https://github.com/mukesh1996-ds/Stock-analysis-of-ABC-organization/blob/main/Images/Background.jpg)

