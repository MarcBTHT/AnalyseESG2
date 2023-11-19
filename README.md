# Automatic portfolio management including sentiment analysis and Machine Learning

## Disclaimer/Attention

This is a school project. We do not recommend the use of the information output by the algorithm as a financial advice.  

## Project description

![image](https://github.com/MarcBTHT/AnalyseESG2/assets/116173196/2f4c84ba-0eb7-4b75-9e83-f64a79691956)


- We assigned ESG scores to each of the CAC40 companies and selected the top x performers. 
- For the selected companies, we conducted a monthly Twitter sentiment analysis, utilizing Natural Language Processing (NLP) on tweets related to each company. 
- Additionally, we calculated scores based on their half-yearly reports. 
- Leveraging machine learning and these scores, we allocated weights to each company within its respective industry sector.
- In parallel, we conducted return forecasts using time series analysis (ARIMA model) and employed Markowitz methodology to determine sector weights. 
- Finally, we multiplied the two sets of weights to construct our monthly portfolio.

## Prerequisites

1. Python 3.9 (pandas does not yet support python 3.10) : [link](https://www.python.org/downloads/release/python-397/)

2. Python packages :
    * numpy
    * pandas
    * [PyQt5](https://pypi.org/project/PyQt5/) : only for IDEs unable to display matplotlib graphics (VSCode)
    * matplotlib
    * [DateTime](https://pypi.org/project/DateTime/)
    * requests
    * wheel
    * [lxml](https://pypi.org/project/lxml/)
    * [yfinance](https://pypi.org/project/yfinance/)
    * [tweepy](https://pypi.org/project/tweepy/)

You can also use the windows command prompt and pip, for example `pip3 install -r requirements.txt`
