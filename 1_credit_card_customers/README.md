# Прогнозирование оттока клиентов банка.

Менеджер банка обеспокоен тем, что все больше и больше клиентов отказываются от обслуживания кредитных карт. Он был бы очень признателен, если бы кто-то мог предсказать кто скоро откажется от услуг, чтобы работники могли заранее обратиться к клиентам, чтобы предоставить им более качественные услуги и изменить их решения в противоположном направлении.

## Цель исследования:

Построить модель, которая предскажет, уйдет ли в ближайшее время клиент

## Итог исследования:

Итоговая модель - lgboost('learning_rate': 0.3, 'max_depth': 4, 'n_estimators': 400). Итоговая метрика модели `f1`: `0.90`, `auc-roc`: `0.99`.

В дальнейшем, необходимо будет упорядочить клиентов по вероятности ухода и обрабатывать наиболее вероятно уходящих. Чтобы оценить порог для обработки клиента необходимы дополнительные данные о планируемых затратах на удерживание и издержки следуемые из ухода клиента.

## Стек технологий:

sklearn, lightgbm, imblearn, shap, re, phik, pandas, numpy, matplotlib, seaborn

## Статус проекта:

Завершен.
