## Outline

This lesson provides an introduction to the data science process and challenges generally faced by data scientists at different stages of this process. Students will be introduced to different roles within data science domain with a focus on similarities and differences within these roles. This would allow students to better position themselves for a role that suits their skills and aspirations. Following this introduction, the lesson provides a quick overview of tools and technologies currently being employed for data scientists for data collection, exploration and analysis. Python would be identified as a tool of choice and students will be provided a strong rationale in support of using Python for compkete data science process. 

The second half of taught component will introduce students to key data types generally used for collection and processing data within python, followed by coding exercises to pratice these datatypes for simple examples. 

##  Learning Objectives

* Introduction to Data Science Process 
* Data Science Roles
* Data Science Tools and Technologies
* Introduction to Python Programming Language 
* Python data types


## The Data Science Process 15 minutes

A common question asked by most aspiring data scientists is "How to do data science ?" or "How do I get started with data science skills". Following steps describe different stages of the data science process as shown by Sudeep Agarwal [Understanding Data Science Life Cycle](http://sudeep.co/data-science/Understanding-the-Data-Science-Lifecycle)

<img src="chart.png" width = "500"/>

#### Business Understanding / Domain Knowledge

Before trying to solve a data related problem, it is imperative that a data scientist/analyst carries a clear understanding of the problem domain. Following 5 types of analytical questions are generally asked at this stage as stated in [Microsoft Azure blog]
(https://docs.microsoft.com/en-us/azure/machine-learning/team-data-science-process/lifecycle-business-understanding) 

* **How much or how many?** 
e.g. Identifying number of new customers likely to join your company in next quarter. (Regression analysis)

* **Which category?**
e.g. Assignging a document to a given category for a document management system.  (Classification analysis)

* **Which group?**
e.g. Creating a number of a groups (segments) of your customers based on their monetary value. (Clustering)

* **Is this weird? (anomaly detection)**
e.g. Detecting suspicious activities of a customers by a credit card company to identify potential fraud. (Anomaly detection)

* **Which option should be taken?**
e.g. Recommending new products (e.g. movies/books/music by Amazon) to exisating customers (Recommendation systems)
> Exercise: Think of at at least one such analytical question. Determine which of above category does your question belong to and how answering it correvtly may help achieves your analysis goal.

#### Data Collection

After asking the analytical question and identifying objectives for your analysis, the next stage of analysis is to identify and gather the required data. Data mining is a process of identifying and collecting data of interest from different sources e.g. databases, text files, Internet and also printed documents etc. Some of the questions that you may ask yourself at this stage are:

* What data items do I need in order to answer my analystical question ?
* Where can I find this data ?
* How can I obtain the data from data source ?
* How do I sample from this data ?
* are their any privacy/ legal issues that I must consider prior to data usage ?





Now that you’ve defined the objectives of your project, it’s time to start gathering the data. Data mining is the process of gathering your data from different sources. Some people tend to group data retrieval and cleaning together, but each of these processes is such a substantial step that I’ve decided to break them apart. At this stage, some of the questions worth considering are - what data do I need for my project? Where does it live? How can I obtain it? What is the most efficient way to store and access all of it?

If all the data necessary for the project is packaged and handed to you, you’ve won the lottery. More often than not, finding the right data takes both time and effort. If the data lives in databases, your job is relatively simple - you can query the relevant data using SQL queries, or manipulate it using a dataframe tool like Pandas. However, if your data doesn’t actually exist in a dataset, you’ll need to scrape it. Beautiful Soup is a popular library used to scrape web pages for data. If you’re working with a mobile app and want to track user engagement and interactions, there are countless tools that can be integrated within the app so that you can start getting valuable data from customers. Google Analytics, for example, allows you to define custom events within the app which can help you understand how your users behave and collect the corresponding data.















