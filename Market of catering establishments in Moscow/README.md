# Исследование рынка заведений общественного питания в Москве

## Описание проекта

Цель проекта — исследовать рынок общественного питания в Москве и оценить возможности для открытия новой кофейни, вдохновленной концепцией «Central Perk» из сериала «Друзья». Анализ включает изучение структуры рынка, конкуренции и успешных практик для формирования рекомендаций инвесторам.

## Данные

Использованы данные о заведениях общественного питания Москвы, включающие информацию о названиях, адресах, категориях заведений, режиме работы, рейтингах, ценах, географическом расположении и других характеристиках.

**Ключевые колонки:**
- `name` — название заведения
- `category` — тип заведения (например, кафе, ресторан, кофейня)
- `rating` — рейтинг заведения
- `price` — ценовая категория
- `lat`, `lng` — координаты заведения

## Задачи проекта

Проект состоит из следующих этапов:

1. **Загрузка и предварительная обработка данных:**
   - Обработка данных, включая удаление дубликатов и работу с пропусками.
   
2. **Анализ структуры рынка:**
   - Анализ количества и типов заведений, их распределение по районам Москвы.
   
3. **Оценка конкурентной среды:**
   - Анализ рынка кофеен, определение успешных практик и ключевых факторов успеха.
   
4. **Подготовка рекомендаций:**
   - Разработка рекомендаций для инвесторов на основе полученных данных.
   
5. **Презентация и выводы:**
   - Создание презентации для инвесторов с ключевыми выводами и предложениями.

## Используемые библиотеки

Проект выполнен с использованием следующих библиотек:

- `pandas`
- `numpy`
- `seaborn`
- `matplotlib`
- `folium`
- `json`

## Результаты

Центральный административный округ (ЦАО) не подходит для открытия новой кофейни из-за высокой конкуренции и дорогостоящей аренды. Взамен рекомендуется Северо-Западный административный округ (СЗАО), где конкуренция ниже, рейтинги заведений выше, а цены более доступные. Для успешного запуска кофейни в этом районе целесообразно установить цену капучино в 170 рублей, предусмотреть около 50 посадочных мест и рассмотреть круглосуточный режим работы.

