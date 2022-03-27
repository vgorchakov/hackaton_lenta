# hackaton_lenta
Hackaton "Hack The Cart" from Lenta 

The task was to build a reccomendation system for buyers at "Lenta".

Took 2nd place on public and private leaderboard out of 100+ teams.


Входные файлы:
  hist_data.csv - файл с датой для обучения 
  test.csv - файл с датой для валидации решения на хакатоне
  
Ноутбуки:
eda.ipynb - разведочный анализ
user_class.ipynb - классификация пользователей в 7 групп (число кластеров получено методом локтя)
class_rec.ipynb - рекомендации для групп
local_validation_groups.ipynb - соединение личных рекомендаций и групповых
  
  Порядок работы:
1. Запустить user_class.ipynb, получить датафрейм с разделением пользователей на группы
2. Запустить class_rec.ipynb, получить словарь с рекомендациями для групп
3. Запустить local_validation_groups.ipynb, получить пресказание модели
