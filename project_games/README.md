# Изучение закономерностей, определяющих успешность игр


## Данные

В наличии были следующие данные. Каждая запись в логе — это действие пользователя, или событие.
 - EventName — название события;
 - DeviceIDHash — уникальный идентификатор пользователя;
 - EventTimestamp — время события;
 - ExpId — номер эксперимента: 246 и 247 — контрольные группы, а 248 — экспериментальная.

## Задача
Разобраться как ведут себя пользователи мобильного приложения. А именно:
- проанализировать воронку продаж. Узнать, как пользователи доходят до покупки. Сколько пользователей доходит до покупки, а сколько — «застревает» на предыдущих шагах? На каких именно?
- исследовать результаты A/A/B-эксперимента. Дизайнеры захотели поменять шрифты во всём приложении, а менеджеры испугались, что пользователям будет непривычно. Договорились принять решение по результатам A/A/B-теста. Пользователей разбили на 3 группы: 2 контрольные со старыми шрифтами и одну экспериментальную — с новыми. Необходимо выяснить, какой шрифт лучше.  

## Используемые библиотеки
*pandas*,
*Matplotlib*,
*SciPy*

Проект выполнен на основе данных интернет-магазина «Стримчик», который продаёт по всему миру компьютерные игры. Для анализа были доступны исторические данные о продажах игр, оценке пользователей и экспертов, жанры и платформы (например, Xbox или PlayStation).

Целью проекта является выявление определяющих успешность игры закономерностей, что позволит сделать ставку на потенциально популярный продукт и спланировать рекламные кампании.

Описание данных

Name — название игры
Platform — платформа
Year_of_Release — год выпуска
Genre — жанр игры
NA_sales — продажи в Северной Америке (миллионы проданных копий)
EU_sales — продажи в Европе (миллионы проданных копий)
JP_sales — продажи в Японии (миллионы проданных копий)
Other_sales — продажи в других странах (миллионы проданных копий)
Critic_Score — оценка критиков (максимум 100)
User_Score — оценка пользователей (максимум 10)
Rating — рейтинг от организации ESRB (англ. Entertainment Software Rating Board). Эта ассоциация определяет рейтинг компьютерных игр и присваивает им подходящую возрастную категорию.
В наборе данные до 2016 года. Данные за 2016 год могут быть неполными.

План работы

знакомство с данными и поставленной задачей
предобработка данных (изменение типов данных, обработка пропусков, аномалий, дубликатов)
исследовательский анализ данных
подготовка прототипа решения, проверка результатов и их доработка
оформление результатов и формулирование выводов