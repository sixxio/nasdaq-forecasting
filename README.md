# nasdaq-forecasting
![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white)
![Keras](https://img.shields.io/badge/Keras-%23D00000.svg?style=for-the-badge&logo=Keras&logoColor=white)
![Plotly](https://img.shields.io/badge/Plotly-%233F4F75.svg?style=for-the-badge&logo=plotly&logoColor=white)
![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)

Данный проект посвящен прогнозированию стоимости акций, представленных на бирже NASDAQ.
В ходе анализа научных работ в предметной области было определено, что наиболее актуальным вопросом является использование моделей машинного обучения для получения наиболее точных результатов.
В ходе бенчмарка были проверены 26 моделей: 2 модели авторегрессии - скользящего среднего, 8 моделей машинного обучения и 16 моделей на основе нейронных сетей.
Было определено, что наиболее точным является прогноз модели на основе нейронной сети с двумя слоями из GRU ячеек.
Модель на основе данной топологии была обучена и запущена в прод.
