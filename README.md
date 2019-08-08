# keras-micronnet [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/nikitkaa/keras-micronnet/)


Keras implementation of MicronNet from the paper "MicronNet: A Highly Compact Deep Convolutional Neural Network Architecture for Real-time Embedded Traffic Sign Classification" (https://arxiv.org/pdf/1804.00497v3.pdf)

## Dataset

Used dataset: [The German Traffic Sign Recognition Benchmark](http://benchmark.ini.rub.de/?section=gtsrb)
* Number of training samples: 39209
* Number of testing samples: 12630


## Results

* Categorical accuracy achieved on the test set - 97.62%;
* Timings of evaluation on the test set with a batch size of 50 (based on 10 runs):
  * Google Colab CPU avg. time - 34.4 sec (best of 3);
  * CPU i5-4258U (Macbook Pro Late 2013) avg. time - 29sec ± 1.99sec (best of 7);
* Total number of parameters: 516,179;
* Model's weights size - 2.1MB.


## Результаты

* Лучшая модель демонстрирует качество классификации порядка 97.62%;
* Время работы классификатора - предсказание полной тестовой выборки с размером батча 50 (на основании 10 измерений):
  * Среднее время на CPU в Google Colab - 34.4 сек. (best of 3);
  * Среднее время на CPU i5-4258U (Macbook Pro Late 2013) - 29сек. ± 1.99сек (best of 7).
* Количество параметров модели: 516,179;
* Объем памяти, занимаемый весами модели - 2.1МБ.
