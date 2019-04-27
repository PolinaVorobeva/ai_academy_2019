# ai_academy_2019
final solution, top-8 (0.90208)

Сайт проекта: https://contest.ai-academy.ru

Проект Сбербанка, направленный на популяризацию Машинного Обучения (МО) в рядах школьников. Финальным этапом соревнования является хакатон, на котором предлагается решить задачу оценки опытности игрока по данным с его игр.
### Здесь предстайвленно мое решение, занявшее 8 место в итоговом рейтинге участников Хакатона

# Описание задачи

Для решения финальной задачи были предоставлены два набора данных train и test

Обучающая (train) выборка содержит описание некоторого числа матчей, опытность игрока в которых известна
Тестовая (test) выборка - данные для которых нужно предсказать вероятность принадлежности игрока к опытным или новичкам.

# Формат решения

На хакатоне нам предлагалось записывать ответы (набор вероятностей) в csv-таблицу, содержащую две колонки: 'id' - идентификатор героя и 'skilled_prob' - вероятность принадлежности игрока к опытным.
Финальной метрикой была метрика ROC_AUC (https://en.wikipedia.org/wiki/Receiver_operating_characteristic)

# Дополнительно

Базавое решение от организаторов:

https://github.com/sberbank-ai/ai-academy-2019/blob/master/Dota2SkillPrediction_Tutorial.ipynb

# Данные

Данные для решения можно найти по ссылке:
https://s3.eu-central-1.amazonaws.com/ai-academy-2019/public/final/{filename}

filenames: academy2019_final_train.jsonlines, academy2019_final_test.jsonlines, academy2019_final_train.csv, academy2019_final_test.csv
