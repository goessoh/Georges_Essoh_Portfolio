# [Hotel-Recommendation-Analysis](https://github.com/goessoh/Hotel-Recommendation-Analysis)
Hotel recommendations are one of the most popular and widely used features of travel sites. This project aims to conduct an exploratory data analysis, perform variable engineering and predetermine the best models for an optimal recommendation.

![](/Images/istockphoto-1256667384-612x612.jpg)



# [Data-Preparation](https://github.com/goessoh/Data-Preparation)
This project demonstrates my ability to prepare data for further analysis, and it shows my ability to query databases and APIs and web scraping.
Pandas, BeautifulSoup and JSON libraries are used for web scraping and API queries, while Sqlalchemy is used to query databases.

![](/Images/istockphoto-1165363914-612x612.jpg)


# [Sentiment-Analysis](https://github.com/goessoh/Sentiment-Analysis)
This project explores techniques to mine and analyzes text data to discover useful knowledge: text mining, unstructured data, social networks, and other types of unsupervised data mining.

![](/Images/istockphoto-1196964881-612x612.jpg)



# [Life-Expectancy-Prediction](https://github.com/goessoh/Life-Expectancy-Prediction)
This project explores techniques to mine and analyzes large datasets to discover useful knowledge.

![](/Images/istockphoto-1351036587-612x612.jpg)


# [Predict-Customer-Loyalty](https://github.com/goessoh/Predict-Customer-Loyalty)
This project demonstrates the use advanced analysis and Machine Learning techniques using Python for predictive analysis(Classification).

![](/Images/istockphoto-897409724-612x612.jpg)


# [Predicting-medical-costs]()
This project is a compendium of various Machine learning techniques: Regression and classification to predict medical cost from an Insurance perspective.

![](/Images/istockphoto-1263521165-612x612.jpg)


# [Marketing-promotion-recommendation]()
This repository is an exploratory data analysis project with R to determine the ideal date for a marketting promotion at a Dodgers' game for maximum impact.

![](/Images/business-3080799__340%20(1).jpg)


# [Productivity-Prediction-of-Garment-Employees](https://github.com/goessoh/Productivity-Prediction-of-Garment-Employees)
This repository presents two approaches for predicting employees' productivity: time series analysis and regression using python.

![](/Images/woman-5762754_960_720.png)


<?xml version="1.0" encoding="UTF-8"?>
<rss version="2.0" xmlns:atom="http://www.w3.org/2005/Atom">
	<channel>
		<title>{{ site.name | xml_escape }}</title>
		<description>{% if site.description %}{{ site.description | xml_escape }}{% endif %}</description>		
		<link>{{ site.url }}</link>
		<atom:link href="{{ site.url }}/feed.xml" rel="self" type="application/rss+xml" />
		{% for post in site.posts limit:10 %}
			<item>
				<title>{{ post.title | xml_escape }}</title>
				<description>{{ post.content | xml_escape }}</description>
				<pubDate>{{ post.date | date: "%a, %d %b %Y %H:%M:%S %z" }}</pubDate>
				<link>{{ site.url }}{{ post.url }}</link>
				<guid isPermaLink="true">{{ site.url }}{{ post.url }}</guid>
			</item>
		{% endfor %}
	</channel>
</rss>
