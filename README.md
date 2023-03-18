# Zomato-Restuarant-Clustering-Sentiment-Analysis


![zomato](https://user-images.githubusercontent.com/116551866/226087778-ddec77be-1e3a-4cd6-ba0f-17de92db14d2.PNG)


**This project is about Zomato. It is a restuarant aggregator and food delivery start-up founded by Deepinder Goyal and Pankaj Chaddah in 2008. Zomato provides information, menus and user-reviews of restuarant and also food delivery options from partner restuarant in selected cities.**


# 📋 Problem Satement
#**The project focuses on Customer and Company, by clustering the restuarant on cuisine and cost vs benefits and finding out top critics in the industry will help restuarant, so they can colaborate with critics and promote their restuarant on Zomato and on Social media. Understanding the sentiment of review's will help Zomato, SO they can improve their Business in terms of serviec and operations.**

# 📋 Visualizations

# 1) Most expensive restuarant
![Cost](https://user-images.githubusercontent.com/116551866/226087928-aea98bf9-934c-45fe-bd13-29268e4fba6a.PNG)

# 2) Least expensive restuarant
![leastex](https://user-images.githubusercontent.com/116551866/226088243-c73967f7-a42c-4d4b-958c-2837e1d5d447.PNG)

# 3) Most 15 served cuisines
![mostserved](https://user-images.githubusercontent.com/116551866/226088266-6846de7e-dca9-4868-9b44-915aa91a3906.PNG)

# 4) Most 15 used tags
![taggs](https://user-images.githubusercontent.com/116551866/226088281-3099cc6b-6a14-4ac3-95c8-79b461afc70a.PNG)

# 5) Elbow Method
![no_scluter](https://user-images.githubusercontent.com/116551866/226088306-b11829ac-2afc-4e14-ba1f-4735c3bd6047.PNG)

# 6) Silhuoette coefficient
![Silhuoette coefficient](https://user-images.githubusercontent.com/116551866/226088335-dac3a481-a89f-42da-809e-f1c3fa0457fe.PNG)

# 7)Silhuoette score
![Silhuoette score](https://user-images.githubusercontent.com/116551866/226088376-ae7836ee-d824-4efc-b38a-a96e64d91999.PNG)

# 8) Average cost of clusters
![clustercost](https://user-images.githubusercontent.com/116551866/226088404-c88a7a04-de74-4e77-b208-ea2db4fd10ef.PNG)

# 9)Raintg
![rating](https://user-images.githubusercontent.com/116551866/226088715-859ba5ee-39df-4337-873e-0db59c75e05c.PNG)

# 10) Restuarant by Rating
![resbyrating](https://user-images.githubusercontent.com/116551866/226088779-70688a0b-544e-431a-aa71-4321acdb95ca.PNG)

# 11) Critics by followers
![criticsfollower](https://user-images.githubusercontent.com/116551866/226088987-c2e07e52-e7b4-4c3b-901d-d0211777164b.PNG)

# 12) Critics by revies
![criticsrev](https://user-images.githubusercontent.com/116551866/226089136-2b6d5eab-e5c9-4a5a-afd6-7e0c269ff992.PNG)

# 13) Sentiment of reviews according to rating
![senti](https://user-images.githubusercontent.com/116551866/226089256-d509a4db-90fa-49ef-9e29-23c60ae17b63.PNG)

# 📋 Model Used-

# 1) KMeans Clustering
![Kmeans](https://user-images.githubusercontent.com/116551866/226089618-4e91c2f3-2d17-45e9-91a6-768892cbd6fa.PNG)

# 2) Dendogram
![dendo](https://user-images.githubusercontent.com/116551866/226089624-2f1d5039-3a0c-4b05-bdf4-7d6c01dda485.PNG)

# 3) Agglomerative clustering
![aggloroclus](https://user-images.githubusercontent.com/116551866/226089621-c61a5747-6cda-4a33-85cb-620957908b00.PNG)



# 📋 Model Performance
![table1](https://user-images.githubusercontent.com/116551866/226089411-624e4653-d6b4-489d-9901-0531f5ab8e61.PNG)

![Table2](https://user-images.githubusercontent.com/116551866/226089414-a3ef81c7-422f-4cc2-8ef8-20777d435598.PNG)

# 📋 Conclusion



*   In EDA part found out:



1.   Top 10 resturant by rating.

2.   Top 10 resturant by critics.

3.   Top 10 resturant by Cost.

4.   Top 10 Critics by follower.

5.   Top 10 Critics by reviews.

6.   Cost of fast foods is very low.

7.   The cost vs benefit of Standard restuarant is high and Delight restuarant is low.

8.  Through NLP we found that higher the rating, positive is the sentiment and lower the rating, negative is the sentiment. 


# Conclusion from above data wrangling, that this top 10 critic's by follower are very important, b'coz they have follower and people trust thier reviews and rating. So a Restuarant can call this critic's and can colaborate with them to promote thier restuarant on Zomato and on their blogs. Which will increase the trust among new customers and bring them more revenue.

# For clustering the restuarant both we can use both model as the clsuter of both models is same.  

# In this project we've final NaiveBayes model for understanding the sentiment, b'coz it's f1 score is 79% and here model f1 score is important. f1 score is the final metric we're taking into account
