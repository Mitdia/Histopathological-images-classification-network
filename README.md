# Histopathological-images-classification-network

Реализованны классы ModelNeural и ModelSVM для создания, обучения и тестирования моделей основанных на сверточных нейронных сетях и SVM классификаторе соответсввенно.
Также написан генератор данных для обучения нейронных сетей (валидация/батчи). (class DataGenerator)

Также реализованы улучшения:

## Features
* #VTP - Визуализация матрицы ошибок.
* #VLP - Визуализация процесса обучения нейронных сетей.
* #AHC - Автоматический подбор гиперпараметров для SVM модели
* #DA - Аугментация данных при подаче в нейронную сеть (для каждого батча случайно прреобразуются входные данные)
* #V/P_DL - Вывод данных каждую эпоху + валидация каждую эпоху


