
Problem Statement: 
In the financial services and eCommerce ecosystem, organizations receive thousands of customer complaints daily. However, these complaints are:
•	Unstructured (text-heavy) 
•	Poorly categorized 
•	Slow to resolve 
•	Reactive rather than proactive 
This results in:
•	Increased operational costs 
•	Delayed resolution times 
•	Poor customer satisfaction 
•	Missed opportunities to identify systemic issues

This leads to the question on "How can we transform raw complaint data into actionable insights to reduce resolution time, operational cost, and improve customer experience?” identyfing the above statement as the business challenge.

Objective: Designing a data-driven complaint intelligence system that incorporates feature engineering technique from the existing data features to analyze response time, compliance length and sentimentality using NLP 
Dataset: 
•	Source: Kaggle Consumer Complaint Dataset (complaints.csv) 
•	Features include: 
o	Complaint narrative 
o	Product 
o	Issue
o	Date received 
o	Date sent to company
Solution Approach:
•	Cleaned and preprocessed text (NLP techniques) 
•	Tokenization, stopword removal, TF-IDF vectorization 
•	Created new features: 
o	Complaint length 
o	Sentiment score 
o	Resolution delay 


Insight Results:
After feature engineering, I performed statistical analysis to understand feature distributions. I observed that complaint length and resolution delay were highly right-skewed with significant outliers. While most complaints were resolved quickly, a small number showed extreme delays, indicating potential operational inefficiencies. Sentiment scores were mostly neutral, with fewer highly negative cases. These insights helped guide further preprocessing and model design.
