<img src="https://bit.ly/2VnXWr2" alt="Ironhack Logo" width="100"/>

# The Business Benefits of Process Improvements & Implementation of Recommender Systems
*Elliott Coyne*

*Data Analytics, Barcelona, December 2019*

## Content
- [Project Description](#project-description)
- [Hypotheses / Questions](#hypotheses-questions)
- [Dataset](#dataset)
- [Cleaning](#cleaning)
- [Analysis](#analysis)
- [Model Training and Evaluation](#model-training-and-evaluation)
- [Conclusion](#conclusion)
- [Future Work](#future-work)
- [Workflow](#workflow)
- [Organization](#organization)
- [Links](#links)

## Project Description
The purpose of this task is to emulate the work of a business consultant who has been engaged by an online retailer to identify opportunities for improvement within their business. Strategies to be explored include the implementation of a recommender system to increase sales for both regular and business customers (based on their  purchasing habits) as well as an analysis of customer returns and the potential impact on cash flow and employee workload.

## Questions
Given the retailer is only able to provide transactional data (and not details of all customers or a current inventory master file), much time will be taken to analyse and clean the data in order to derive meaningful insights. Once the data is cleaned and the necessary assumptions made, the following questions will need to answered:
* How much can be learned about a business simply by analysing it's transaction data?
* What is the potentail increase in revenue that could be enjoyed if a recommender system were to be implemented?
* What is the rate of returned products? Does this identify stock that should be discontinued? What are the possible implications for employee workflow, when considering the processing of returned items.

## Dataset
* This project is a simulation of a Business Analysis Consultation for a ficticious online retailer. The raw dataset used was sourced from XXX. The link to the raw dataset can be found in the links sections below.


* Where did you get your data? If you downloaded a dataset (either public or private), describe where you downloaded it and include the command to load the dataset.
* Did you build your own datset? If so, did you use an API or a web scraper? PRovide the relevant scripts in your repo.
* For all types of datasets, provide a description of the size, complexity, and data types included in your dataset, as well as a schema of the tables if necessary.
* If the question cannot be answered with the available data, why not? What data would you need to answer it better?

## Cleaning
Describe your full process of data wrangling and cleaning. Document why you chose to fill missing values, extract outliers, or create the variables you did as well as your reasoning behind the process.

## Analysis



* Overview the general steps you went through to analyze your data in order to test your hypothesis.
* Document each step of your data exploration and analysis.
* Include charts to demonstrate the effect of your work.
* If you used Machine Learning in your final project, describe your feature selection process.

## Model Training and Evaluation
* Recommender Systems are on the use of customer clustering and the investigation of distances between customers. There are multiple metrics that can be used to calculate the aforementioned distances (i.e. 'cityblock', 'correlation', 'cosine', 'dice', 'euclidean', 'hamming' and 'jaccard'). During the build of the recommender system different metrics will be used and their output assessed to determine which would be the most suitable to implement.

## Conclusion
* Working with transactional data alone proved to be a challenge, however the additional cleaning and exploratory data analysis resulted in a more intiment knowledge of the retailer.
* In order to assess the strength/ validity of the recommendations, a furtheer analysis will need to be carried out following their implemention.




* Summarize your results. What do they mean?
* What can you say about your hypotheses?
* Interpret your findings in terms of the questions you try to answer.

## Future Work
The assumption would be that the retailer would adopt the recommendations made within this project. Therefore it would be prudent to collect further transaction data in order to assess the success or failure of the recommentations. In addition to the quantitative data collected from transaction lots, it would also be useful to collect qualitative data from employess both pre and post implementation of the recommendations.

## Workflow
Following the selection of the topic probelm and questions, suitable data was sourced. This data was then downloaded and loaded into dataframes, cleaned and analysed. The cleaning process was carried out simultaneously to Exploratory Data Analysis (EDA); cleaning and removing outliers whilst reviewing the data appeared to be the most efficient use of time.

## Organization
In order to organise the project, a kanban board from Trello was used. The link to the Trello board can be found below.

The respository root folder has one main working directory, 'your-project' which is divded into three sub-folders. This Readme file resides in the root directory. Below is an explanation of each sub folder and their respective contents:
* Charts(Tableau) - The downloaded Tableau Public files are stored locally for review and comment.
* Code - The Jupyter Notebook files used to obtain, clean and analyse the data.
* Data - Both the raw XLSX file (downloaded) and CSV files (generated during investigation) used for this project.
* Organisation - Includes spreadhseet to determine the differernt dataframes required (which result from cleaning).

## Links
Please find all relevant links for this project below:
[Repository](https://github.com/tristar82/Project-Week-8-Final-Project)
[Slides](xxxxxx)
[Trello](xxxxxx)
[Tableau Public](xxxxxx)
[Medium Article](xxxxxx)
**Data Source**
[UCI****] Dataset downloaded from (http://archive.ics.uci.edu/ml/machine-learning-databases/00352/)
**Libraries Required to Run Code**
[Plotly](https://plot.ly/python/v3/ipython-notebooks/cufflinks/)

