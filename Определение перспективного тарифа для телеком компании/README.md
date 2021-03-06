# Определение перспективного тарифа для телеком компании

## Описание проекта

### Исследовательский анализ

В задаче произведен исследовательский анализ поведения клиентов оператора сотовой связи. Анализ проводился на основе выборки размером в 500 записей. На основании полученных данных, сводных таблиц и графиков распределения величин проанализировано поведение клиентов каждого тарифа. Статистическими инструментами проверены гипотезы о различии выручки абонентов разных тарифов и различии выручки абонентов из Москвы и других регионов. Определен наиболее выгодный для компании тарифный план.

### Рекомендация тарифов

Решена задача бинарной классификации. Построена модель, рекомендующая пользователю определенный тариф на основании данных о использовании им сети. В задаче были исследованы следующие виды моделей для бинарной классификации - логистическая регрессия, решающее дерево и случайный лес. Произведена настройка моделей с использованием кросс-валидации. Лучшие результаты показал случайный лес с использованием GridSearch.

## Используемые инструменты 

Pandas для работы с табличными данными.   
Seaborn и matplotlib для визуализации.  
Scipy для проверки статистических гипотез.  
scikit-learn для построения моделей, оценки их качества и кросс-валидации.   