# Курс "Нейронные сети и глубокое обучение" Самарского Университета
Лектор Артем Владимирович Никоноров, д.т.н., artniko@gmail.com  
Ассистент Виктория Витальевна Евдокимова, аспирант Самарского Университета, data.science.sbj@gmail.com


Курс основывается на предыдущих более обзорных лекциях и туториалах по глубокому обучению и его приложениях, в частности, вот [небольшая обзорная лекция](https://youtu.be/Gpq1PFUee88) в Кавказском Математическом Центре. Также во многом этот курс является адаптацией известнейшего курса http://cs231n.stanford.edu/  

## Предварительный график проведения курса.
**Вторая лекция в 14-30 МСК (15-30 по Самаре) 28.09.2020 в Zoom.**  
https://us02web.zoom.us/j/8366671872?pwd=WWh1TXZxbjdxcWgrTjlUdVlSdk5kUT09  
Идентификатор конференции: 836 667 1872  
Код доступа: 755845  


Телеграмм группа курса:
https://t.me/DL_SamU_2020

Предположительно, лекции будут вестись раз в две недели по понедельникам.
Продолжительность лекции два астрономических часа.

[Видеозапись первой лекции](https://www.youtube.com/watch?v=BKG1wEATYOU)


## Предварительный лекционный план.

План может менятся в процессе курса.  

**Лекция 1. Классификация, основанная на данных**   
[Видеозапись лекции 14.09.2020](https://www.youtube.com/watch?v=BKG1wEATYOU)  
Введение в курс.  
Задача классификации изображений.  
Подходы основанные на данных.  
Линейная классификация и knn-классификатор.  

**Лекция 2. Функции потерь и оптимизация.**  
Мультиклассовый SVM и его функция потерь.  
Софтмакс и мультимодальная логистическая регрессия.  
Оптимизация функции потерь.  
Стохастический градиентный спуск.  

**Лекция 3. Нейронные сети и обратное распространение ошибки.**  
Алгоритм обратного распространения ошибки.  
Многослойный перцептрон.  
Классификация с точки зрения нейронной сети.  

**Лекция 4. Сверточные сети (СНС).**  
История.  
Основные операции СНС.  
Применение СНС вне задач машинного зрения.  

**Лекция 5. Инструментарий глубокого обучения.**  
CPU vs GPU vs TPU.  
Пакеты глубокого обучения, Tensorflow, Keras и другие.  
Вычислительные графы СНС.  

**Лекция 6. Обучение СНС, часть 1.**  
Активационные функции, обработка данных сетью.  
Пакетная нормализация и другие трюки.  
Transfer learning.

**Лекция 7. Обучение СНС, часть 2.**  
Политики обновления гиперпараметров.  
Тюнинг процесса обучения.
Аугментация данных.  

**Лекция 8. Архитектуры СНС**  
Базовые архитектуры - AlexNet, VGG, GoogleNet, ResNet, UNET и другие.  

**Лекция 9. Генеративные и рекуррентные модели**  
RNN/LSTM.  
Механизм attention.
Обработка естественного языка.
GAN сети.

**Лекция 10. Прикладные сценарии использования СНС**  
TBD.  

**Лекция 11. Перспективы развития ИИ**  
TBD.  

## Предварительный план лабораторных работ.

План может менятся в процессе курса.  

**Л.Р. 1**  
kNN, многоклассовый SVM, SoftMax.  
[Материалы к лабораторной](https://github.com/da0c/DL_Course_SamU/blob/master/lab_1-2/assignment1.ipynb).

**Л.Р. 2**  
Двухслойная сеть.
[Материалы к лабораторной](https://github.com/da0c/DL_Course_SamU/blob/master/lab_1-2/assignment2.ipynb).

**Л.Р. 3**  
Многослойный перцептрон, обратное распространение ошибки, сверточные сети.

**Л.Р. 4**  
Использование различных архитектуры СНС в Tensorflow/Keras.

**Л.Р. 5**  
Решение прикладной задачи с применением СНС.



## Литература и дополнительные источнки  

1. Отличная книга на русском по глубокому обучению -  
[С. И. Николенко, А. Кадурин, Е. В. Архангельская, Глубокое обучение. Погружение в мир нейронных сетей. 2018](https://www.ozon.ru/context/detail/id/154415719/)  
2. Отличная книга по техническим аспектам реализации на Python -  
[Шолле Франсуа, Глубокое обучение на Python](https://www.ozon.ru/context/detail/id/145615583/)  

3. [Лекционный курс К.В. Воронцова по машинному обучению](http://www.machinelearning.ru/wiki/index.php?title=%D0%9C%D0%B0%D1%88%D0%B8%D0%BD%D0%BD%D0%BE%D0%B5_%D0%BE%D0%B1%D1%83%D1%87%D0%B5%D0%BD%D0%B8%D0%B5_%28%D0%BA%D1%83%D1%80%D1%81_%D0%BB%D0%B5%D0%BA%D1%86%D0%B8%D0%B9%2C_%D0%9A.%D0%92.%D0%92%D0%BE%D1%80%D0%BE%D0%BD%D1%86%D0%BE%D0%B2%29).
4. [Видеолекция академика Ю.И. Жкравлева](https://www.youtube.com/watch?v=R3CMqrrIWOk) об истоках машинного обучения в СССР и о сочетании эвристики и науки в распознавании образов.  
5. Видеолекции С.И. Николенко по GAN сетям [1](https://www.youtube.com/watch?v=SlJgPIOlpiI), [2](https://www.youtube.com/watch?v=w38m5mTrG_M&t=1147s).
Хорошая проерка ваших знаний, на выходе из настоящего курса вы полностью понимать то, что говорится в этих лекциях по GAN.  





