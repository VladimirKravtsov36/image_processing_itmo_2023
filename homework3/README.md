# Домашнее задание 3. Self-Supervised Learning

Ссылка на Colab: https://colab.research.google.com/drive/1k16APcfYf17jjZuaNO1uUdeoGXnU6lms?usp=sharing

## Эксперимент 1

Была обучена архитектура MobileNetV3 Large через подход SSL 

Оптимизатор AdamW
Лосс CrossEntropyLoss

График функции потерь
![alt text](images/training_ssl_loss.jpeg) 

### Сравнение с архитектурой без SSL предобучения

Лосс из ДЗ1
![alt text](images/hw1_loss.jpeg)

Лосс SSL
![alt text](images/ssl_loss.jpeg)

График метрик из ДЗ1
![alt text](images/hw1_metrics_plot.jpeg)

График метрик SSL
![alt text](images/ssl_metrics_plot.jpeg)

Таблица метрик из ДЗ1
![alt text](images/hw1_metrics_table.jpeg)

Таблица метрик SSL
![alt text](images/ssl_metrics_table.jpeg)

### Выводы

Благодаря SSL претрейну удалось получить более высокие метрики, а также более быструю сходимость модели