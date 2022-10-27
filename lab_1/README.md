# Лабораторная работа №1

В данной ЛР мне было необходимо реализовать алгоритмы KNN, Naive Bayes, логистической и линейной регрессии, SVM.

В качестве датасета я использовал обработанный датасет из ЛР №0.

Алгоритмы показали следующие результаты:

### KNN

![image](https://user-images.githubusercontent.com/71846372/198397114-07a98c95-1bc6-4efb-9d15-6f1b5e39f52c.png)

![image](https://user-images.githubusercontent.com/71846372/198397165-2b8bd381-1238-4a1d-8029-e74cc588324e.png)

Accuracy train: 0.7176499556781247

Accuracy tests: 0.6815642458100558

Precision tests: 0.5384615384615384

Recall tests: 0.5645161290322581

### NB

![image](https://user-images.githubusercontent.com/71846372/198397373-f442c374-7084-43df-93ca-761a7263ed5a.png)

![image](https://user-images.githubusercontent.com/71846372/198397384-0e1b7fb8-3515-46d1-9c09-9752422a4098.png)

Accuracy train: 0.7022160937653895

Accuracy tests: 0.7318435754189944

Precision tests: 0.5945945945945946

Recall tests: 0.7096774193548387


### Regression

![image](https://user-images.githubusercontent.com/71846372/198397589-689d4ccf-0274-4faa-8c67-107b9b962dce.png)

![image](https://user-images.githubusercontent.com/71846372/198397606-2eb51bf9-8073-495e-bb8d-cd172103df1b.png)

Accuracy train: 0.6783315276273023

Accuracy tests: 0.776536312849162

Precision tests: 0.7037037037037037

Recall tests: 0.6129032258064516

### SVM

![image](https://user-images.githubusercontent.com/71846372/198397700-d78b9a04-3c57-4130-bca8-17b81e3c6ac7.png)

![image](https://user-images.githubusercontent.com/71846372/198397730-c4d3d88a-fa3a-4bb9-9c12-d87fb51e495a.png)

Accuracy train: 0.7134147542598246

Accuracy tests: 0.7932960893854749

Precision tests: 0.6865671641791045

Recall tests: 0.7419354838709677


### Выводы

Как видно, наилучшие результаты показывает регрессия. Я думаю, что это связано, с тем, что она лучше всего подходит для решаемой задачи - разделению двух классов. Таким образом, при некоторой доработке и точном подборе гиперпараметров можно достигнуть и более высоких значений точности.


