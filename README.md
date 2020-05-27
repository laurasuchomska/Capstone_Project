# * Foresight *
Implementing data to inform business decisions

# Executive Summary

The Play Store apps data has enormous potential to drive app-making businesses to success. Actionable insights can be drawn for developers to work on and capture the Android market.
In a world overwhelmed by choice, decision making and buying behaviour encompasses more than a well-executed great idea. Consumers are relying on their fellow consumers' experience and feedback, regarding a purchased product or service. Currently, the demand for reviews is such, that even short cuts have been created for consumers to capture more reviews at a faster pace. They are known as Ratings! In the form of stars, points, thumbs up, etc. Together with more elaborated reviews, ratings have become pivotal in today's decision making and buying behaviour.
Consequently, this practice becomes an important question from the business perspective, as it can help companies to understand what the customer's current needs are, including costumer's profiling, target audience for certain types of Apps, and feedback for improving currently existing applications.
Ratings have become critical a factor for an app to go viral. So, before developers/investors even start spending time and money on creating an app, it is important to know what consumers have already said about similar apps. Assimilating consumers' feedback into the creation of a mobile application, could arguably be what determines its success or failure.
Foresight is a tool which uses machine learning techniques to investigate mobile apps ratings and help developers to anticipate potential issues with their mobile app design and execution.

# Key Files:
[Link]
Dataset (from Kaggle)
https://www.kaggle.com/lava18/google-play-store-apps
Power Point Presentation slides (pdf file)
file:///C:/Users/laura/Desktop/Capstone_Project/Capstone%20Project_slides.pdf
Jupyter Notebook
http://localhost:8888/notebooks/Foresight.ipynb

# Methodology:

1.	Importing Libraries
2.	Uploading data
3.	Features Description
4.	Data Cleaning
5.	Exploratory Data Analysis
6.	Data Visualization
7.	Data Preparation
8.	Modelling
9.	Evaluation

# Key Findings:

Findings from this investigation have shown 1) most popular App category is Family, and the least popular is the Events' Category. Amongst the most popular categories are: Games, Medical, Tools and Photography. The Distribution of Rating scores showed that most Apps which are normally rated, received scores between 4.0 and 4.7.Moreover, there is clear difference between the number of "Paid" (602) and "Free of Charge Apps" (7588).
The best performing model was the Random Forest Classifier when tuned with SkFlod hyper parameter (0.775). The model also performed well on the test dataset. Finally, the important features contributing to mobile apps' ratings are number of reviews, number of installations, and App size.

# Conclusions:

In conclusion, Play Store apps data has enormous potential to drive app-making businesses to success. Actionable insights can be drawn for developers to work on and capture the Android market. Foresight is a tool which uses machine learning techniques to investigate mobile apps ratings and help developers to anticipate potential issues with their mobile app design and execution.

# Recommendations:

-	Sentiment Analysis and Natural Language Processing of Reviews
-	Investigate the Role of Fake and Bot Reviews
