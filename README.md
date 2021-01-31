# Amazon_Vine_Analysis

## Overview
The analysis used PySpark to perform the extract, transform, and load (ETL) process on a select dataset (US Music) from Amazon. The ETL process used a Google Colaboratory notebook and then connected the data to an Amazon Web Services relational database (AWS RDS). The data was then loaded into a postgres database.<br>

Data: Amazon US Music https://s3.amazonaws.com/amazon-reviews-pds/tsv/amazon_reviews_us_Music_v1_00.tsv.gz


## Results
### Vine vs. Non-Vine Reviews
<img src="https://github.com/ChrisBarton107/Amazon_Vine_Analysis/blob/main/Resources/Paid.png" alt="drawing" height="150" width="600"/>

<img src="https://github.com/ChrisBarton107/Amazon_Vine_Analysis/blob/main/Resources/Unpaid.png" alt="drawing" height="150" width="600"/><br>
- Vine reviews: 7
- Non-Vine reviews: 105,979<br>

### Five Star Reviews
<img src="https://github.com/ChrisBarton107/Amazon_Vine_Analysis/blob/main/Resources/Five_Star_Paid.png" alt="drawing" height="150" width="600"/>

<img src="https://github.com/ChrisBarton107/Amazon_Vine_Analysis/blob/main/Resources/Five_Star_Unpaid.png" alt="drawing" height="150" width="600"/><br>
- Five Star Vine reviews: 0
- Five Star Non-Vine reviews: 67,580<br>

### Five Star Review Percentages
<img src="https://github.com/ChrisBarton107/Amazon_Vine_Analysis/blob/main/Resources/Five_Star_PPerc.png" alt="drawing" height="100" width="600"/>

<img src="https://github.com/ChrisBarton107/Amazon_Vine_Analysis/blob/main/Resources/Five_Star_UPerc.png" alt="drawing" height="100" width="600"/><br>
- Percentage of Five Star Vine reviews: 0%
- Percentage of Five Star Non-Vine reviews: Approximately 64%

## Summary
Based on the data collected, it is evident Amazon Vine reviews didn't influence this particular data set. Approximately 64% of Non-Vine reviews were five star reviews while 0% of Vine reviews were five star reviews, revealing no positivity bias for Amazon Vine reviewers in this dataset. 
