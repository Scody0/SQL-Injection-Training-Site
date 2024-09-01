# SQL Injection Training Site

![SQL Injection Training Site](https://via.placeholder.com/800x200.png?text=SQL+Injection+Training+Site)

## Description

**SQL Injection Training Site** is an educational website designed for learning about SQL injection vulnerabilities. This project helps users understand how SQL injections work, the risks they pose, and how to prevent them.

## Important Warning ⚠️

> **Attention:** This site is for educational purposes only. Using the acquired knowledge for unauthorized access to data or hacking sites is illegal and punishable by law. The author is not responsible for any actions taken based on the information provided on this site.

## Features

- **Interactive buttons with preset SQL injection commands** — quickly understand the mechanics of attacks.
- **Console for entering custom SQL queries** — allows experimenting with different commands.
- **Dark and light themes** — switch between themes for better usability.
- **Multilingual interface (English and Russian)** — easily switch between languages for broader accessibility.
- **Accordion with command explanations** — detailed explanations for each preset command to enhance understanding.

## Installation and Launch

### Local Launch

1. **Clone the repository:**

    ```bash
    git clone https://github.com/Scody0/SQL-Injection-Training-Site.git
    ```

2. **Navigate to the project directory:**

    ```bash
    cd SQL-Injection-Training-Site
    ```

3. **Run the site using a simple HTTP server (e.g., with Python):**

    ```bash
    python -m http.server
    ```

4. **Open the site in your browser at:**

    ```
    http://localhost:8000
    ```

### Deployment on Hosting

This site can be deployed on any web server (Apache, Nginx) or used as a static page on GitHub Pages, Vercel, or Netlify.

## Usage

### Main Interface Elements

- **Buttons with preset commands** — execute SQL injection commands and immediately see the results.
- **Command input field** — write and run your own SQL queries.
- **Clear button** — clears the output console to start fresh.
- **Theme and language toggle** — switch between light/dark modes and English/Russian language.
- **Accordion with explanations** — collapsible panels with explanations of the preset commands.

### Example Commands

1. `' OR '1'='1` — bypasses authentication by always evaluating to true, allowing login without a password.
2. `' UNION SELECT null, null -- ` — merges data from different tables, potentially exposing hidden information.
3. `' DROP TABLE users -- ` — deletes the `users` table, which could lead to complete data loss.

## Important Information

- **Use knowledge responsibly:** All commands and examples are for learning purposes. Never apply them in real systems without permission.
- **Data security:** Make sure you understand the consequences of running each command, especially if adapting the site for other purposes.
- **Protection against attacks:** Learning about vulnerabilities helps understand how to protect your applications from similar attacks in the future.

## Developer and License

- **Developer:** SCODY
- **Version:** 0.0.4
- **License:** MIT License. You are free to use, modify, and distribute this code under the terms of the license.

## Contacts and Links

- **GitHub:** [https://github.com/Scody0/SQL-Injection-Training-Site](https://github.com/Scody0/SQL-Injection-Training-Site)
- **YouTube:** [https://youtube.com/@scody_org](https://www.youtube.com/@scody_org)
- **Telegram:** [https://t.me/scody_org](https://t.me/scody_org)

## Acknowledgments

Thank you to everyone who supports this project and shares knowledge about web security. Together, we make the internet a safer place!

---

_This project is created for educational purposes and aims to improve the security of web applications. Use wisely._

---

# Учебный сайт по SQL-инъекциям

![Учебный сайт по SQL-инъекциям](https://via.placeholder.com/800x200.png?text=Учебный+сайт+по+SQL-инъекциям)

## Описание

Учебный сайт по SQL-инъекциям предназначен для изучения уязвимостей SQL-инъекций. Проект создан с целью помочь пользователям понять, как работают SQL-инъекции, какие опасности они представляют и как их можно предотвратить.

## Важное предупреждение ⚠️

> **Внимание:** Этот сайт предназначен исключительно для учебных целей. Использование полученных знаний для несанкционированного доступа к чужим данным или взлома сайтов является незаконным и наказуемо по закону. Автор не несет ответственности за любые действия, предпринятые на основе информации, предоставленной на этом сайте.

## Особенности сайта

- **Интерактивные кнопки с предустановленными командами SQL-инъекций** — для быстрого понимания механизмов атак.
- **Консоль для ввода пользовательских SQL-запросов** — позволяет экспериментировать с разными командами.
- **Темная и светлая тема** — переключение между темами для удобства использования.
- **Многоязычный интерфейс (Русский и Английский)** — легко переключаться между языками для расширенной аудитории.
- **Аккордеон с объяснениями команд** — подробные пояснения к каждой предустановленной команде для лучшего понимания.

## Установка и запуск

### Локальный запуск

1. **Склонируйте репозиторий:**

    ```bash
    git clone https://github.com/Scody0/SQL-Injection-Training-Site.git
    ```

2. **Перейдите в директорию проекта:**

    ```bash
    cd SQL-Injection-Training-Site
    ```

3. **Запустите сайт с помощью простого HTTP-сервера (например, с использованием Python):**

    ```bash
    python -m http.server
    ```

4. **Откройте сайт в браузере по адресу:**

    ```
    http://localhost:8000
    ```

### Использование на хостинге

Этот сайт можно развернуть на любом веб-сервере (Apache, Nginx) или использовать как статическую страницу на GitHub Pages, Vercel или Netlify.

## Использование

### Основные элементы интерфейса

- **Кнопки с предустановленными командами** — позволяют выполнить команды SQL-инъекций и сразу увидеть результат.
- **Поле ввода команд** — для написания и выполнения пользовательских SQL-запросов.
- **Кнопка очистки** — очищает консоль вывода, чтобы начать заново.
- **Тема и язык интерфейса** — можно переключать с помощью соответствующих кнопок.
- **Аккордеон с объяснениями** — раскрывающиеся панели с объяснением предустановленных команд.

### Примеры команд

1. `' OR '1'='1` — обходит авторизацию, всегда возвращая истинное значение, что позволяет войти без пароля.
2. `' UNION SELECT null, null -- ` — позволяет объединить данные из разных таблиц и получить доступ к скрытой информации.
3. `' DROP TABLE users -- ` — удаляет таблицу `users`, что может привести к потере всех данных.

## Важная информация

- **Используйте знания ответственно:** Все команды и примеры предназначены для обучения. Никогда не применяйте их в реальных системах без разрешения.
- **Безопасность данных:** Убедитесь, что вы понимаете последствия выполнения каждой команды, особенно если решите адаптировать или модифицировать сайт для других целей.
- **Защита от атак:** Изучение уязвимостей помогает лучше понять, как защитить свои приложения от подобных атак в будущем.

## Разработчик и лицензия

- **Разработчик:** SCODY
- **Версия:** 0.0.4
- **Лицензия:** MIT License. Вы можете свободно использовать, изменять и распространять этот код, соблюдая условия лицензии.

## Контакты и ссылки

- **GitHub:** [https://github.com/Scody0/SQL-Injection-Training-Site](https://github.com/Scody0/SQL-Injection-Training-Site)
- **YouTube:** [https://youtube.com/@scody_org](https://www.youtube.com/@scody_org)
- **Telegram:** [https://t.me/scody_org](https://t.me/scody_org)

## Благодарности

Спасибо всем, кто поддерживает проект и делится знаниями о веб-безопасности. Вместе мы делаем интернет безопаснее!

---

_Этот проект создан с целью обучения и повышения уровня безопасности веб-приложений. Используйте с умом._
