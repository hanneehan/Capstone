# Capstone
## Project Overview
Gathering information and analyzing information to assist our decision is one of the born nature of human beings. Crowd-sourced review and rating platforms such as Yelp and Google review are oftentimes the only source where consumers can obtain a priori information before they decide to explore a new restaurant/bar/local service/etc that they have never been to. According to Nielson, 92% of customers read Yelp review before they make a purchase. However, such review/rating platforms often yield two major problems: fake reviews/ratings and reviews/ratings that are distored by personal bias. 

Fake reviews are in most cases produced for two purposes. The most common scenario is where business owners hire people write positive reviews to get more popularity for their business. The second occasion, not as often as the first kind, business owners might hire people write negative reviews to taint the reputation of their competitor. Fake reviews, no matter which kind, can have great impact on both the business and the customers. 

Besides fake reviews, users of review/rating platform may encounter another issue: inconsistent reivews/ratings. Think about two examples. Restaurant A and B both have 5 reviews and average ratings of 4 stars. Individual ratings of Restaurant A are [4, 4, 4, 4, 4]. One the contrary, ratings of restaurant B are not so evenly distributed with individual ratings of [5, 5, 5, 2, 3]. How would one decide between these two restaurants? In fact, everyone has one's own internal rating scale even though everyone's sharing the same 5-point Likert Scale. Does my 3 stars the same as yours? Does his 4 stars really higher than your 3 stars? Without a common ground(“an imaginary rubric for reviewing restaurants in Yelp"） that everyone agrees, it is impossible to equate ratings that are created by the individuals that may have very different rating styles. 

 The current project is initiated based on these two commonly existing problems of review/rating system. To solve fake review problem, I aim to develop a methodology with several screening standards (from the low level screening to the most strict level screening) , with each standard developed based on the review-relevant variables, user-relevant variables and business-relevant variables. Based on the results of screening, a validity score will be computed. A review/ratings with low validity score suggests high chance of being a fake review and vice ver sa. For the inconsistent rating/reviews, my plan is to use reviewer's record of reviews/ratings and the reviews/rating record of the same business to evaluate a reviewer's rating pattern and extremity, for example, if a reviewer is always giving rating that are way lower than average rating of business, across different business, that suggests the reviewer's strict raters and the strictness will be quantified by a quantile score of the yelp crowd.

## Data Description
The dataset of the current project is provided by Yelp for academic research. There are 5 subparts of the meta data: business data, review data, user data, tip data and checkin data. See more detailed description for the dataset and the variables included in each dataset, please refer to the data library via the link： https://docs.google.com/spreadsheets/d/1_m0FnvOcA-6uToc7MPNTf5lInwHhaU2DUEQBI-ag5i8/edit#gid=0  
