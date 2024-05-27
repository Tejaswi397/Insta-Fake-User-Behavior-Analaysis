# Instagram-Fake-User-Behavior-Analysis Project
The aim of this project is to build and train the dataset using various machine learning algorithms, evaluate their accuracy, and perform detailed metrics analysis. The goal is to identify the best model based on F1-score and recall.

## Introduction:
Instagram is definitely one of the most popular social-media platforms in the world. which has a wide range of audience of all groups, Instagram became more than simply a photo-sharing platform. People use it for marketing, for sharing their political views, educational purposes, and to make businesses!

## 1. Problem Statement:
1. This project focuses on analyzing user behavior on Instagram to gain insights into user engagement, preferences, and overall experience. Key areas include user engagement metrics, content analysis, demographics, follower growth/churn, influencer analysis, brand advocacy, story engagement, page factors, and user journey analysis. Privacy and ethical considerations align with Instagram's terms of service and data usage policies.
2. Machine learning can be used to avoid having major issues with these fake accounts. By using models for classification tasks, it’s possible to easily detect whether an account is real or fake.

## Input Features:
This Data was taken from kagglecom.The dataset contains 13 features with 785 records. Here is the overview of the 13 features:
S.No	Feature Name	Description	Type	Example
 1. edge_followed_by:	Number of followers of the Instagram account	(Numeric)
 2.	edge_follow:	Number of accounts that the Instagram account follows	(Numeric)
 3.	username_length:	Length of the username of the Instagram account	(Numeric)	
 4.	username_has_number:	Binary indicator if the username contains a number	Categorical	(Yes)
 5.	full_name_has_number:	Binary indicator if the full name contains a number	Categorical	(No)
 6.	full_name_length:	Length of the full name of the Instagram account	(Numeric)
 7.	is_private:	Binary indicator if the account is private	Categorical	(Yes)
 8.	is_joined_recently:	Binary indicator if the account was joined recently	Categorical (No)
 9.	has_channel:	Binary indicator if the account has a channel	Categorical	(Yes)
 10.	is_business_account:	Binary indicator if the account is a business account	Categorical	(Yes)
 11.	has_guides:	Binary indicator if the account has guides	Categorical	(No)
 12.	has_external_url:	Binary indicator if the account has an external URL	Categorical	(Yes)
 13.	is_fake:	Binary label indicating if the account is fake	Target	1 (Yes)

Through a quick data inspection, it was possible to see that the train set consists of 628 samples, while the test set consists of 157 samples. Both sets have the same 13 attributes. 

## Exploratory Data Analaysis
## Comparsion Between Business Account and Personal Account
https://github.com/Tejaswi397/Insta-Fake-User-Behavior-Analaysis/assets/115448356/a674d6cd-739e-47a9-9119-f4d7259f711c"
