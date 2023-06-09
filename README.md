# Подготовка прототипа модели для металлообрабатывающего предприятия
***Описание проекта:*** 

Подготовьте прототип модели машинного обучения для «Цифры». Компания разрабатывает решения для эффективной работы промышленных предприятий.

Модель должна предсказать коэффициент восстановления золота из золотосодержащей руды. Используйте данные с параметрами добычи и очистки. 

Модель поможет оптимизировать производство, чтобы не запускать предприятие с убыточными характеристиками.

***План работы над проектом:***

1. Подготовить данные;
2. Провести исследовательский анализ данных;
3. Построить и обучить модель; 
4. Общий вывод.

## Вывод
Мы написали функцию, которая поможет нам вычислить `итоговой sMAPE` (эффективности и обогащения). Перебрали гиперпараметры для моделей. Лучшей моделью на обучающей выборке стала `RandomForestRegressor` с параметрами (max_depth=3, n_estimators=21 и max_depth=4, n_estimators=41). У неё лучший показатель `итогового sMAPE`, а именно `8.4`. Мы так же проверили эту модель на адекватность и проверку она прошла. ***Модель адекватна***. На тестовой выборке получили результат `9.6`.
