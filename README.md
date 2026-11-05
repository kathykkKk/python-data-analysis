# Анализ данных на Python

Репозиторий с лабораторными работами по курсу «Анализ данных на Python».

Бацанова Екатерина Александровна, ИСУ 367871, группа M4182

## Лабораторные работы

| № | Тема | Данные | Блокнот |
|---|---|---|---|
| 1 | Иерархический кластерный анализ | [Digit Dataset](HW1/task.pdf) | [lab1.ipynb](HW1/lab1.ipynb) |
| 2 | Кластерный анализ методом k-средних (k-means) | [Digit Dataset](HW1/task.pdf) | [lab2.ipynb](HW2/lab2.ipynb) |
| 3 | Кластерный анализ методом DBSCAN | [Digit Dataset](HW1/task.pdf) | [lab3.ipynb](HW3/lab3.ipynb) |

## Структура репозитория

```text
.
├── HW1/
│   ├── lab1.ipynb
│   ├── digit.dat
│   └── task.pdf
│
└── README.md
```

Каждая лабораторная работа `n` размещается в отдельной директории `HWn/`. В ней находятся Jupyter Notebook с решением, необходимые исходные данные и задание к работе.

## Запуск

**1. Клонировать репозиторий:**

```bash
git clone <URL_репозитория>
cd python-data-analysis
```

**2. Запустить лабораторную работу:**

```bash
cd HWn
jupyter lab labn.ipynb
```

После открытия блокнота выполнить все ячейки последовательно (**Run → Run All Cells**).

## Используемые технологии

- Python
- Jupyter Notebook (Google Colab)
- NumPy
- Pandas
- SciPy
- Matplotlib

Код оформляется с учётом рекомендаций [PEP 8](https://peps.python.org/pep-0008/).
