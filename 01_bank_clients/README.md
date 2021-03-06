# Исследование надежности заемщиков
## Описание проекта:
На основе данных кредитного отдела банка провели исследование влияния семейного положения и количества детей на факт погашения кредита в срок. Была получена информация о данных. Определены и обработаны пропуски. Заменены типы данных на соответствующие хранящимся данным. Удалены дубликаты. Выделены леммы в значениях столбца и категоризированны данные. Проведен исследовательский анализ, в котором при помощи сводных таблиц сопоставлялись категории заемщиков и доля просрочек в них.
## Результат:
Анализ показал, что на возврат кредита оказывают влияние наличие детей, семейное положение, уровень дохода и цели заёма. Наиболее платежеспособные клиенты те, у которых отсутствуют дети, и которые имеют доход от 200 тыс. Неженатые или незамужние клиенты имеют больший процент просрочек. Чаще всего среди целей кредита фигурируют недвижимость, автомобиль, образование и свадьба.
## Описание данных:
- children — количество детей заемщика
- days_employed — трудовой стаж, дней
- dob_years — возраст, лет
- education — образование
- education_id — id образования
- family_status — семейное положение
- family_status_id — id семейного положения
- gender — пол
- income_type — тип занятости
- debt — наличие задолженности
- total_income — доход в месяц
- purpose — цель кредита
## Используемые библиотеки:
- pandas
- pymystem3
- collections
