# 👋 Привет, я Анастасия Патрушева
Аналитик данных с бэкграундом в бизнес- и системном анализе

---

## 📋 Обо мне

Перехожу в аналитику данных из бизнес- и системного анализа. 4,5 года работала в RPA-стартапе: собирала требования, писала ТЗ, координировала запуск решений для банков и ритейла. Последние 1,5 года учусь на аналитика данных и собираю портфолио проектов.

Мне интересно находить в данных ответы на бизнес-вопросы и оформлять их так, чтобы результат был понятен и команде, и стейкхолдерам. А ещё умею довести данные до продукта — собрать пайплайн и дашборд от сбора до деплоя. 

**Сейчас фокусируюсь на**:
- Продуктовой аналитике и проверке гипотез
- Визуализации метрик и построении дашбордов
- Чистке, трансформации и исследовании данных в pandas
- SQL-запросах средней и высокой сложности (оконные функции, CTE)

---

## 🛠 Инструменты

**Анализ и визуализация** 
![SQL](https://img.shields.io/badge/SQL-003B57?style=flat-square&logo=postgresql&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=flat-square&logo=python&logoColor=white)
![Seaborn](https://img.shields.io/badge/Seaborn-3776AB?style=flat-square&logo=python&logoColor=white)
![Plotly](https://img.shields.io/badge/Plotly-3F4F75?style=flat-square&logo=plotly&logoColor=white)
![Altair](https://img.shields.io/badge/Altair-1E88E5?style=flat-square)
![SciPy](https://img.shields.io/badge/SciPy-8CAAE6?style=flat-square&logo=scipy&logoColor=white)
![statsmodels](https://img.shields.io/badge/statsmodels-3F51B5?style=flat-square)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white)
![Yandex DataLens](https://img.shields.io/badge/DataLens-FC6F66?style=flat-square&logo=yandex&logoColor=white)
![Apache Superset](https://img.shields.io/badge/Apache_Superset-20A6C9?style=flat-square&logo=apachesuperset&logoColor=white)

**Базы данных и Big Data** 
![ClickHouse](https://img.shields.io/badge/ClickHouse-FFCC01?style=flat-square&logo=clickhouse&logoColor=black)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![DuckDB](https://img.shields.io/badge/DuckDB-FFF000?style=flat-square&logo=duckdb&logoColor=black)
![PySpark](https://img.shields.io/badge/PySpark-E25A1C?style=flat-square&logo=apachespark&logoColor=white)

**Оркестрация и инструменты** 
![Apache Airflow](https://img.shields.io/badge/Apache_Airflow-017CEE?style=flat-square&logo=apache-airflow&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat-square&logo=jupyter&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)

---

## 📁 Проекты в портфолио

### 🎮 Проект 1: LoL Analytics — сквозная дата-платформа и дашборд
**Задача**: Построить полный путь данных по ранкед-матчам League of Legends — от сбора до интерактивного дашборда — и оценить силу чемпионов, эффективность предметов и сдвиги меты со статистической строгостью  
**Инструменты**: Python (pandas, scikit-learn), DuckDB, Parquet, звёздная схема, Streamlit, Altair; интервал Уилсона, Z-тест долей, KMeans  
**Результат**: Живой дашборд на Streamlit — 9 вкладок, 3 источника данных, ~26 000 матчей; тир-лист чемпионов по нижней границе Уилсона, значимые баф/нерф между патчами через Z-тест, сегментация игроков на архетипы (KMeans)  
[🔗 Дашборд →](https://lol-analytics-asvnevc2yjcwphjea7dyru.streamlit.app/) · [🔗 Репозиторий →](https://github.com/AnastasiaPatrusheva/lol-analytics)

### 🎓 Проект 2: A/B-тест образовательного онбординга в финтехе (SollmaFin)
**Задача**: Оценить влияние обучающего блока о финансовых рисках на удержание и повторные депозиты новых пользователей в Латинской Америке  
**Инструменты**: Python (pandas, scipy, statsmodels), бутстрап, funnel analysis, Z/t-тесты  
**Результат**: Конверсия во второй депозит выросла на **+60,9%** (p < 0,001); фича рекомендована к внедрению как инструмент повышения качества клиентской базы  
[🔗 Подробнее →](https://github.com/AnastasiaPatrusheva/Data-Analytics-Portfolio/tree/master/fintech-onboarding)

### 📈 Проект 3: Юнит-экономика и оптимизация каналов привлечения (Procrastinate Pro+)
**Задача**: Выявить причины стагнации выручки при росте аудитории после запуска нового контента; рассчитать CAC, LTV₂₈, ROI по 4 каналам  
**Инструменты**: Python (pandas, seaborn), когортный анализ, тепловые карты, статистическая проверка гипотез  
**Результат**: Выявлен канал с **ROI +170%**; сформулирована рекомендация по перераспределению бюджета, прогноз роста общего ROI с 1,2× до 2,0×  
[🔗 Подробнее →](https://github.com/AnastasiaPatrusheva/Data-Analytics-Portfolio/tree/master/unit-economics-channels)

### 🛒 Проект 4: Поиск точек роста маркетплейса + микро-эксперимент
**Задача**: Найти причины падения монетизации во второй половине года; протестировать гипотезу стимулирования низкоконверсионного трафика  
**Инструменты**: Python (pandas, plotly, scipy), сегментация, воронки, A/B-тест, Z-тест  
**Результат**: Бонус на первую покупку поднял конверсию среди пользователей TikTok с **1,0% до 7,5%** (+6,5 п.п., p < 0,000001) без падения среднего чека; механика рекомендована к масштабированию при контроле стоимости стимула  
[🔗 Подробнее →](https://github.com/AnastasiaPatrusheva/Data-Analytics-Portfolio/tree/master/marketplace-analysis)

### ⚙️ Проект 5: ETL-пайплайн аналитики стримингового сервиса
**Задача**: Ежедневно превращать сырые логи прослушиваний стримингового сервиса в витрины для BI — по типам контента, географии и сегментам аудитории, без ручных выгрузок и с возможностью пересчитать историю  
**Инструменты**: PySpark, Apache Airflow, ClickHouse, Apache Superset, Parquet, Docker, pytest  
**Результат**: Ежедневный пайплайн, обрабатывающий данные по одной дате: контроль качества до загрузки, повторный запуск без дублей, история за 102 дня пересчитана (**102 запуска без сбоя**); дашборд из 5 графиков в Superset  
[🔗 Подробнее →](https://github.com/AnastasiaPatrusheva/Data-Analytics-Portfolio/tree/master/streaming-content-etl)

---

## 🎯 Что ищу

Позицию **Data Analyst**, где смогу:
- Применять и развивать навыки: Python, SQL, статистика, визуализация
- Участвовать в решении реальных бизнес-задач с измеримым результатом
- Расти как специалист в среде, где важны данные, эксперименты и обратная связь

---

## 📬 Контакты

Готова выполнить тестовое задание и пройти собеседование.

Связаться со мной:

[✉️ Написать в Telegram](https://t.me/Anastasia1735)  
[📧 Отправить на Email](mailto:a_patrusheva@internet.ru)  
[📄 Посмотреть резюме на HH](https://hh.ru/resume/b5182467ff105ec7530039ed1f5665664f6d77)
