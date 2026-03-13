# Walking Through a Customer Segmentation Case Study

[Let's Work on a Data Science Project Together](https://karina-datascientist.beehiiv.com/p/data-science-project)
 - From the Karina Datascientist's Newsletter by Karina Samsonova
 - Dated 3/13/2026

I worked through this sample project from The Karina Datascientist's Newsletter, which provided an opportunity to explore the different customers in a retailer's customer and order list. The data is from an actual UK based online retailer for transactions occurring between January 2010 and September 2011 and can be found in the UC Irvine Machine Learning Repository "Online Retail" (also called number 352).

The goals of this exercise were 
1. practicing data ingestion, feature engineering, and unsupervised learning with K-Means clustering
2. extracting the business insights from the segmentations 
   - identifying the customer segment with the most positive impact on sales based on RFM
3. challenging ourselves to add Average Order Value to the segmentation analysis

Further, I added the following work:
   - question: would adding Average Order Value to the segmentation analysis would identify the same segment as most impactful
   - conclusion: Adding AOV in this use case did not change which segment was identified as most impactful
 
Data Source: 
Chen, D. (2015). Online Retail Dataset. UCI Machine Learning Repository. 
 - [doi](https://doi.org/10.24432/C5BW33.)
 - [pdf version of the paper](https://link.springer.com/content/pdf/10.1057/dbm.2012.17.pdf)

Folder structure
```
walk-thru-customer-segmentation/
  ├── Draft Findings.docx                       # Metrics and analysis from notebook results
  ├── README.md                                 # this file
  └── walk-thru-customer-segmentation.ipynb     # python notebook to retrieve, ingest, feature engineer, run unsupervised learning, identify results
```
