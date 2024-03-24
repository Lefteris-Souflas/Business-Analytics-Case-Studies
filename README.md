## Business Analytics Case Studies

This assignment consists of three case studies, covering market basket analysis (association rules), customer segmentation (clustering), and campaign management (customer response model). Each case study contributes to a portion of the overall grade, with the first case study accounting for 15%, the second for 25%, and the third for 60%. Answers to the questions must be provided using **SAS Visual Data Mining and Machine Learning** on **SAS Viya** in order to explore and analyze the given data.

### Deliverable
The deliverable for this assignment is a single report containing answers to all three case studies. The report should be formatted to address both technical and business audiences appropriately, with executive summaries provided at the beginning of each case study.

### Case Study 1: Market Basket Analysis (15%)
#### Buy-books-on-line.com
#### In Summary
- **Problem**: Exploiting cross-selling opportunities for books related to "Business Analytics."
- **Data Set**: "On_Line_Book_Store" containing 19,805 past sales transactions.
- **Task**: Apply association rules to identify next best offer propositions.
- **Questions**: 
  1. Write Executive Summary.
  2. Chart sales of each book.
  3. Identify books to advertise based on association rules.
  4. Determine most frequently bought sets of books.

#### In Detail
Buy-books-on-line.com is an on line store that sells books about science and information technology. The store is very well known in the academic community so a lot of its customers are university professors and also librarians at universities buying on behalf of their institutions. A very popular category of the books that the store sells is that related to “Business Analytics”. In this category the store has a list of 56 books such as “Credit Risk Analytics”, “Marketing Analytics”, “Analytics at Work” etc. The past year 1,896 customers have bought at least one book that belongs to the “Business Analytics” category i.e. at least one of the 56 books.
The sales department of the store wants to exploit cross selling opportunities so as to sell as many books as possible. The optimal way to achieve this, is to do wise next best offer propositions to its customers by applying associations rules. The analytics department of the store has collected a data set with 19,805 past sales transactions related to the “Business Analytics” book category. The data set is called “On_Line_Book_Store”.
You are hired as an analyst by the on-line store to aid the analytics department in this market basket analysis initiative. After the data analysis you should write a report to the analytics team of the company (technical people) to explain them what you did, which method you used, how it works and what were your results. As already said the report should contain an executive summary in a business format. Use as minimum support level the 0.05 and as minimum confidence level the 0.1. Also set the maximum number of items in a rule equal to 3 (three) (in the interface this option is referred erroneously as minimum number of items in a rule). Save the rules table in the CASUSER library with the title MBA_Results. In the main body of the report you should answer the following questions:
1) Write the Executive Summary. This part accounts for 20% of the case study’s mark.
2) What are the sales (in units) of each book? Provide a relevant chart (bar chart) using the SAS Visual Analytics software. Enrich the chart so as to show data labels, chart title, titles in both axis. This question accounts for 20% of the case study’s mark.
3) Which two books should the store advertise to customers who bought/ are searching to buy only one of the following:
• Managerial Analytics
• Implementing Analytics
• Customer Analytics for Dummies
• Enterprise Analytics
In other words create the Amazon’s “Customers who Bought this Item also bought” list of books. What is the biggest lift of the rules with three (3) items where each one of the above mentioned 4 books is on the left side of the rule? How is it interpreted? This part accounts for 30% of the case study’s mark.
4) If you set the maximum items in a rule to 3, which are the 3 books most bought together by customers? How many occurrences of this set of 3 books are found together? What does this number mean? What is the support metric of this set of 3 books and how is it calculated? This part accounts for 30% of the case study’s mark.

### Case Study 2: Customer Segmentation (25%)
#### Sports-OnLine.com
- **Problem**: Understanding market through customer segmentation analysis using RFM technique.
- **Data Set**: "RFM_Final_Practice.sas7bdat" containing 995 customers' transactions.
- **Task**: Perform clustering and profiling of customer segments.
- **Questions**: 
  - Write Executive Summary.
  - Name segments and propose marketing actions for each.

### Case Study 3: Campaign Management (60%)
#### XYZ Insurance
- **Problem**: Develop machine learning model for fraud detection in insurance claims.
- **Data Set**: "Historical_Claims_Final" containing claims data from May - August 2017.
- **Task**: Build model to predict fraudulent claims for new data.
- **Questions**: 
  - Write Executive Summary.
  - Interpret profit matrix.
  - Determine minimum probability for fraudulent claims.
  - Partition historical data for training and validation.
  - Analyze missing values and proportion of fraudulent claims.
  - Evaluate decision tree and logistic regression models.
  - Score new claims and analyze results.

*For detailed data dictionary, refer to the end of the document.*
