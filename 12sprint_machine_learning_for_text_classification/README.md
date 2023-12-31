
# Проект для «Викишоп»

Поздравляем! Вы прошли курс в тренажёре. Самое время проверить знания и решить новую задачу машинного обучения. Выполнять работу будете самостоятельно.

Когда закончите, отправьте её на проверку ревьюеру: он пришлёт комментарии в течение суток. После этого нужно доработать проект и пройти повторную проверку.

Скорее всего, вы доработаете кейс по комментариям ещё несколько раз. Это нормально.

Проект завершён, когда ревьюер одобрит все доработки.

## Описание проекта

Интернет-магазин «Викишоп» запускает новый сервис. Теперь пользователи могут редактировать и дополнять описания товаров, как в вики-сообществах. То есть клиенты предлагают свои правки и комментируют изменения других. Магазину нужен инструмент, который будет искать токсичные комментарии и отправлять их на модерацию.

Обучите модель классифицировать комментарии на позитивные и негативные. В вашем распоряжении набор данных с разметкой о токсичности правок.

Постройте модель со значением метрики качества _F1_ не меньше 0.75.

### Инструкция для проекта

В любом случае алгоритм решения выглядит так:

1.  Загрузите и подготовьте данные.
2.  Обучите разные модели.
3.  Сделайте выводы.

### Описание данных

Столбец _text_ в нём содержит текст комментария, а _toxic_ — целевой признак.

