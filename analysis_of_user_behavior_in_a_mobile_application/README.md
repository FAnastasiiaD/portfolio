# Описание проекта Анализ пользовательского поведения в мобильном приложении
Работа в стартапе, который продаёт продукты питания.

[Для отображения всего функционала, используйте NBCiewer - Jupyter Notebook](https://nbviewer.org/github/FAnastasiiaD/portfolio/blob/main/analysis_of_user_behavior_in_a_mobile_application/analysis_of_user_behavior_in_a_mobile_application_project.ipynb)

Статус проекта: завершен.

## Данные

Данные использования мобильного приложения для продажи продуктов питания.

**Предоставленные данные:**

- Название события;
- Уникальный идентификатор пользователя;
- Время события;
- Номер эксперимента: 246 и 247 — контрольные группы, а 248 — экспериментальная.

## Задачи

Необходимо разобраться, как ведут себя пользователи мобильного приложения.

- Проанализировать воронку продаж;
- Оценить результаты A/A/B-тестирования. 

## Ход исследования

 1. Обзор данных.
 2. Предобработка данных.
 3. Анализ данных.
 4. Воронка событий.
 5. Результаты эксперимента.
 6. Вывод.

## Вывод

При проверке различий между долями уникальных посетителей контрольной группы (2467) и группы с изменённым шрифтом (248)(АAB теста) ни на одном из этапов воронки нет оснований считать доли различными.

Это может говорить о том, что изменение шрифта не оказало координальных изменений, напротив, пользователи с изменненым шрифтом переходят к оплате на 2% больше.

## Используемые библиотеки
- *Pandas*
- *Matplotlib*
- *Plotly*
- *NumPy*
- *SciPy*
- *Math*
- *DateTime*
