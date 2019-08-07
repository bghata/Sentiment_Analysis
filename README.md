# Sentiment_Analysis_of_iPhone_and_Galaxy

## Data Overview:

The objective of this study is to find out which device of (Apple iPhone & Samsung Galaxy) will be the best option to be bundled with the suite of smartphone medical apps for use by aid workers in developing countries.
The data was collected from “common crawl”, ”open repository of websites”, with the use of AWS.
The data has 60 attributes and 17,756 instances where each represents a website.
The method of analysis is based on sentiment analysis on website reviews (positive to negative). 

## Data pre-processing:

Beside the original datasets provided by Alert Analytics, additional examination of feature variance which is exploring the features with (near-zero variance). Features with no variance can be said to hold little to no information. Features that have very little, or "near zero variance", may or may not have useful information. 

Another analysis on the data was to use the Recursive Feature Elimination (RFE) which is a form of automated feature selection. RFE with random forest will try every combination of feature subsets and return a final list of recommended features.


## Models & Algorithms Tested:

-	Random Forest
-	Weighted K-Nearest Neighbors (KKNN)
-	Support Vector Machine (SVM)
-	Gradient Boosting Trees


## Amazon Web Services:
Amazon Web Services (AWS) is a subsidiary of Amazon which was launched in 2016, and it that provides on-demand cloud computing platforms to individuals, companies, and governments, on a metered pay-as-you-go basis.

The services used in this study are:
-	Elastic Compute Cloud (EC2)
-	Elastic MapReducer (EMR)
-	Simple Storage Service (S3)

The AWS technology is implemented at server farms throughout the world, and maintained by the Amazon subsidiary. 

Fees are based on a combination of usage, the hardware/OS/software/networking features chosen by the subscriber, required availability, redundancy, security, and service options. 

Subscribers can pay for a single virtual AWS computer, a dedicated physical computer, or clusters of either. 

As part of the subscription agreement, Amazon provides security for subscribers' system. AWS operates from many global geographical regions including 6 in North America.
