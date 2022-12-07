# Automated web-scraping and prediction of real estate property price
A Selenium-coded crawler that scrapes real estate ads from www.superimmo.com, a real estate website in France, to analyze the features of home properties and predict the next property price per sqm in different districts of Ile-de-France region. 

## Description
The project intends to show how ethical web-scraping data from a live website can help real estate investors to stay on top of market changes and evolution. Moreover, the data scraped is fit continuously to a machine learning model that predicts the adjusted price of a real estate property based on its continuous learning from web-scraped data. The next milestone of this project is to package all the benefits that this code present (in addition to extended code) into a software-as-a-service solution intended to offer a one-stop shop for real estate investors to be in control of their business decisions in real-time.

## Getting Started

### Prerequisites

* Selenium 4.0
<br> The recommended method to install Selenium 4.0 is the following:
<pre>pip install selenium</pre>
For other install options, please refer to <a href="https://www.selenium.dev/documentation/webdriver/getting_started/install_library/" rel="nofollow">Install a Selenium library</a>

* XGBoost
<br> The recommended method to install XGBoost is the following:
<pre>pip install xgboost</pre>
For other install options, please refer to <a href="https://xgboost.readthedocs.io/en/stable/install.html" rel="nofollow">Installation Guide</a>

* Other Python libraries
<br> Other libraries used in this project are usually installed by default in a Jupyter notebook, but if it is not the case, here are the libraries you need to install: <a href="https://pandas.pydata.org/docs/getting_started/install.html" rel="nofollow">pandas</a>, <a href="https://numpy.org/install/" rel="nofollow">numpy</a>, <a href="https://www.folkstalk.com/2022/10/install-re-package-python-with-code-examples.html" rel="nofollow">regex</a>, <a href="https://www.tutorialspoint.com/how-to-install-matplotlib-in-python" rel="nofollow">matplotlib</a>, <a href="https://seaborn.pydata.org/installing.html" rel="nofollow">seaborn</a>, and <a href="https://scikit-learn.org/stable/install.html" rel="nofollow">sci-kit learn</a>

### Usage

After installing the libraries, all you need to do is to run the script. The dataset is within the code since you will be scraping it from the website. You need to know that the code is set to scrape 500 pages by default; but you can change this by changing the range limit in the following code:
<pre>for n in range(1,500):</pre>
Note that the bigger the limit you choose, the more time the crawler will take to run the script.

## Help

* Keep your computer always connected to the internet while you run the script
* Note that the crawler code is exclusive to the website chosen in this project

## Authors

Assaad Ghanem  
assaad_ghanem@hotmail.com
