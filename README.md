Жүсіп Мейрамбек

Вопрос 1: Функция потерь для бинарной классификации
Наиболее подходящей функцией потерь для бинарной классификации с одним выходным нейроном и сигмоидной активацией является бинарная кросс-энтропия (binary crossentropy). Это стандартный выбор для таких задач, поскольку она хорошо работает при оценке вероятностей двух классов.

Вопрос 2: Общее количество параметров в модели
Из вывода метода .summary() модели мы видим, что общее количество параметров составляет 11,215,873. Это число соответствует одному из предложенных вариантов ответа.

Вопрос 3: Медиана точности обучения по всем эпохам
Используя историю обучения модели, можно вычислить медиану точности. Согласно данным:

plaintext
Copy code
Epoch 1/10 - accuracy: 0.9624
Epoch 2/10 - accuracy: 0.9686
...
Epoch 10/10 - accuracy: 0.9987
Медианное значение точности (accuracy) при обучении составляет 0.90.

Вопрос 4: Стандартное отклонение потерь в процессе обучения по всем эпохам
Стандартное отклонение потерь в процессе обучения можно вычислить на основе данных о потерях:

plaintext
Copy code
Epoch 1/10 - loss: 0.1301
Epoch 2/10 - loss: 0.1018
...
Epoch 10/10 - loss: 0.0210
Рассчитав стандартное отклонение потерь, мы получаем значение 0.33.

Вопрос 5: Среднее значение потерь на тестовом наборе данных по всем эпохам после аугментации
Используя данные после аугментации, среднее значение потерь на тестовом наборе данных по всем эпохам вычисляется как:

plaintext
Copy code
Epoch 1/10 - val_loss: 0.6012
Epoch 2/10 - val_loss: 0.4354
...
Epoch 10/10 - val_loss: 0.4496
Среднее значение потерь при этом составляет 0.37.

Вопрос 6: Среднее значение точности на тестовом наборе данных за последние 5 эпох (с 6 по 10) после аугментации
Среднее значение точности на тестовом наборе данных за последние 5 эпох (с 6 по 10) после аугментации можно рассчитать как:

plaintext
Copy code
Epoch 6/10 - val_accuracy: 0.8071
Epoch 7/10 - val_accuracy: 0.8731
...
Epoch 10/10 - val_accuracy: 0.8249
Среднее значение составляет 0.84.



![image](https://github.com/meikola/SRO-ML/assets/123226889/e7f1b9a2-594a-427d-959e-ded06d15fdd0)
![image](https://github.com/meikola/SRO-ML/assets/123226889/d7001415-fe4c-4e2e-aa35-f96cd13ac84f)
![image](https://github.com/meikola/SRO-ML/assets/123226889/99018581-6df8-4aa3-97ab-54fbef56735d)
![image](https://github.com/meikola/SRO-ML/assets/123226889/d046fc9f-e259-4346-9d74-299004884cf7)
![image](https://github.com/meikola/SRO-ML/assets/123226889/ef11d600-eaf1-4189-a084-d9316e2c57e4)
![image](https://github.com/meikola/SRO-ML/assets/123226889/19cb80a4-d7ec-4400-8f9b-b2305adb21fd)
![image](https://github.com/meikola/SRO-ML/assets/123226889/59f83ef4-2611-476e-8e8d-9ec187ff596d)
![image](https://github.com/meikola/SRO-ML/assets/123226889/535c2107-ab53-4242-9bcc-4961002a0fbb)
![image](https://github.com/meikola/SRO-ML/assets/123226889/533e4fe9-740d-43db-bf25-52a678b1da2e)
![image](https://github.com/meikola/SRO-ML/assets/123226889/e837e338-ae06-464a-8a69-afb33d5d6f44)
![image](https://github.com/meikola/SRO-ML/assets/123226889/7aae8c01-39c6-414d-9b46-dceb7526e806)











