# anime-recommendation-system
Abstract
During the last few decades, alongside the rapid globalization, the market for television media has expanded considerably. This is especially the case for anime, a style of Japanese film and television animation which is typically aimed at adults as well as children. With digitalization, anime is readily available for viewers worldwide; However, the manner in which anime movies and shows are recommended to the targeted audience remains lacklustre despite the constant efforts made towards its development. This project aims to aid this problem and improve the overall viewer experience; the system focuses on the recommendation algorithm to bring the viewer anime suggestions based on their previously watched anime. It additionally provides the user with similar anime suggestions based on their search.

Keywords- Matplotlib, Seaborn, Python, Numpy, Pandas, Sklearn.

Introduction 
Data Science:
Data science is an interdisciplinary field that uses scientific methods, processes, algorithms, and systems to extract knowledge and insights from noisy, structured, and unstructured data, and apply knowledge and actionable insights from data across a broad range of application domains. Data science is related to data mining, machine learning and big data. 

Those who practice data science are called data scientists, and they combine a range of skills to analyze data collected from the web, smartphones, customers, sensors, and other sources to derive actionable insights.

Data science encompasses preparing data for analysis, including cleansing, aggregating, and manipulating the data to perform advanced data analysis. Analytic applications and data scientists can then review the results to uncover patterns and enable business leaders to draw informed insights. 
  

Data Analytics
Data analytics is the process and practice of analyzing data to answer questions, extract insights, and identify trends. Across industries and around the world, data analysts use different tools, techniques, and frameworks to derive actionable business insights from raw data.  

Data analysis bridges the gap between data scientists and business analysts. It provides with the questions that need answering from an organization and then organize and analyze data to find results that align with high-level business strategy. 

Data analysts are responsible for translating technical analysis to qualitative action items and effectively communicating their findings to diverse stakeholders.
Skills needed: Programming skills (SAS/ R/ Python), statistical and mathematical skills, data wrangling, data visualization.

 

NumPy 
NumPy (numerical Python) is a library that consists of multidimensional array objects and a set of functions for manipulating them. It’s one of the most used Python packages for scientific computing as it allows you to perform mathematical and logical operations on arrays. NumPy is a Python scripting language.

Pandas
Pandas is an open-source Python Library providing high-performance data manipulation and analysis tool using its powerful data structures. The name Pandas is derived from the word Panel Data – an Econometrics from Multidimensional data.

SciPy 
SciPy is an open-source library used for solving mathematical, scientific, engineering, and technical problems. It allows users to manipulate the data and visualize the data using a wide range of high-level Python commands. SciPy is built on the Python NumPy extension. SciPy is also pronounced as “Sigh Pi.”

Scikit-Learn (Sklearn)

Scikit-learn (Sklearn) is the most useful and robust library for machine learning in Python. It provides a selection of efficient tools for machine learning and statistical modeling including classification, regression, clustering and dimensionality reduction via a consistence interface in Python. This library, which is largely written in Python, is built upon NumPy, SciPy and Matplotlib.

Matplotlib
Matplotlib is a cross-platform, data visualization and graphical plotting library for Python and its numerical extension NumPy. As such, it offers a viable open source alternative to MATLAB. Developers can also use matplotlib’s APIs (Application Programming Interfaces) to embed plots in GUI applications.

Seaborn
Seaborn is a Python library created for enhanced data visualization. It’s a very timely and relevant tool for data professionals working today precisely because effective data visualization – and communication in general – is a particularly essential skill. Being able to bridge the gap between data and insight is hugely valuable, and Seaborn is a tool that fits comfortably in the toolchain of anyone interested in doing just that.



Cosine Similarity
•	Difficulty Level : Basic
•	Last Updated : 06 Oct 2020
Prerequisite – Measures of Distance in Data Mining
In Data Mining, similarity measure refers to distance with dimensions representing features of the data object, in a dataset. If this distance is less, there will be a high degree of similarity, but when the distance is large, there will be a low degree of similarity.
Some of the popular similarity measures are –
1.	Euclidean Distance.
2.	Manhattan Distance.
3.	Jaccard Similarity.
4.	Minkowski Distance.
5.	Cosine Similarity.
Cosine similarity is a metric, helpful in determining, how similar the data objects are irrespective of their size. We can measure the similarity between two sentences in Python using Cosine Similarity. In cosine similarity, data objects in a dataset are treated as a vector. 

The formula to find the cosine similarity between two vectors is –
	Cos(x, y) = x . y / ||x|| * ||y||
where,
•	x . y = dot product of the vectors ‘x’ and ‘y’.
•	||x|| and ||y|| = length of the two vectors ‘x’ and ‘y’.
•	||x|| * ||y|| = cross product of the two vectors ‘x’ and ‘y’.

This data set contains information on user preference data from 73,516 users on 12,294 anime. Each user is able to add anime to their completed list and give it a rating and this data set is a compilation of those ratings. The data was obtained thanks to YONATAN RABINOVICH from Kaggle(https://www.kaggle.com) and MyAnimeList(https://myanimelist.net) API.

RESULT

In this project, a recommendation algorithm based on cosine similarity was created. This project was able to aid the above-stated problem and improve the overall viewer experience; the system focuses on the recommendation algorithm. to bring the viewer anime suggestions based on their previously watched anime. It additionally provides the user with similar anime suggestions based on their search.

CONCLUSION

Anime dataset had missing rating data by 1.87%. Most anime type present in the dataset is by Television and genre present by frequency in the dataset is Hentai. The predictions have an accuracy of 60% (approx).

REFERENCE
1.	www.kaggle.com
2.	www.youtube.com
3.	www.github.com
4.	www.researchgate.net
5.	scholar.google.com
6.	www.journals.elsevier.com
7.	www.geeksforgeeks.org
8.	numpy.org
9.	pandas.pydata.org
10.	www.tutorialspoint.com
11.	medium.com
12.	www.statology.org
13.	www.machinelearningplus.com
14.	www.activestate.com
15.	hub.packtpub.com
16.	myanimelist.net


