Module 11 Challenge

This project runs a time series data analysis on MercadoLibre google search traffic and sees if the results correlate with increases in stock prices.
Data is grouped by day of week, week of year, ect. to find seasonal or repeating patterns and then visualized through several different plots to help present the results as a whole.

---



## Technologies



This project uses Python 3.9.7, Google Colab, and the following libraries - 


| Library | Version | Documentation
|----|----|---|
| pandas |1.4.2| [pandas docs](https://pandas.pydata.org/docs)
| hvplot |0.8.0| [hvplot docs](https://hvplot.holoviz.org/)
| scikit-learn |1.1.1| [scikit-learn docs](https://scikit-learn.org/stable/)
| prophet| 1.1| [prophet docs](https://facebook.github.io/prophet/docs/quick_start.html)
| pystan | 3.5.0 | [pystan docs](https://pystan.readthedocs.io/en/latest/)

---



## Installation Guide




To run this program, upload the .ipynb file in [Google Colab](https://colab.research.google.com/)



---



## Usage


Several plots were used to help visualize the data results.



|<p align="center">Search Trends May 2020</p>|<p align="center">Traffic by the Hour</p>|
|---|---|
|<p align="center"><img src="images/search_trends.JPG" width=500/></p>|<p align="center"><img src="images/search_trends_heatmap.JPG" width=500/>
|<p align="center">**Day of Week Traffic**</p>|<p align="center">**Week of Year Traffic**</p>|
|<p align="center"><img src="images/search_trends_dayofweek.JPG" width=500/>|<p align="center"><img src="images/search_trends_weekofyear.JPG" width=500/>|
|<p align="center">**Prophet Forecast Results**</p>|<p align="center">**Prophet Forecast Results**</p>|
|<p align="center"><img src="images/search_prophet_1.JPG" width=500/>|<p align="center"><img src="images/search_prophet_2.JPG" width=500/>|
---



## Contributors

Dan McQueen

dandmcqueen@gmail.com

[Linkedin](https://www.linkedin.com/in/dan-mcqueen-4a5980238/)

---



## License

[GNU v3.0](LICENSE)
