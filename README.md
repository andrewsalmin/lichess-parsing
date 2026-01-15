# ♟️ Анализ партий на Lichess

[![Python](https://img.shields.io/badge/Python-3.11+-blue?logo=python)](https://www.python.org/)

[![Jupyter](https://img.shields.io/badge/Notebook-Jupyter-orange?logo=jupyter)](https://jupyter.org/)

## 📘 О репозитории
Данный репозиторий содержит проект по анализу партий, сыгранных на lichess.org, выгружаемых с помощью Lichess API.
В проекте использованы библиотеки Python — `requests`, `io`, `python-chess`, `collections`, `datetime`, `matplotlib`.

## 🌐 Онлайн‑просмотр

[![View in nbviewer](https://img.shields.io/badge/Open%20in-nbviewer-blue?logo=jupyter)](https://nbviewer.org/github/andrewsalmin/lichess-parsing/blob/main/lichess_parsing.ipynb)

[![Launch Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/andrewsalmin/lichess-parsing/HEAD?labpath=lichess_parsing.ipynb)

## ⚙️ Как запустить локально
```bash
    # Клонировать репозиторий:
    git clone https://github.com/andrewsalmin/lichess-parsing.git
    
    # Перейти в папку проекта:
    cd lichess-parsing
    
    # Создать виртуальное окружение (один раз):
    python -m venv venv
    
    # Активировать окружение:
    # Linux / macOS:
    source venv/bin/activate
    # Windows (PowerShell / CMD):
    venv\Scripts\activate
    
    # Установить зависимости в это окружение (один раз):
    pip install -r requirements.txt
    
    # Запустить Jupyter
    jupyter notebook

```