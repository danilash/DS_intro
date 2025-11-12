# Итоговые проекты курса «Введение в Data Science»

Ниже приведён список из **30 возможных проектных тем** для итоговой работы.  
Каждый проект предполагает полный **Data Science-пайплайн**:
1. Загрузка и анализ данных  
2. Визуализация  
3. Подготовка и обучение модели  
4. Интерпретация и выводы 

**Каждый студент самостоятельно выбирает тему проекта** в соответствии со своими интересами.

---

## Формат проекта
- Работа индивидуально 
- Репозиторий проекта на GitHub
- Ноутбук (Jupyter/Colab) с чистым и понятным кодом
- Презентация результатов (графики, выводы, точность модели)

---

## Рекомендуемые библиотеки
`pandas`, `numpy`, `matplotlib`, `seaborn`,  
`scikit-learn`, `keras`, `tensorflow`,  
`nltk`, `PIL`, `opencv`, `plotly`

---

## Темы проектов

| № | Название проекта | Датасет | Задача | Результат | Основные библиотеки |
|:-:|------------------|----------|---------|------------|---------------------|
| 1 | **Анализ успеваемости студентов** | [Student Performance (UCI)](https://www.kaggle.com/datasets/whenamancodes/student-performance) | Прогнозировать итоговую оценку учащегося на основе факторов (время на учебу, семья, досуг). | Модель линейной регрессии, R² ≥ 0.65; визуализация факторов влияния. | pandas, seaborn, sklearn |
| 2 | **Прогноз цен на жильё** | [Boston Housing](https://www.kaggle.com/datasets/vikrishnan/boston-house-prices) | Оценить стоимость жилья по характеристикам района. | Регрессионная модель (R² ≥ 0.7), графики корреляций и важности признаков. | pandas, sklearn |
| 3 | **Анализ отзывов о фильмах** | [IMDb Reviews](https://www.kaggle.com/datasets/lakshmi25npathi/imdb-dataset-of-50k-movie-reviews) | Определить эмоциональную окраску отзывов (положительный/отрицательный). | Классификатор (LogReg или нейросеть), accuracy ≥ 85 %; визуализация частот слов. | pandas, sklearn, nltk |
| 4 | **Предсказание уровня счастья стран** | [World Happiness Report](https://www.kaggle.com/datasets/unsdsn/world-happiness) | Прогнозировать индекс счастья страны по социально-экономическим показателям. | Регрессия (R² ≥ 0.8), графики влияния ВВП и здоровья. | pandas, seaborn, sklearn |
| 5 | **Прогноз температуры** | [Daily Weather Data](https://www.kaggle.com/datasets/muthuj7/weather-dataset) | Прогнозировать температуру следующего дня по погодным параметрам. | Регрессия, MAE ≤ 2 °C; графики временных рядов. | pandas, matplotlib, sklearn |
| 6 | **Статистика игроков NBA** | [NBA Players Stats](https://www.kaggle.com/datasets/drgilermo/nba-players-stats) | Найти, какие показатели сильнее влияют на результативность игрока. | Регрессия + визуализация зависимостей; R² ≥ 0.7. | pandas, seaborn, sklearn |
| 7 | **Рекомендательная система песен** | [Spotify Tracks](https://www.kaggle.com/datasets/maharshipandya/-spotify-tracks-dataset) | Находить похожие песни по признакам (темп, танцевальность, энергия). | Content-based рекомендации; интерактивная визуализация похожих треков. | pandas, sklearn |
| 8 | **Классификация жанров книг** | [Goodreads Books](https://www.kaggle.com/datasets/jealousleopard/goodreadsbooks) | Определить жанр книги по описанию. | TF-IDF + классификатор, accuracy ≥ 75 %; визуализация частот слов. | pandas, sklearn |
| 9 | **Популярность видеороликов на YouTube** | [YouTube Trending Videos](https://www.kaggle.com/datasets/datasnaek/youtube-new) | Определить, какие факторы влияют на количество просмотров. | Регрессия (R² ≥ 0.6), графики зависимости лайков/просмотров/категорий. | pandas, seaborn, sklearn |
| 10 | **Прогноз доходов по демографическим данным** | [Adult Income (UCI)](https://www.kaggle.com/datasets/uciml/adult-census-income) | Определить, зарабатывает ли человек > 50 k$ на основе социально-демографических факторов. | Классификация, accuracy ≥ 85 %; визуализация важности признаков. | pandas, sklearn |
| 11 | **Классификация одежды (Fashion MNIST)** | [Fashion MNIST](https://www.kaggle.com/datasets/zalando-research/fashionmnist) | Распознать тип одежды (футболка, кроссовки и т.д.) по изображению. | CNN, точность ≥ 88 %; визуализация предсказаний. | keras, tensorflow |
| 12 | **Классификация животных** | [Animals10](https://www.kaggle.com/datasets/alessiocorrado99/animals10) | Распознавать животных по изображениям. | CNN, точность ≥ 80 %; визуализация confusion matrix. | keras, tensorflow |
| 13 | **Определение марки автомобиля** | [Stanford Cars](https://www.kaggle.com/datasets/jutrera/stanford-car-dataset-by-classes-folder) | Распознать марку автомобиля по изображению. | CNN, accuracy ≥ 85 %; визуализация примеров ошибок. | keras, tensorflow |
| 14 | **Прогноз рейтинга фильмов** | [TMDB 5000 Movies](https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata) | Предсказать средний рейтинг фильма по жанрам, бюджету, актёрам. | Регрессия (R² ≥ 0.7); графики влияния бюджета и жанра. | pandas, sklearn |
| 15 | **Прогноз спроса на электроэнергию** | [Household Power Consumption](https://www.kaggle.com/datasets/uciml/electric-power-consumption-data-set) | Прогнозировать потребление энергии на сутки вперёд. | Временной ряд, MLP, MAE ≤ 10 %; графики трендов. | pandas, keras |
| 16 | **Прогноз активности пользователей фитнес-приложений** | [FitBit Fitness Tracker Data](https://www.kaggle.com/datasets/arashnic/fitbit) | Прогнозировать активность пользователя (шаги, калории) по данным за предыдущие дни. | Регрессия (R² ≥ 0.7); визуализация корреляции сна и активности. | pandas, sklearn |
| 17 | **Классификация растений по виду** | [Plant Species Dataset](https://www.kaggle.com/datasets/olgabelitskaya/flower-color-images) | Распознать вид растения по изображению цветка. | CNN, accuracy ≥ 80 %; визуализация примеров. | keras, tensorflow |
| 18 | **Прогноз аренды велосипедов** | [Bike Sharing (UCI)](https://archive.ics.uci.edu/ml/datasets/bike+sharing+dataset) | Прогнозировать количество аренд велосипедов по погоде и дате. | Регрессия (R² ≥ 0.7); графики сезонных колебаний. | pandas, sklearn |
| 19 | **Сегментация клиентов интернет-магазина** | [E-commerce Data](https://www.kaggle.com/datasets/carrie1/ecommerce-data) | Разделить клиентов на группы по поведению покупок. | Кластеризация (KMeans), визуализация кластеров и профилей. | pandas, sklearn |
| 20 | **Прогноз задержек авиарейсов** | [Flight Delays](https://www.kaggle.com/datasets/usdot/flight-delays) | Предсказать, задержится ли рейс более чем на 15 минут. | Классификация, accuracy ≥ 80 %; графики распределений по аэропортам. | pandas, sklearn |
| 21 | **Классификация блюд по фото (Food-101)** | [Food-101 Dataset](https://www.kaggle.com/datasets/kmader/food41) | Распознать тип блюда по изображению. | CNN, accuracy ≥ 78 %; визуализация примеров предсказаний. | keras, tensorflow |
| 22 | **Анализ продаж видеоигр** | [Video Game Sales](https://www.kaggle.com/datasets/gregorut/videogamesales) | Выявить, какие факторы влияют на продажи игр. | Регрессия (R² ≥ 0.65); графики зависимости от жанра и платформы. | pandas, seaborn |
| 23 | **Анализ загрязнения воздуха** | [Air Quality in India](https://www.kaggle.com/datasets/rohanrao/air-quality-data-in-india) | Прогнозировать уровень загрязнения (PM2.5). | Регрессия (R² ≥ 0.7), визуализация по городам и месяцам. | pandas, matplotlib, sklearn |
| 24 | **Прогноз поступления в вуз** | [Graduate Admissions](https://www.kaggle.com/datasets/mohansacharya/graduate-admissions) | Определить, примут ли абитуриента в вуз по результатам экзаменов. | Классификация, accuracy ≥ 85 %; визуализация важности факторов. | pandas, sklearn |
| 25 | **Анализ эмоций в тексте** | [Emotions Dataset](https://www.kaggle.com/datasets/praveengovi/emotions-dataset-for-nlp) | Классифицировать текст по эмоции (радость, грусть и т.д.). | NLP-модель, accuracy ≥ 80 %; визуализация confusion matrix. | pandas, sklearn, nltk |
| 26 | **Классификация фруктов по фото** | [Fruits 360](https://www.kaggle.com/datasets/moltean/fruits) | Определить вид фрукта по изображению. | CNN, accuracy ≥ 90 %; визуализация примеров. | keras, tensorflow |
| 27 | **Прогноз популярности мобильных приложений** | [Google Play Store Apps](https://www.kaggle.com/datasets/lava18/google-play-store-apps) | Прогнозировать количество установок приложения по рейтингу, категории и отзывам. | Регрессия (R² ≥ 0.75); визуализация влияния рейтинга и цены. | pandas, sklearn |
| 28 | **Определение фейковых новостей** | [Fake and Real News Dataset](https://www.kaggle.com/datasets/clmentbisaillon/fake-and-real-news-dataset) | Классифицировать новости как настоящие или фейковые. | NLP-модель TF-IDF + LogReg, accuracy ≥ 85 %. | pandas, sklearn |
| 29 | **Классификация рентгеновских снимков лёгких** | [Chest X-Ray Pneumonia](https://www.kaggle.com/datasets/paultimothymooney/chest-xray-pneumonia) | Определить, есть ли у пациента признаки пневмонии по снимку лёгких. | CNN, accuracy ≥ 85 %; визуализация Grad-CAM и примеров ошибок. | keras, tensorflow |
| 30 | **Прогноз исхода футбольных матчей** | [European Soccer Database](https://www.kaggle.com/datasets/hugomathien/soccer) | Предсказать исход матча (победа/ничья/поражение). | Классификация, accuracy ≥ 70 %; визуализация статистики команд. | pandas, sklearn |

---

## Требования по оформлению проекта
- Используйте **GitHub** для хранения кода и данных (или ссылку на Kaggle)  
- Добавьте **README.md** с описанием задачи, используемых библиотек и результатов  
- Визуализации оформите аккуратно, с подписями и легендами  
- Указывайте метрики качества модели (accuracy, MSE и т.п.)  
- Финальный ноутбук должен быть читаемым и логичным  
- Краткая презентация (8-10 слайдов)  
- Рефлексия: что получилось, что нет, какие данные повлияли сильнее всего

---

**Удачи с проектом!**  
Помните: цель — не просто натренировать модель, а **понять данные, сделать выводы и красиво их представить.**