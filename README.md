## Time Series Forecasting And Analysis Of Store Sales Of Corporation Favorita Products-Regression Findings

[![View My Profile](https://img.shields.io/badge/View-My_Profile-green?logo=GitHub)](https://github.com/justinjabo250)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-%230077B5?logo=linkedin&logoColor=orange)](https://www.linkedin.com/in/jabo-justin-2815341a2/) 
[![View Repositories](https://img.shields.io/badge/View-My_Repositories-blue?logo=GitHub)](https://github.com/justinjabo250?tab=repositories)
[![View My Profile](https://img.shields.io/badge/MEDIUM-Article-purple?logo=Medium)](https://medium.com/@jabojustin250)
[![Website](https://img.shields.io/badge/My-Website-darkgreen)](https://github.com/justinjabo250?tab=repositories)
[![Articles](https://img.shields.io/badge/My-Portfolio-darkblue?logo=Website)](https://justinjabo250.github.io/Developing-a-web-application-for-an-online-portfolio./)
[![View GitHub Profile](https://img.shields.io/badge/GitHub-Profile-purple)](https://github.com/justinjabo250)


<img src="https://user-images.githubusercontent.com/115732734/271711902-8993af83-86cd-46b7-bb84-866f205b4468.jpeg" width="550">

## Time Series Forecasting And Analysis Of Store Sales Of Corporation Favorita Products-Regression Findings

### Description: 

This study aims to evaluate and anticipate the sales of a specific store using time series data from Corporation Favorita, a prominent supermarket retailer with headquarters in Ecuador.

The objective is to create a model that can precisely forecast future sales utilizing the hundreds of products sold at various Favorita locations in order to assist the management of the store in developing inventory and sales plans.

We will use sales forecasting to determine future sales levels for a corporation using past sales data since Favorita Corporation's sales over the previous four years have generated a lot of data. By using this information, which has been kept on file for a certain period of time after the event or after it occurred, we want to help company managers make predictions about the future.

As part of this research, we will formulate scientific hypotheses based on time-stamped historical data, use those hypotheses to construct models through historical analysis, use those models to generate observations, and utilize those observations to inform future strategic decision-making. To improve operations and ultimately revenue, we would like to help management at Favorita Corporation get some insights from their data.

## Project Goals

This project involves time series forecasting. Using information from Corporation Favorita, a big grocery chain with headquarters in Ecuador, we will forecast store sales. Six csv files (train, test, store, oil, holidays_events, transactions) are sent to us; they contain information about goods, stores, specials, sales, oil prices, holidays and more.


<img src="https://user-images.githubusercontent.com/115732734/271712315-71f5165a-3133-422f-8ba3-8cf0039b9029.jpeg" width="550">


# Methodology:

According to IBM, CRISP-DM, which stands for Cross-Industry Standard Process for Data Mining, is an industry-proven way to guide your data mining efforts.

•	It offers explanations of the common project phases, the tasks related to each phase, and the relationships between these tasks as a methodology.
•	As a process model, CRISP-DM provides a summary of the life cycle of data mining.


# The CRISP-DMThe six stages of the data mining lifecycle are as follows:

1. Business Understanding
2. Data Understanding
3. Data Preparation
4. Modeling
5. Evaluation
6. Deployment


# Business Understanding:

The goal of this project is to increase sales by learning more about long-term sales trends. understand prior events, how they affected sales, what can be done to remedy them, and, if necessary, the next step. This research attempts to examine several regression approaches in order to produce some predictions.


Hypothesis: The sales of the store are affected by various factors, such as the day of the week, season, promotions, and other external factors. By analyzing these factors and building a time series forecasting model, we can accurately predict the store's future sales.

Null Hypothesis: Some products have sold more than others in terms of revenue.

Alternative Hypothesis: The retail company received an equal amount of revenue from each product.

![data-analyticsss](https://user-images.githubusercontent.com/115732734/236700882-3bec3829-7039-4000-9d74-b15611877723.jpeg)

# Research Questions:

1. Is the train dataset complete (has all the required dates)?
2. Which dates have the lowest and highest sales for each year?
3. Did the earthquake impact sales?
4. Are certain groups of stores selling more products? (Cluster, city, state, type)
5. Are sales affected by promotions, oil prices and holidays?
6. What analysis can we get from the date and its extractable features?
7. What is the RMSLE, RMSE, MSLE, MSE from the ML model?


# 📁 Dataset

Public dataset can be found [`here`](https://rb.gy/xmxeqc)

# 🚀 Setup

Install the required packages to be able to run the evaluation locally.

You need to have [`Python3`](https://www.python.org/) on your system. Then you can clone this repo and being at the repo's root (`root :: repo_name> ...`) follow the steps below:

- Windows:

```python
python -m venv venv; venv\Scripts\activate; python -m pip install -q --upgrade pip; python -m pip install -qr requirements.txt
```

- Linux & MacOs:

```python
python3 -m venv venv; source venv/bin/activate; python -m pip install -q --upgrade pip; python -m pip install -qr requirements.txt
```

The both long command-lines have a same structure, they pipe multiple commands using the symbol **;** but you may manually execute them one after another.

1. **Create the Python's virtual environment** that isolates the required libraries of the project to avoid conflicts;
2. **Activate the Python's virtual environment** so that the Python kernel & libraries will be those of the isolated environment;
3. **Upgrade Pip, the installed libraries/packages manager** to have the up-to-date version that will work correctly;
4. **Install the required libraries/packages** listed in the `requirements.txt` file so that it will be allow to import them into the python's scripts and notebooks without any issue.

**NB:** For MacOs users, please install `Xcode` if you have an issue.

## ✨ Contribution

Contributions, issues, and feature requests are welcome!

To contribute to this project, see the GitHub documentation on **[creating a pull request](https://help.github.com/en/github/collaborating-with-issues-and-pull-requests/creating-a-pull-request)**.

## 👏 Support

Give a ⭐️ if you like this project!

---

<p>&copy; 2023 Justin Jabo</p>
