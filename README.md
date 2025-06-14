# тестовое задание 

Тестовое задание: Предсказание цены авто на взятых с сайта auto.kz данных + анализ амортизации цены автомобиля


## Краткое описание

*Суть задачи*

*Что нужно сделать*
1) Построить модель машинного обучения
Необходимо создать модель, которая по входным параметрам будет предсказывать цену автомобиля.

2) Проанализировать динамику изменения стоимости
Нужно изучить, как стоимость автомобиля меняется с течением времени. Для разных производителей или моделей темпы обесценивания могут отличаться. Можно сгруппировать автомобили в кластеры с похожим поведением и описать свойства этих кластеров.

*Оформить результаты*
Результаты работы нужно представить в виде презентации (PowerPoint) или Jupyter-ноутбука. В отчёте следует показать:

- Как вы тестировали разные модели,

- Какую модель выбрали и почему,

- Какие метрики использовали,

- Какие параметры включили в модель,

- Какие выводы сделали по амортизации.

Технические детали
Для анализа рекомендуется использовать Python и библиотеки: matplotlib, seaborn, sklearn.

---

## Установка

1. **Клонирование репозитория**
   ```bash
   git clone https://github.com/Halssara/test_task_outsource.git
   cd test_task_outsource
   ```

2. **Установка зависимостей**
   ```bash
   pip install -r requirements.txt
   ```

3. **Загрузка данных**

   ```
   Данные можно скачать по ссылке
   https://drive.google.com/file/d/1JtTzGBeye-Q211NumAncGDc4i-YYsO-a/view?usp=sharing
   ```
---

## Использование

1. **Запуск Jupyter Notebook**
   ```
   jupyter notebook
   ```
   Откройте файл с основным кодом в браузере.

2. **Основные команды**
   - Для запуска анализа — выполните ячейки в Jupyter Notebook.
   - Для обучения модели — используйте соответствующие скрипты или ячейки ноутбука.

---

## Структура проекта

```
.
├── README.md
├── jupyter_notebook.ipynb  # Основной код в Jupyter Notebook
├── cars.csv                # csv файл с данными
└── requirements.txt        # Зависимости проекта (если есть)
```

---

## Игнорируемые файлы

Следующие папки и файлы добавлены в `.gitignore` и не включаются в репозиторий:
- `.idea/`
- `.git/`
- `catboost_info/`
- `venv/`
