<a name="readme-top"></a>
<!-- ABOUT THE PROJECT -->
## About The Project

While research i noticed, that the most actual subject of study is comparison machine learning models and neural networks to classic models such as ARMA and ARIMA.  
But most of already existing works are devoted to the comparison of 2-5 models in total.  
So, it doesn't allow forming single point of view without benchmarking different models by myself.  

In total i used 26 models such as autoregressive moving average, linear, decision tree and neural network based regression.  
I determined, that stacked GRU model provide the most accurate result.  
So, i used neural network with two GRU layers to get final model.  

Jupyter Notebook with short version of research is in `jmlc.ipynb`, also there are tickers lists (`tickers.json` and `tickers_test.json`), part of used dataset (`data.parquet.gz`) and already trained neural network (`trained.h5`).

Also, to be repeatable by anyone all code has been refactored and published in <a href="https://github.com/sixxio/ftsf">this repo</a> and <a href="https://pypi.org/project/ftsf/">PyPI</a>, documentation is available <a href="https://sixxio.github.io/ftsf">here</a>.  

And you can try simple forecasting webapp demo by clicking <a href="https://polycast.streamlit.app">here</a> (all code provided in <a href="https://github.com/sixxio/polycast">this repo</a>).  


### Built With
To prepare data were used such libraries as Pandas and NumPy.  
To test different model were used libraries such as Statsmodels, Sklearn and Keras.  
![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white)
![Keras](https://img.shields.io/badge/Keras-%23D00000.svg?style=for-the-badge&logo=Keras&logoColor=white)
![Plotly](https://img.shields.io/badge/Plotly-%233F4F75.svg?style=for-the-badge&logo=plotly&logoColor=white)

<!-- CONTACT -->
## Contact

Nikita Safonov - [@sixxio](https://t.me/sixxio) - [nickit.safonov@yandex.ru](mailto:nickit.safonov@yandex.ru) 

Project Link: [nasdaq-forecasting](https://github.com/sixxio/nasdaq-forecasting)

