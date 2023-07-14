# EDA-on-Data-Science-Job-Posting-on-Glassdoor
![image](https://github.com/Lalitha-PS-5/EDA-on-Data-Science-Job-Posting-on-Glassdoor/assets/113533079/3117620e-acaa-44c1-8247-467b5e59979e)
![image](https://github.com/Lalitha-PS-5/EDA-on-Data-Science-Job-Posting-on-Glassdoor/assets/113533079/65950885-f2c3-48bb-a409-9f5f04716f5f)
![image](https://github.com/Lalitha-PS-5/EDA-on-Data-Science-Job-Posting-on-Glassdoor/assets/113533079/f78f558c-1445-4717-b18d-30d3fe41aa46)
![image](https://github.com/Lalitha-PS-5/EDA-on-Data-Science-Job-Posting-on-Glassdoor/assets/113533079/1a789a58-175a-4a5a-8c7b-c3fc1f1a5491)
![image](https://github.com/Lalitha-PS-5/EDA-on-Data-Science-Job-Posting-on-Glassdoor/assets/113533079/ee4b09a6-e9f8-498a-9117-23856199f8b4)
![image](https://github.com/Lalitha-PS-5/EDA-on-Data-Science-Job-Posting-on-Glassdoor/assets/113533079/aa24d68d-a1f1-4c48-8577-8cd4e8b0466d)
![image](https://github.com/Lalitha-PS-5/EDA-on-Data-Science-Job-Posting-on-Glassdoor/assets/113533079/8f5a0d55-2632-4380-9fe0-bd1998377d86)

We'll use the Glassdoor survey dataset for our Datascience jobs data analysis. This is an annual survey extracted from Glassdoor. Downloaded the CSV manually and uploaded it via Jupyter's GUI. The file size is 3.14MB with 1000 rows and 14 columns.

![image](https://github.com/Lalitha-PS-5/EDA-on-Data-Science-Job-Posting-on-Glassdoor/assets/113533079/2211b9c0-d8ca-4442-b868-c9b8284c7f56)
![image](https://github.com/Lalitha-PS-5/EDA-on-Data-Science-Job-Posting-on-Glassdoor/assets/113533079/827ab9df-1590-4a57-910f-a5c7b63d5f86)

The dataset contains over 1000 responses to 14 questions (although many questions are optional). The responses have been anonymized and there's no personally identifiable information available to us - although each respondent has been assigned a randomized respondent ID.

Let's view the list of columns in the data frame.
![image](https://github.com/Lalitha-PS-5/EDA-on-Data-Science-Job-Posting-on-Glassdoor/assets/113533079/55577c71-1579-447b-8390-c744fb5feb70)

We can view some basic information about the data frame using the .info method

![image](https://github.com/Lalitha-PS-5/EDA-on-Data-Science-Job-Posting-on-Glassdoor/assets/113533079/1d3be8bd-ae1f-40fa-9fcf-0ede07e50cb2)

It appears that each column contains values of a specific data type. For the numeric columns, you can view the some statistical information like mean, standard deviation, minimum/maximum values and number of non-empty values using the .describe method.

![image](https://github.com/Lalitha-PS-5/EDA-on-Data-Science-Job-Posting-on-Glassdoor/assets/113533079/a5bc5fac-c7ba-4878-a260-3f791316e275)


# Exploratory Analysis and Visualization
Before we can ask interesting questions about the survey responses, it would help to understand what the demographics i.e. salary estimate, revenue and size of the company, employment level , ratings etc. of the respondents look like.

It's important to explore these variable in order to understand how representative the survey is of the worldwide programming community, as a survey of this scale generally tends to have some selection bias.

Let's begin by installing and importing matplotlib.pyplot and seaborn.
# Q. Identify the highest number of salaries that a Data Scientists or Data Analysts

![image](https://github.com/Lalitha-PS-5/EDA-on-Data-Science-Job-Posting-on-Glassdoor/assets/113533079/2c825a6d-a4c0-47d6-b924-8c5cf4ac4bdc)

It can be observed that the the top salaries ranges are between One Lakh to One Lakh fourty five thousand.
# Q. Identify the ratings associated with the Data science Job

![image](https://github.com/Lalitha-PS-5/EDA-on-Data-Science-Job-Posting-on-Glassdoor/assets/113533079/e32392ca-2bee-4b46-b61a-dc4c40aaa21c)

# Q: Find out the density of the company names v/s ratings to visualize the top ratings and the companies.

![image](https://github.com/Lalitha-PS-5/EDA-on-Data-Science-Job-Posting-on-Glassdoor/assets/113533079/8ebb1acb-aea8-4169-aab7-5978be409af9)
Hence the density of company ratings corresponding to its name could be seen above.

The above visualization shows that most of the companies has integrated Data Scientists / Data Analytics post in the past recent years from 2000 and the domain has already boomed introducing many Data Science aspirants :)

# Q: Which company has been founded in recent years with the ratings.

![image](https://github.com/Lalitha-PS-5/EDA-on-Data-Science-Job-Posting-on-Glassdoor/assets/113533079/e3405c39-48eb-407f-9183-12be31a4ca03)

It can be observed that the data science job slowly started booming from 1950 and major hipe in data science jobs is mostly obserbed in the year 2000.

### More questions and inferences could be found in ipynb file. Please refer that file for complete step by step details with Code.

# Inferences and Conclusions
I had drawn many interesting inferences from the survey, here's a summary of the few of them:

Based on the demographics of the survey respondents, we can infer that the survey is somewhat representative of the overall Data Scientists programming community.

The programming community is not as diverse as it can be, and although things are improving, we should take more efforts to support & encourage members of underrepresented communities - whether it is in terms of age, country, race, gender or otherwise.

Python and SQL are the most used programming languages for Data Analytics and Data Scientists. SQL is extensively used for text mininig.

Python is the language most people are interested in learning - since it is an easy-to-learn general purpose programming language well suited for a variety of domains.

It can be observed that the data science job slowly started booming from 1950 and major hipe in data science jobs is mostly obserbed in the year 2000.

You can learn and start Data Scientists course professionally at any age, and you're likely to have a long and fulfilling career if you also enjoy programming as a hobby.

# References and Future Work
There's a wealth of information to be discovered using the survey, and I've barely scratched the surface. Here are some ideas for further exploration:

Perform text mining and could extract intersting insights about the reviews in Job Description column

Choose a different set of columns (I chose on 11 out of 14) to analyze other facts of the data

Prepare an analysis focusing on diversity - and identify areas where underrepresented communities are at par with the majority (e.g. education) and where they aren't (e.g. salaries)

Compare the results of this year's survey with the previous years and identify interesting trends References:

Text mining: https://medium.com/@datanizing/modern-text-mining-with-python-part-2-of-5-data-exploration-with-pandas-ee3456cf6a4

Pandas user guide: https://pandas.pydata.org/docs/user_guide/index.html

Matplotlib user guide: https://matplotlib.org/3.3.1/users/index.html

Seaborn user guide & tutorial: https://seaborn.pydata.org/tutorial.html

UCI repository: https://github.com/JovianML/UCIdata
