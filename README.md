
# Problem statement
When shopping for a new laptop a consumer may look for certain specifications and features on a budget. College students, who generally are financially unstable, have a limited budget to afford high-end laptops. There are several factors influencing the price of the laptop. Usually high specifications and more features mean more money. The purpose of this project is to identify the most significant factors of laptop which drives the laptop prices by developing a regression model to forecast the prices of laptops. Using our regression model and analysis, one may be able to identify the correct price of the laptop instead of performing a competitive analysis. For a consumer who lacks knowledge about laptops may find our model to be useful. Especially our model may be helpful to consumers with a limited budget, such as students, since they may be able to predict the price of the laptop given the features and specifications that they want.

# Description
This Model/WebApp predicts laptop price. Many times we have come across websites like "amazon.com", "flipkart.com" where they sell the laptops in many part of the country, so this model is also inspired by the concept of predicting laptop prices based on the Company, Screen Size, RAM, Memory etc. Firstly I built the model using sklearn and machine learning algorithm using laptop prices dataset. Second step was to write a python code using Streamlit that uses the saved model to serve http requests. Third component was to deploy the model on heroku that allows user to enter Company, Screen Size, RAM, Memory etc and it will call the model to retrieve the predicted price. During model building I came across all data science concepts such as data load and cleaning, outlier detection and removal, feature engineering etc.

## Data:
- The train and test data will consist of various features that describe that laptop's configuration
- Each row contains fixed size object of features. There are 11 features and each feature can be accessed by its name.

### Features:
1. Company – describes the company name
2. Type – whether it is Notebook, Ultrabook or anything else
3. Ram – RAM size in GB
4. Weight – Weight of the laptop in kg
5. Touchscreen – if it has touchscreen or not
6. IPS – if it has IPS display or not
7. Scren Size – Size of screen of laptop in inches
8. Screen Resolution – Screen Resolution of the laptop
9. CPU - Processor type for the laptop
10. HDD - Hard Disk capacity in GB
11. SSD - SSD memory in GB
12. GPU - GPU Brand
13. OS - Operating system of the laptop

## Technologies used

1.  Python
2.  Numpy and Pandas for data cleaning
3.  Matplotlib and Seaborn for data visualization
4.  Sklearn for model building
5.  Jupyter notebook, visual studio code as IDE
6.  Streamlit for Deployment
## Deployment


Web App Link(Heroku) -  [Visit here](https://www.house-price-demo.herokuapp.com/)


## Screenshot

### Web App

<img src="https://snz04pap001files.storage.live.com/y4m9mh7b9SXalcZtO7GCKVbl6FiLW6TDATusjPKJQW11lHO-ePv6fq_iqbQYOjSoaXWK_k3DQqsssX7EV0j7y10KDghCKAFZWCiLEOoeBnHKLZzoPCA87JvdGnnSKVO2xpjekyE9KYMcJhNGYmH-cmHpkaJZw_6thGfwkhON3U0Pwc8kgXd8E-QK-51lhMwX8Kh?width=983&height=634&cropmode=none" width="983" height="634" />

<br>
<br>
<br>
<img src="https://snz04pap001files.storage.live.com/y4m8nDq607QvmNkRuL9Q6Rqn4U3-sGEjH8-JenevtJX1sMXSfoqYYvaW4Kxxb25A8Usr0sATG4kAzQwRxTItdEnei000QFspPTGHXnaLUwyM3e6mXJmMTbwDrnc8WgYMDwZJvG_73uijd7N6qj5ux9nKMa4COLmoFxGJOcBBv_X-Qs64br428v4g7nH4InW3JO6?width=870&height=640&cropmode=none" width="870" height="640" />

### Code Snippet

<img src="https://snz04pap001files.storage.live.com/y4m_oin3lxMKlzQ-FkRpCZ5EiXGeIyTqZxqMwCzuTPx-0GGLIXJk9VLymYaUaDT7exEukkmVUAPj6nIYNB4RuDjV8QdPIXF6RzbKppLjk93uNDhcvas3JLAylQtiHab-mu4E26XoeMIGZtQYlYvg3Ow_tMTTjpJk13w6nTt4ejrg9gxiXCoixSlxQEfxn0DBKX2?width=731&height=642&cropmode=none" width="731" height="642" />

<br>
<br>
<br>

<img src="https://snz04pap001files.storage.live.com/y4mbVmZQyoM3XbG0nzDQoNp6pSzgjFtX3pkbxsubAbH52ITuPn--3pZWWOf1kBDKBJ6HyoihSmAXWrex1qIt3oNQi60TO0SAug9ebzPKYmVTY-rw8XklFeG-coNe3WRvH_CPBBE2XACWRCJZhXLva1ZS3nhz8dXQ7lTIUNiJCTqivLu_x923ABEuz6x1Yg46BaF?width=559&height=396&cropmode=none" width="559" height="396" />

## Connect with me <img src='https://raw.githubusercontent.com/ShahriarShafin/ShahriarShafin/main/Assets/handshake.gif' width="100px">



<a href = 'https://www.linkedin.com/in/deepak-porwal04'> <img width = '32px' align= 'center' src="https://raw.githubusercontent.com/rahulbanerjee26/githubAboutMeGenerator/main/icons/linked-in-alt.svg"/></a>&emsp;&emsp;<a href = 'https://deepak-porwal.herokuapp.com/'> <img width = '32px' align= 'center' src="https://raw.githubusercontent.com/rahulbanerjee26/githubAboutMeGenerator/main/icons/portfolio.png"/></a>&emsp;&emsp;<a href = 'https://www.github.com/deepak-porwal04'> <img width = '32px' align= 'center' src="https://raw.githubusercontent.com/rahulbanerjee26/githubAboutMeGenerator/main/icons/github.svg"/></a>

