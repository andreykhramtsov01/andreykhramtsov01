<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=26&pause=1000&color=3776AB&center=true&vCenter=true&width=620&lines=Привет!+Я+Андрей+👋;Python+Backend+Developer;FastAPI+%7C+PostgreSQL+%7C+Docker+%7C+AI" alt="Typing SVG" />

<br/>

**Python Backend Developer** из Москвы 🇷🇺  
Строю REST API, AI-интеграции и инструменты автоматизации

[![GitHub followers](https://img.shields.io/github/followers/andreykhramtsov01?label=Followers&style=social)](https://github.com/andreykhramtsov01)
&nbsp;
[![Profile views](https://komarev.com/ghpvc/?username=andreykhramtsov01&color=3776AB&style=flat)](https://github.com/andreykhramtsov01)

</div>

---

## 👨‍💻 О себе

- 🎯 Ищу стажировку: **QA Engineer** или **Backend Developer**
- 🔭 Сейчас работаю над: покрытием проектов pytest-тестами и настройкой CI/CD
- 🌱 Изучаю: pytest, GitHub Actions, тест-стратегии
- 💬 Спроси меня про: FastAPI, PostgreSQL, Docker, LangChain, COM-автоматизацию
- 📍 Москва

---

## 🚀 Проекты

<table>
<tr>
<td width="50%" valign="top">

### 🤖 Banking Python Mentor Bot
[![Repo](https://img.shields.io/badge/GitHub-banking--python--mentor--bot-blue?style=flat&logo=github)](https://github.com/andreykhramtsov01/banking-python-mentor-bot)

Русскоязычный **AI-наставник** по Python и backend-разработке для банковского домена.

**Особенности:**
- Web UI на Jinja2 + Vanilla JS (Fetch API, без перезагрузки)
- Память разговора по `session_id` через LangChain
- Поддержка OpenAI и OpenRouter (любой LLM)
- REST API: `/api/chat`, `/api/history`, `/api/clear`
- Docker-запуск одной командой

**Стек:** `FastAPI` `LangChain` `langchain-openai` `Jinja2` `JavaScript` `Docker`  
![Tests](https://img.shields.io/badge/тесты-pytest_%2B_mock-0A9EDC?style=flat&logo=pytest&logoColor=white)

</td>
<td width="50%" valign="top">

### 💳 Payment Simulator API
[![Repo](https://img.shields.io/badge/GitHub-payment--simulator-blue?style=flat&logo=github)](https://github.com/andreykhramtsov01/payment-simulator)

**REST API** для симуляции обработки платежей с реалистичной статистикой.

**Особенности:**
- CRUD операции над платежами
- Симуляция статусов: success (70%) / failed (20%) / processing (10%)
- Агрегированная статистика по статусам
- Миграции через Alembic
- Зависимости через Pydantic Settings

**Стек:** `FastAPI` `PostgreSQL` `SQLAlchemy 2.0` `Alembic` `psycopg3` `Docker`  
![Tests](https://img.shields.io/badge/тесты-pytest_%2B_TestClient-0A9EDC?style=flat&logo=pytest&logoColor=white)

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🗂️ DOCEditor
[![Repo](https://img.shields.io/badge/GitHub-DOCEditor-blue?style=flat&logo=github)](https://github.com/andreykhramtsov01/DOCEditor)

**Desktop-приложение** для автоматической доработки шаблонных протоколов диспансерного наблюдения (`.doc`) через COM-автоматизацию Microsoft Word.

**Особенности:**
- GUI на Tkinter (без сторонних зависимостей)
- COM-автоматизация Word через `pywin32`
- Пакетная обработка нескольких файлов
- Сборка в `.exe` через PyInstaller
- Покрыт unittest-тестами (`Test/` директория)

**Стек:** `Python` `Tkinter` `pywin32` `PyInstaller` `unittest`  
![Tests](https://img.shields.io/badge/тесты-unittest-3776AB?style=flat&logo=python&logoColor=white)

</td>
<td width="50%" valign="top">

### 🔜 В планах
- [ ] pytest-тесты для payment-simulator и banking-bot
- [ ] GitHub Actions CI (автозапуск тестов на пуш)
- [ ] Перенос истории чата в PostgreSQL (banking-bot)
- [ ] RAG по банковской документации (banking-bot)
- [ ] Деплой в облако (Railway / Render)
- [ ] Добавить пагинацию и авторизацию в payment-simulator

</td>
</tr>
</table>

---

## 🛠️ Стек

<div align="center">

**Backend**

[![Python](https://img.shields.io/badge/Python_3.11+-3776AB?style=flat&logo=python&logoColor=white)](https://python.org)
[![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white)](https://fastapi.tiangolo.com)
[![Pydantic](https://img.shields.io/badge/Pydantic_v2-E92063?style=flat&logo=pydantic&logoColor=white)](https://docs.pydantic.dev)
[![Uvicorn](https://img.shields.io/badge/Uvicorn-4B0082?style=flat&logo=gunicorn&logoColor=white)](https://www.uvicorn.org)

**Базы данных**

[![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=flat&logo=postgresql&logoColor=white)](https://postgresql.org)
[![SQLAlchemy](https://img.shields.io/badge/SQLAlchemy_2.0-4F337A?style=flat&logo=sqlalchemy&logoColor=white)](https://sqlalchemy.org)
[![Alembic](https://img.shields.io/badge/Alembic-2F4F4F?style=flat&logo=alembic&logoColor=white)](https://alembic.sqlalchemy.org)

**AI / LLM**

[![LangChain](https://img.shields.io/badge/LangChain-FF6B35?style=flat&logo=langchain&logoColor=white)](https://langchain.com)
[![OpenAI](https://img.shields.io/badge/OpenAI_API-412991?style=flat&logo=openai&logoColor=white)](https://openai.com)
[![OpenRouter](https://img.shields.io/badge/OpenRouter-FF6B35?style=flat&logo=openai&logoColor=white)](https://openrouter.ai)

**DevOps**

[![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)](https://docker.com)
[![Docker Compose](https://img.shields.io/badge/Docker_Compose-2496ED?style=flat&logo=docker&logoColor=white)](https://docs.docker.com/compose)

**Frontend (базовый)**

[![Jinja2](https://img.shields.io/badge/Jinja2-B41717?style=flat&logo=jinja&logoColor=white)](https://jinja.palletsprojects.com)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)](https://developer.mozilla.org/docs/Web/JavaScript)
[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)](https://developer.mozilla.org/docs/Web/HTML)

**Desktop / Автоматизация**

[![Tkinter](https://img.shields.io/badge/Tkinter-3776AB?style=flat&logo=python&logoColor=white)](https://docs.python.org/3/library/tkinter.html)
[![pywin32](https://img.shields.io/badge/pywin32_(COM)-0078D6?style=flat&logo=windows&logoColor=white)](https://github.com/mhammond/pywin32)
[![PyInstaller](https://img.shields.io/badge/PyInstaller-3776AB?style=flat&logo=python&logoColor=white)](https://pyinstaller.org)

**Тестирование**

[![pytest](https://img.shields.io/badge/pytest-0A9EDC?style=flat&logo=pytest&logoColor=white)](https://pytest.org)
[![unittest](https://img.shields.io/badge/unittest-3776AB?style=flat&logo=python&logoColor=white)](https://docs.python.org/3/library/unittest.html)
[![httpx](https://img.shields.io/badge/httpx-333333?style=flat&logo=python&logoColor=white)](https://www.python-httpx.org)

</div>

---

## 🧪 Тестирование

Уделяю внимание качеству кода и покрытию тестами во всех проектах:

| Проект | Фреймворк | Что покрыто |
|--------|-----------|-------------|
| [DOCEditor](https://github.com/andreykhramtsov01/DOCEditor) | `unittest` | COM-автоматизация Word, обработка файлов. Тесты автоматически пропускаются если Word недоступен |
| [payment-simulator](https://github.com/andreykhramtsov01/payment-simulator) | `pytest` + `httpx TestClient` | Все REST-эндпоинты: создание/получение платежей, симуляция статусов, статистика, 404-сценарии |
| [banking-python-mentor-bot](https://github.com/andreykhramtsov01/banking-python-mentor-bot) | `pytest` + `unittest.mock` | API-эндпоинты, история чата, очистка сессии, обработка ошибок LLM — с моком модели (без реальных API-запросов) |

```bash
# Запуск тестов
pytest tests/ -v                            # payment-simulator, banking-bot
python -m unittest discover -s Test -v      # DOCEditor
```

---

## 📊 GitHub Stats

<div align="center">

<img src="https://github-readme-streak-stats.herokuapp.com/?user=andreykhramtsov01&theme=tokyonight&hide_border=true" height="160"/>
&nbsp;
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=andreykhramtsov01&layout=compact&theme=tokyonight&hide_border=true&langs_count=6" height="160"/>

</div>

---

## 📫 Контакты

<div align="center">

[![Telegram](https://img.shields.io/badge/Telegram-@D__r__u__c__e-2AABEE?style=for-the-badge&logo=telegram&logoColor=white)](https://t.me/D_r_u_c_e)
&nbsp;
[![Email](https://img.shields.io/badge/Email-andrey.khramtsov01@gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:andrey.khramtsov01@gmail.com)

</div>
