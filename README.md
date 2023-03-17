# REST-revenue-prediction-for-restaurants
## Machine Learning and Data Analysis applied to Hospitality

Welcome everyone!
I will be cooking for you today!

![rest01](https://user-images.githubusercontent.com/117359250/225934856-89dbfaa9-650a-4be4-a4a0-ad827d9d2b56.png)


This is something I’ve said so many times in the past 24 years. 
I stand here today as a data analyst, and former chef.


Today I will introduce you to Rest, revenue prediction for restaurants.


Restaurants are a very peculiar business. Let me tell you roughly why.

You love to eat, so you think selling food is a wonderful idea.
so…
You get a place, the best location you can find.

![rest02](https://user-images.githubusercontent.com/117359250/225935088-f2140e53-561d-4062-9dee-07f456b7abf4.png)


You fill it with extremely specific equipment, very expensive. 
There are parts of your new place that need to be hot, cold, dry, wet, ventilated, open, closed, beautiful, public, private.
You decorate it. Hopefully in good taste.
You recruit a huge team of people, mostly immigrants.
You fill it literally to the roof with things you want to transform and sell, but these things are food and they will go really really bad in a matter of hours, or days in the best cases.

And then???
Then you basically open the front door and wait for people to walk in.


In the restaurant industry there is a constant struggle to make informed decisions based on relevant data, because collecting and organizing data hardly ever seems to come as a priority.

But why is this??

Imagine yourselves facing a typical morning as a restaurant manager:

![rest03](https://user-images.githubusercontent.com/117359250/225935153-fee87d9f-31df-435b-b111-665b67517313.png)


You are there, standing, as suppliers are pushing the clock to unload hundreds of kilos of fresh vegetables, dozens of containers of raw fish covered with melting ice.
At the same time, last minute changes are reported on today’s menu because the line cook didn’t show up and the kitchen is understaffed.
Somehow, there’s a whole family of 6 in front of you asking for the allergens menu, because their little ones are all intolerant to something different.
And there’s a lady saying there’s a fire in the back, but you find time to explain it’s just the kitchen smoking pastrami now, because they ran out last night.

Sounds crazy, right?

Let us all take a deep breath.

Trust me: 
these people know what they do.

But I have a question:
Do they imagine what they COULD DO if we told them they don’t need to prepare for the unexpected?

This is Rest, a tool that tells you WHAT TO EXPECT.

![rest04](https://user-images.githubusercontent.com/117359250/225935248-4b627cb0-7cd9-4c3d-b6c9-6f34d4c7dbd7.png)


To develop Rest, we faced many challenges.
We proposed a collaboration with a traditional restaurant in the Gothic Quarter, near the Ramblas.
Since there are no substantial records of a predictive tool like this one, all explanations were received with a skeptical look, so we were trusted with confidential data only based on previous work experience and personal confidence.
 
We then collected and cleaned revenue data since 2020, and all the corresponding data on weather, holidays and relevant surroundings.
This daily sales data was reorganized by classifying in unified features, and merging together into a single coherent dataset, as well as dealing with duplicate observations and outliers.
We collected all 1900 reviews for our Case Study, by scraping public data available from Google Places, through the use of API’s.

Preprocessing the data was done by rescaling values, and selecting features according to the weight they represented.
An EDA showed that our Case Study was not the typical place for tourism, and instead revealed a clear pattern associated to local public. This way we could establish more importance for seasonality and weekdays as the most clear possible predictors.

![rest05](https://user-images.githubusercontent.com/117359250/225935330-076b5237-fbf2-4aad-b795-e0088d4fb350.png)


![rest06](https://user-images.githubusercontent.com/117359250/225935446-ff6fd3fc-3f2a-4853-9f00-aa1a59591d9b.png)

Our model has shown promising accuracy and has the potential to greatly impact the restaurant industry. By predicting revenue, restaurants can better manage their stock and staff, understand their target audience and plan marketing strategies, ultimately leading to increased profits.
Right now, Rest is forecasting daily revenue with a RMSE (Root Mean Square Error) of 120 euros, which is quite a great prediction.
We are still tuning and improving the model.

![rest08](https://user-images.githubusercontent.com/117359250/225935514-ebbf7a76-fee1-4cf5-ba1f-cbca4043e09f.png)


In terms of scalability of this project, we aim to predict, not just the revenue, but what dishes will be in demand, and what will the clients profile be, what action within the restaurant will engage more and better social media interaction, and more.
And of course, the necessary further analysis and recommendations to improve customer satisfaction and profitability.

This is a powerful combination of deep understanding of the industry, and the applied technology of Machine Learning with Python.

Rest is data analysis, and accurate forecast, applied to hospitality.


We know  the restaurant business is highly competitive and challenging.
It is definitely exhausting and requires restaurateurs to juggle a multitude of responsibilities.

So Rest is here to give these business men and women some peace of mind, and let them do what they do best: 
Create amazing magical dining experiences for their guests.


And when we, as guests, sit at a restaurant, in this public act of intimacy, we are bringing our emotions and our personal stories. Every meal we had with our family is a memory that can be potentially activated when we eat. So we want to be fed by people who are happy with what they do.

I will tell you a story of my own:

For countless Sundays I learned to make pasta with my great grandmother.
And guess what?
Before she broke the first egg, even she was asking for PREDICTIONS.
She used to ask “How many of us will be there for lunch?”


![rest09](https://user-images.githubusercontent.com/117359250/225935559-05b4353f-23fa-4094-8991-c9417df2218b.png)
