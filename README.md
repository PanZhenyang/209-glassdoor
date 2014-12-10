# Data Science Final Project: Glassdoor Insight #

### Author

* Wenshuai Ye \<wenshuaiye@g.harvard.edu\>
* Yaxiong Cai \<yaxiongcai@g.harvard.edu\>
* Zhenyang Pan 
* Yuhao Zhu \<yuhaozhu@g.harvard.edu\>
* Ye Kuang \<yekuang@g.harvard.edu\>

![](Facebook.jpg)

As graduate students at Harvard University interested in launching start-ups in the future, we would like to know how people view their employers from different aspects and what are people's views of different features of a company (benefit, culture, balance, management, opportunity, size, etc) influence their view on the company as a whole. We perform the analysis on various levels, including stratifying the analysis by industries and states.

## Structure
Our project consists both IPython Notebook Sourcecode and Data Assest.

- `Final Project Delivery.ipynb`: Integrated sourcecode, including data scraping from Glassdoor, data wrangling, analysis and visualization and text mining. For each part of our work, we also included a reasonable analysis on the result.
- `\*Data` folders: Folders that contains raw data to be wrangled before analysis.
- `gd_cleaned_data_1129_sample2_industry.csv`: Data that has been processed, including each companies name, geometric location, which main and sub industry it belongs, five subjective rating scores from employers' perspective and an overall rating score.

## Prerequisites
Our project is done using Anaconda IPython Notebook. To get started, you may want to install it first.

Most of the modules we are using have already been included in IPython Notebook. However, in order to display the statistics distriution over USA, you will need to install `vincent` module first.