# mobile-price-classification
Background:
Bob has started his own mobile company. He wants to give a tough fight to big companies like Apple, Samsung, etc.

He does not know how to estimate the price of mobiles his company creates. In this competitive mobile phone market you cannot simply assume things. To solve this problem he collects sales data of mobile phones of various companies.

Bob wants to find out some relation between features of a mobile phone(e.g.:- RAM, Internal Memory, etc) and its selling price. But he is not so good at Machine Learning. So he needs your help to solve this problem.

In this problem, you do not have to predict the actual price but a price range indicating how high the price is

**Price_range is the target variable with value of 0(low cost), 1(medium cost), 2(high cost) and 3(very high cost)**

[Source: Kaggle]

## What is in the project<p>
1. Exploratory Data Analysis
2. Data Visualization
3. Feature Engineering (feature scaling, checking multicollinearity)
4. Machine learning modeling with classification algorithms (Logistic Regression, KNN Classifier, Linear SVC, AdaBoost, Random Forest)
5. Apply prediction to new and unseen data

## Machine Learning Model Result
Highest accuracy; Linear SVC with around 97% accuracy

## Conclusion
This is the result of the prediction of new & unseen data from Bob vs actual data that Bob collected from competitors

![image](https://github.com/amandasbrn/mobile-price-classification/assets/66349501/9c26ca83-73d4-4d98-b1ca-a93247cb9a3a)

From the data, we can conclude that battery power, RAM, resolution, and weight affect the price range the most. Since the model accuracy is 97.2%, it did a great job of discovering the pattern and relationship between each element and the price.
My suggestion is; it will be much easier for Bob to segment his customers for the next step to target them accordingly. For instance:
1. Some people highly consider RAM, resolution, memory, and battery power, such as gamers, which are fulfilled by price range 3. Bob can invest in those elements to make specific phone series to appeal to this group of customers.
2. There are also people who look for the best phones based on their specifications without belonging to any specific group (such as gamers) and they can also be enticed by the fact that it is lightweight. Price Range 3 offers a complete package.
3. Interestingly, lower price ranges have a better front camera and primary camera megapixels. This can attract customers who buy phones because of the camera, for example, content creators, photographers, or just casually like photography and videography in general.
4. Besides camera quality, lower price ranges also have decent internal memory (don't have that much difference with the most expensive phones) and screen resolution. This will be worth the price for budget-conscious customers.

From the data, Bob's company can strategically market its mobile phones based on the features that are most competitive in each price range. For example, for high-end phones, marketing campaigns can highlight RAM, internal memory, and screen quality, while lower-priced phones can excel in terms of camera megapixels.
