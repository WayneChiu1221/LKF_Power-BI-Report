# LKF_Power-BI-Report
A Power BI report that shows all the weekly spending of a couple in Bath,UK
Welcome! 

This file contains the screenshot of my Power BI reports, the actual pbix file and also the log.

If you are new to Power BI, please install Power BI desktop on your computer first. Please refer to https://powerbi.microsoft.com/en-gb/ .Alternatively, you can also refer to the pdf which is the screenshot of the Power BI report



**Methodology**

I manually consolidate all the expenses into excel with basic info 

**Dates**: The Date of transaction

**Merchant names** : Who are we paying to?

**Spending amounts**: The amount we paid


**Remark flag**: To indicate special expenses such as a trip to London. This flag can help me to filter out non-regular expense

**Paid by**: To indicate who is paying the expense (Wayne or Wayne’s wife)

**Full Year Expense**: To indicate if this expense is for long term or short term. Examples of long term expenses are gym year pass, transportation pass and furniture. Examples of short term expenses are grocery, movie tickets or dining at restaurants

Then, I will copy this excel to an SQL express server in my local computer and build two views - FY Expense & non-FY Expense. In the views, I will calculate # of the week. Then this two views will fit data into the Power BI report


Log

Version
Date
Description 
New Idea / Problem
1.0
21-Oct-21
First prototype of the Power BI report that could breakdown expense into general spending and long term spending


1.1
26-Oct-21
Updated Data 
Need to start figure out how to manage weeks data. 6 weeks data seems too much
Possible to make a tableau version?


1.2
05-Jan-22
Updated Data and month tabs

1.3 
16-Feb-22
Added an automatic date so the period would update automatically each refresh





