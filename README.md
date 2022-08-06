Hey! I'm Haris Hasan and here's a select collection of my academic and hobby data science projects.
<br> Check me out on LinkedIn [here](http://www.linkedin.com/in/harishasan001) and reach out at hasan35@purdue.edu!

(Clicking on the headings will take you to the code / presentation)


### Table of Contents:
- [Can we predict NYC taxi cab fares?](https://github.com/harishasan001/data-sci-portfolio#-can-we-predict-nyc-taxi-cab-fares) An End-to-End Machine Learning model in Python
- [Can we use meeting notes to identify the best clients?](https://github.com/harishasan001/data-sci-portfolio#-can-we-use-meeting-notes-to-identify-the-best-clients) Sentiment Analysis using MS Azure and R
- [Can we use COVID-19 survey data to identify good investments?](https://github.com/harishasan001/data-sci-portfolio#-how-can-we-use-covid-19-survey-data-to-identify-good-investments) Data Analysis, Interpretation, and Business Application
- [What can we learn from crypto stock data?](https://github.com/harishasan001/data-sci-portfolio#-what-can-we-learn-from-crypto-stock-data) Exploratory Data Analysis and Data Visualization in Python
- [Psych Research](https://github.com/harishasan001/data-sci-portfolio#-psych-research) Data Manipulation in Python

______


## [🚕 Can we predict NYC taxi cab fares?](https://github.com/harishasan001/data-sci-portfolio/blob/main/NYC%20Taxi%20Fare%20Prediction.ipynb)
#### End-to-End ML model: Data Cleaning, Exploratory Data Analysis, Supervised Linear Regression Model
##### Languages/tools used: Python: Numpy, Pandas, Seaborn, Scikit-learn
I wrote out a fully detailed report of my methods and learnings [here](https://github.com/harishasan001/data-sci-portfolio/blob/main/NYC%20Taxi%20Fare%20Prediction%20Report%20%2B%20Explanation.pdf) where I explain my thoughts alongside the code. It's quite long so here are some screenshots that should serve well as a TL;DR:

***Context***
<p><kbd><img src="NYC Taxi Fare Report intro.PNG" width="487.2" height="280.8"></kbd></p>  

***An example of my reasoning and methods***
<p><kbd><img src="NYC Taxi Fare exploring.PNG" width="487.2" height="280.8"></kbd></p>

***Results***
<p><kbd><img src="NYC Taxi Fare outcome.PNG" width=""600 height="90"></kbd></p>


## [📔 Can we use meeting notes to identify the best clients?](https://github.com/harishasan001/data-sci-portfolio/blob/main/Meeting%20Notes%20Project%20_%20Haris%20Hasan.pdf) 
#### Data Analysis, Sentiment Analysis, Opinion Mining
##### Languages/tools used: MS Azure, Excel, R

The goal was to consider what kind of insights we can get from meeting notes between the business and clients. It was important for us to figure out what kinds of words could suggest high sales potential.

We manually went through 800 comments from meeting notes over about 8 weeks, rating them in 5 different categories

Then, we used Microsoft Azure to consider the sentiment analysis and key phrases, and compare the results with what we found in our manual analysis.

Finally, we used the sales data to determine the correlation between the sales and dimension scores, and found the correlation coefficient for each of the five categories to reach our conclusions.

***An example of some of my analysis***
<p><kbd>
  <img src="Meeting Notes Project 1.PNG"><img src="Meeting Notes Project 2.PNG"><img src="Meeting Notes 3.PNG">
  </kbd></p>


***Results***
<br>
We realized that Account Penetration was perhaps the most important Dimension Score because it demonstrated the greatest Correlation Coefficient

Practically this means that High Penetration phrases such as “Met with Dr, met with doc”, “Met with office manager”, “met with OM”, “Interested”, etc. can lead to greater Total Sales in the past, present and future.

## [😷 How can we use COVID-19 survey data to identify good investments?](https://github.com/harishasan001/data-sci-portfolio/blob/main/COVID-19%20Data%20Investment%20Project%20_%20Haris%20Hasan.pdf)
Justified a novel hypothesis for investment into artificial-intelligence-based hiring technologies with a focus on rehiring opportunities using COVID-19 survey data using Microsoft Azure 
Achieved highest grade standard for analysis work and presentation

## [📉 What can we learn from crypto stock data?](https://github.com/harishasan001/data-sci-portfolio/blob/main/Crypto%20Stock%20Crash%20Exploratory%20Data%20Analysis.ipynb)
#### Exploratory Data Analysis, Data Visualization
##### Languages/tools used: Python: Pandas, Numpy, Matplotlib, Seaborn

Here, I took the live price data of the top ten crypto stocks from Yahoo finance and sought to answer some questions as I explored it. 
- What's the change in the stock's price over time?
- What was the moving average of various stocks?
- What was the daily return average of a stock?
- What was the correlation between daily returns of different stocks?
  -  This one was particularly interesting to me. Here's the heatmap visualization that proved to be quite insightful:
<br><kbd><img src="crypto stock correlation.PNG" width="365" height="416"></kbd></br>
- How much value do we put at risk by investing in a particular stock?
  - This too provided some intriguing insight, which I'll highlight here:
<br><kbd><img src="Crypto stock risk.PNG"></kbd></br>
- Can we attempt to predict future stock behaviour?
  - Here I implemented the Monte Carlo method to predict the stock price of Coinbase. 
<br><kbd><img src="crypto stock prediction.PNG"></kbd></br>
  - However, I am wary of this method as the final result intuitively feels highly improbable. The value of crypto stock often seems to be tied closely with culture which is something very difficult to account for in simulations and predictions. Perhaps accounting for cultural sentiment in stock value predictions is a data science project worth exploring itself?


## [🧠 Psych Research](https://github.com/harishasan001/data-sci-portfolio/blob/main/Psych%20Research%20.ipynb) 

Created a dynamic database framework of 100,000+ data points using Python to enable future analysis tasks
