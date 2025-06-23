# Project "Social network - Messanger" | Проєкт "Social network - Messanger" 
.х
## Навігація | Navigation on README:
- [Мета створення проєкту | Purpose of the Project](#мета-створення-проєкту--purpose-of-the-project)
- [Склад команди | Developers](#склад-команди--team-members--developers)
- [Посилання | Links](#посилання--links)
- [Структура | Structure of project](#структура--structure-of-the-project)
- [Функціонал кожного з додатків | Functionality of each application](#функціонал-кожного-з-додатків--functionality-of-each-application)
- [Як встановити та запустити проєкт? | How to install and run the project?](#як-встановити-та-запустити-проєкт--how-to-install-and-run-the-project)
- [Висновок | Conclusion](#висновок--conclusion)

  
## Мета створення проєкту | Purpose of the Project
Мета створення цього проєкту — практика з нововивченими складовими модуля Django: Django Forms, Class-Based Views, Django Channels для роботи з веб-сокетами, а також використання Ajax і робота з форматуванням дат у iso-формат. Його головна мета — вдосконалення наших навичок програмування, спільної командної роботи та втілення дизайнерських ідей.

___

The goal of this project is to practice newly learned parts of the Django framework: Django Forms, Class-Based Views, and Django Channels for working with WebSockets. It also includes using Ajax and formatting dates in ISO format. The main aim is to improve our programming skills, learn to work better and effectively as a team, and apply design ideas in practice.

## Склад команди | Team members | Developers

* [**Ващенко Артем**](https://github.com/VashchenkoArtem) — Teamlead
* [**Овчаренко Юлія**](https://github.com/JuliaOvcharenko)
* [**Сафонова Анна**](https://github.com/AnnaSafonova30)
* [**Марков Дмитро**](https://github.com/DmitriyM08)
* [**Харлан Кирило**](https://github.com/KirillKharlan)

___

* [**Vashchenko Artem**](https://github.com/VashchenkoArtem) — Teamlead
* [**Ovcharenko Yuliia**](https://github.com/JuliaOvcharenko)
* [**Safonova Anna**](https://github.com/AnnaSafonova30)
* [**Markov Dmitro**](https://github.com/DmitriyM08)
* [**Kharlan Kyrylo**](https://github.com/KirillKharlan)

## Посилання | Links

* ![](images_for_readme/figma.svg) [Фігма дизайн](https://www.figma.com/design/20TZphWNufeAQYOe7E1sze/%D0%A1%D0%BE%D1%86%D1%96%D0%B0%D0%BB%D1%8C%D0%BD%D0%B0-%D0%BC%D0%B5%D1%80%D0%B5%D0%B6%D0%B0-World-IT?node-id=6-26&p=f&t=bGAjDfyxAR23sLlY-0)

___

* ![](images_for_readme/figma.svg) [Figma design](https://www.figma.com/design/20TZphWNufeAQYOe7E1sze/%D0%A1%D0%BE%D1%86%D1%96%D0%B0%D0%BB%D1%8C%D0%BD%D0%B0-%D0%BC%D0%B5%D1%80%D0%B5%D0%B6%D0%B0-World-IT?node-id=6-26&p=f&t=bGAjDfyxAR23sLlY-0)



## Структура | Structure of the project

* ![](images_for_readme/figma.svg) [Фігджем структура проєкту](https://www.figma.com/board/KYEFp7dDKIrO5GBJwWNcF8/Social_network---Structure-of-the-project?node-id=0-1&t=cvBIJdu1IKlfONmC-1)

___


* ![](images_for_readme/figma.svg) [FigJam structure of the project](https://www.figma.com/board/KYEFp7dDKIrO5GBJwWNcF8/Social_network---Structure-of-the-project?node-id=0-1&t=cvBIJdu1IKlfONmC-1)


## Функціонал кожного з додатків | Functionality of each application

<details>
  <summary><strong>📁 chats</strong></summary>

  ---
  > 📁 chats – Додаток для чатінгу. У процесі розробки ми працювали з: django channels, web socets, з датами в форматі ico. Додаток корисний тим, що будь-який зареєстрований користувач має змогу створювати та використовувати групові або індивідуальні чати. 
  ---
  > 📁 chats  – Application for chating. During the development process we work with: django channels, web socets, and dates in iso-format. The application is useful because everyone can create or user group or individual chats. 
  ---
</details>

<details>
  <summary><strong>📁 friends</strong></summary>

  ---
  > 📁 friends – Сторінка друзів. У процесі розробки якої ми працювали із надсиланням запиту до друзів іншим користувачам, видаленням інших користувачів з друзів, відображенням ваших друзів та рекомендації вам нових друзів, для цього ми користовувалися такими класами відображення як: TemplateView та DeleteView. На якій відображаються користувачі які вжє є вашими друзями або можуть стати вашими друзями якщо ви їх додасте до своїх друзів.
  --- 
  > 📁 friends  – Friends page. During the process of development, we worked hard to ask friends to other friends, to other friends from friends, to the images of your friends and recommendations to you of new friends, for whom we used the following display classes: TemplateView and DeleteView. How do they appear to be your friends, or may they become your friends, and you will pass them on to your friends.
  ---
</details>

<details>
  <summary><strong>📁 main</strong></summary>

  ---
  > 📁 main – Головна сторінка проєкта  
    Це веб-застосунок із функціоналом створення, редагування та перегляду постів, з можливістю додавати зображення вручно (з комп’ютера локалько) чи за допомогою URL-адресою. Застосунок має сучасний інтерфейс із модальними формами, що зручно відкриваються/закриваються без перезавантаження сторінки. 
    * Основні можливості:
    - створювати публікації через інтерактивну форму;
    - переглядати вміст окремих блоків за допомогою кнопок «три крапки»;
    - редагувати вже створені пости: зʼявляється форма, яка автоматично підтягує дані через AJAX;
    - додавати зображення напряму з компʼютера або через поле введення URL-адрес.
    Під час відкриття модальних вікон основний контент затемнюється (ефект blur) для зручності користувача. Усі взаємодії та зміни в HTML-документі здійснюються за допомогою JavaScript, що дозволяє створювати зручний, динамічний і плавний інтерфейс користувача.

  ---
  > 📁 main  –  Project Main Page
  This is a web application with functionality for creating, editing, and viewing posts, allowing users to add images either manually (from a local computer) or via a URL. The app features a modern interface with modal forms that open and close smoothly without reloading the page.
  * Key features:
  - Create posts through an interactive form;
 - View content of individual blocks using the “three dots” buttons;

-Edit existing posts: a form appears that automatically loads data via AJAX;

-Add images directly from the computer or by entering a URL.

  When modal windows open, the main content is blurred for better user focus. All interactions and updates within the HTML document are handled using JavaScript, enabling a smooth, dynamic, and user-friendly interface.
  ---
</details>

<details>
  <summary><strong>📁 publications</strong></summary>

  ---
  > 📁 publications – Додаток для відображення та створення особистих постів користувача. На ньому ми працювали зі створенням посту, його редагуванням та видаленням. Використовували такі класи відображення, як: DeleteView, UpdateView, CreateView, LogoutView.
  ---
  > 📁 publications  – 
  ---
</details>

<details>
  <summary><strong>📁 registration</strong></summary>

  ---
  > 📁 registration – Сторінка реєстрації,яка дозволяє новим користувачам створити обліковий запис для доступу до функціоналу застосунку
  ---
  основний функціонал - Введення данних користувача:Пошта,пароль,підтвердження паролю
  ---
  
  > 📁 registration  – 
  ---
</details>

<details>
  <summary><strong>📁 settings_app</strong></summary>

  ---
  > 📁 settings_app – Додаток для налаштувань профілю користувача та для створення альбомів. 
  ---
  > 📁 settings_app  – Application for user profile settings and for creating albums
  ---
</details>

## Як встановити та запустити проєкт? | How to install and run the project?


> [!NOTE]
> Проєкт стабільно працює на Python 3.8 і вище. Для максимальної сумісності та стабільної роботи рекомендуємо використовувати останню доступну версію Python.
> 
> The project works well with Python 3.8 or higher. To be sure everything works correctly, we recommend using the latest version of Python.



<details>
  <summary><strong>
  
  ![](images_for_readme/windows.svg)
  Для Windows | For Windows</strong></summary>

  - 1️⃣ Завантажте та налаштуйте **Python**: Перейдіть на [офіційний сайт Python](https://www.python.org/), знайдіть вкладку ["Downloads"](https://www.python.org/downloads/) і завантажте версію Python відповідно до вашої операційної системи. Під час налаштування обов’язково оберіть опцію "Add python.exe to PATH".
  ___
  - 1️⃣ Download and install **Python**: Go to the [official Python website](https://www.python.org/), open the ["Downloads"](https://www.python.org/downloads/) tab, and download the Python version for your operating system. When installing, make sure to check the box that says "Add python.exe to PATH".

___
  
  ![](images_for_readme/python.jpg)
  ___

  - 2️⃣ Завантажте та налаштуйте **Git**: Перейдіть на [офіційний сайт Git](https://git-scm.com/) і завантажте версію Git відповідно до вашої операційної системи.

  ___

  - 2️⃣ Download and install **Git**: Go to the [official Git website](https://git-scm.com/) and download the version of Git for your operating system.

  ___

  - 3️⃣ Завантажте та налаштуйте **Visual Studio Code**: Перейдіть на [офіційний сайт Visual Studio Code](https://code.visualstudio.com/) 
  
  ___

  - 3️⃣ Download and install Visual Studio Code: Go to the [official Visual Studio Code website](https://code.visualstudio.com/) and download the version for your operating system.

  ___

  - 4️⃣ Відкрийте Visual Studio Code, створіть або відкрийте необхідну папку в якій буде знаходитися проєкт.
  ___

  - 4️⃣ Open Visual Studio Code, then create or open the folder where your project will be.
  
    - Відкрийте термінал, оберіть "Git Bash"
  
    - Open the terminal and choose "Git Bash"
  
    ![](images_for_readme/bash.jpg)
    ___

    - Скопіюйте команду у відкритий термінал:
  
    - Copy the command into the open terminal:
  
      ```sh
      git clone https://github.com/VashchenkoArtem/social_network.git
      ```
    - Створіть віртуальне оточення та активуйте його
    ___

    - Create a virtual environment and activate it

      ```sh
      python -m venv <namevenv>
      ```

      ```sh
      .\<namevenv>\Scripts\activate.bat
      ```

    - Встановіть необхідні бібліотеки в віртуальне оточення з файлу requirements.txt
      
    ___

    - Install the required libraries into the virtual environment from the requirements.txt file

      ```sh
      pip install -r requirements.txt
      ```
    - Перейдіть у папку social_network, в якій знаходиться файл manage.py якщо ви не там

    ___

    - Go to the folder social_network where the manage.py file is, if you are not there yet
  

      ```sh
      cd social_network
      ```

        ```sh
      cd social_network
      ```

    - Проведіть міграції
    ___

    - Run the migrations
  
      ```sh
      python manage.py migrate
      ```

    - Запустіть сервер
    ___
    - Run the project
  
      ```sh
      python manage.py runserver
      ```
  - 5️⃣ Вітаємо! Ви локально запустили проєкт!
  ___
  - 5️⃣ Congratulations! You have successfully run the project locally!
</details>


<details>
  <summary><strong>
  
  ![](images_for_readme/macos.svg)
  Для MacOS | For MacOS</strong></summary>


  - 1️⃣ Завантажте та налаштуйте **Python**: Перейдіть на [офіційний сайт Python](https://www.python.org/), знайдіть вкладку ["Downloads"](https://www.python.org/downloads/) і завантажте версію Python відповідно до вашої операційної системи. Під час налаштування обов’язково оберіть опцію "Add python.exe to PATH".
  ___
  - 1️⃣ Download and install **Python**: Go to the [official Python website](https://www.python.org/), open the ["Downloads"](https://www.python.org/downloads/) tab, and download the Python version for your operating system. When installing, make sure to check the box that says "Add python.exe to PATH".

___
  
  ![](images_for_readme/python.jpg)
  ___

  - 2️⃣ Завантажте та налаштуйте **Git**: Перейдіть на [офіційний сайт Git](https://git-scm.com/) і завантажте версію Git відповідно до вашої операційної системи.

  ___

  - 2️⃣ Download and install **Git**: Go to the [official Git website](https://git-scm.com/) and download the version of Git for your operating system.

  ___

  - 3️⃣ Завантажте та налаштуйте **Visual Studio Code**: Перейдіть на [офіційний сайт Visual Studio Code](https://code.visualstudio.com/) 
  
  ___

  - 3️⃣ Download and install Visual Studio Code: Go to the [official Visual Studio Code website](https://code.visualstudio.com/) and download the version for your operating system.

  ___

  - 4️⃣ Відкрийте Visual Studio Code, створіть або відкрийте необхідну папку в якій буде знаходитися проєкт.
  ___

  - 4️⃣ Open Visual Studio Code, then create or open the folder where your project will be.
  
    - Відкрийте термінал, оберіть "Git Bash"
    - 
    - Open the terminal and choose "Git Bash"
  
    ![](images_for_readme/bash.jpg)
    ___

    - Скопіюйте команду у відкритий термінал:
  
    - Copy the command into the open terminal:

    ```sh
      git clone https://github.com/VashchenkoArtem/social_network.git
    ```
    - Створіть віртуальне оточення та активуйте його
    ___

    - Create a virtual environment and activate it

      ```sh
      python3 -m venv <namevenv>
      ```

      ```sh
      source <namevenv>/bin/activate
      ```

    - Встановіть необхідні бібліотеки в віртуальне оточення з файлу requirements.txt
      
    ___

    - Install the required libraries into the virtual environment from the requirements.txt file

      ```sh
      pip install -r requirements.txt
      ```
    - Перейдіть у папку social_network, в якій знаходиться файл manage.py якщо ви не там

    ___

    - Go to the folder social_network where the manage.py file is, if you are not there yet
  

      ```sh
      cd social_network
      ```

        ```sh
      cd social_network
      ```

    - Проведіть міграції
    ___

    - Run the migrations
  
      ```sh
      python3 manage.py migrate
      ```

    - Запустіть сервер
    ___
    - Run the project
  
      ```sh
      python3 manage.py runserver
      ```
    ___

    - Натисніть на посилання

    ___

    - Click on link
  
  - 5️⃣ Вітаємо! Ви локально запустили проєкт!
  ___
  - 5️⃣ Congratulations! You have successfully run the project locally!
</details>

___

### Висновок | Conclusion 
📱 Проєкт social_network — проєкт, який навчив нас злагодженій роботі у команді та став важливим етапом у поглибленному вивченні Django. 
У процессі розробки ми:
- Застосовували Django Forms, Class-Based Views, Django Channels для роботи з вебсокетами.
- Реалізували Ajax-запити та попрацювали з форматуванням дат у ISO-формат.
- Познайомилися з поняттями реляційних і нереляційних баз даних, використовуючи:

  - ![](images_for_readme/database.svg) SQLite — для локальної розробки.
  - ![](images_for_readme/database.svg) MySQL — для глобального використання.
  
  ___

- ![](images_for_readme/figma.svg) Окрему увагу було приділено втіленню дизайнерських ідей — важлива навичка frontend-розробки.
  - Верстання з використанням функції calc() та одиниць виміру vw / vh
  - Адаптивний дизайн, максимально наближений до запропонованого макету.

- 🤝 Командна робота
  - Для забезпечення ефективної та комфортної роботи у команді ми дотримувалися таких принципів:

  - 🔧 Чіткий розподіл задач — кожен учасник відповідав за свій функціонал згідно з розподілом, наданим Team Lead.
  - 📞 Регулярна комунікація — обговорення у відео-чаті загальних проблем написаного коду та його функціоналу, видача тімлідом задач для участників групи. Зустрічі відбувалися щонайменше двічі на тиждень.

  - 🌐 Робота з Git — Усі учасники активно використовували систему контролю версій: створення гілок, злиття, зберігання коду.

  - 🌐 Робота з Github — кожен учасник має власну гілку на [гітхаб-репозиторії](https://github.com/VashchenkoArtem/social_network), виконуючи завдання.
  
- 🛠️ Використані технології
  - У процесі розробки були використані такі технології та інструменти:
  - Python – Основна мова програмування, на якій реалізована серверна логіка проєкту.
  
  - Django — Python фреймворк для швидкої та безпечної розробки веб-додатків. 
  
  - JavaScript — Мова програмування для створення функціоналу, інтерактивності та "краси" на стороні користувача.
  
  - HTML — Мова-конструктор, на якому побудована структура всіх веб-сторінок проекту.
  
  - CSS – Мова, яка відповідає за зовнішній вигляд сторінок: кольори, шрифти, розміщення елементів і «косметичний» функціонал.
  
  - jQuery — JavaScript-бібліотека, яка має спрощені методи для роботи з Ajax.
  
  - SQLite – Реляційна база даних для локальної роботи.
  
  - MySQL — Реляційна база даних для віддаленої роботи.
  
  - Git – Система контролю версій	для відстеження змін у коді.
  
  - GitHub — Онлайн-платформа для збереження Git-проєктів та спільної роботи, публікації, обговорення коду.
  
  - [Figma](https://www.figma.com/design/20TZphWNufeAQYOe7E1sze/%D0%A1%D0%BE%D1%86%D1%96%D0%B0%D0%BB%D1%8C%D0%BD%D0%B0-%D0%BC%D0%B5%D1%80%D0%B5%D0%B6%D0%B0-World-IT?node-id=6-26&p=f&t=bGAjDfyxAR23sLlY-0)
  
  - Markdowm — легка, але обмежена мова розмітки, яка дозволяє швидко оформлювати текст: робити заголовки, списки, виділення, вставляти зображення чи посилання. Команда використовувала для написання README.md.


🎯 Завершивши цей проєкт, ми отримали досвід, пов'язаний із покращенням нововивчених складових модуля Django: Django Forms, Class-Based Views, Django Channels для роботи з веб-сокетами, а також використання Ajax і робота з форматуванням дат у iso-формат. Ми отримали навички злагодженної командної роботи, підготовали веб-застосунок до використання з n-кількістю реальних користувачів. Також наша команда дізналася як працювати із віддаленими базами даних на прикладі MySQL. 

⚠️ Труднощі розробки:
- Неправильний розподіл свого часу — проєкт розроблявся наприкінці навчального року, під час контрольних та тестів | виділення на дипломний проєкт 1,5 місяці.
- Проблеми з роботою дат у iso-форматі.
  
___



📱 Project "social_network"
The social_network project helped us learn how to work together as a team. It was an important step in learning more about Django.

During the project, we:
  - Used Django Forms, Class-Based Views, and Django Channels to work with WebSockets.

  - Used Ajax requests and worked with ISO date format.

  - Learned about relational and non-relational databases:

    - ![](images_for_readme/database.svg) SQLite – for local work.

    - ![](images_for_readme/database.svg) MySQL – for global use.

![](images_for_readme/figma.svg) Design
  - We paid special attention to design ideas — this is an important skill for frontend development.
  - We used:

    - The calc() function and CSS units like vw, vh.
  - Responsive design to make the site look good on all screens.

🤝 Teamwork
We worked as a team. To do this, we:

  - 🔧 Shared the tasks — each person had their part of the project.

  - 📞 Talked often — we had video calls at least two times a week.

  - 🌐 Used Git — we created branches, saved our work, and worked together.

  - 🌐 Used GitHub — each person had their own branch in the GitHub repository.
  
🛠️ Used Technologies

  - During the development, the following technologies and tools were used:

  - Python – The main programming language used for the project’s backend logic.

  - Django – A Python framework for fast and secure web application development.

  - JavaScript – A programming language used to create functionality, interactivity, and "beauty" on the user’s side.

  - HTML – A markup language that builds the structure of all web pages in the project.

  - CSS – A language that controls the look of pages: colors, fonts, layout, and cosmetic functions.

  - jQuery – A JavaScript library that makes working with Ajax easier.

  - SQLite – A relational database for local work.

  - MySQL – A relational database for remote work.

  - Git – A version control system to track changes in the code.

  - GitHub – An online platform to store Git projects, work together, publish, and discuss code.

  - Figma – A design tool used by the team for creating UI and layouts.

  - Markdown – A simple but limited markup language that helps quickly format text: create headings, lists, highlights, insert images or links. The team used it for writing the README.md file.


🎯 What We Learned
After this project:

  - We know more about Django: Django Forms, Class-Based Views, WebSockets, Ajax, and date formats.

  - We know how to work in a team and build a web app for real users.

  - We learned how to use remote databases like MySQL.

⚠️ Challenges
  - Time management — the project was during the school year — all teammate had exams. | We had only 1.5 months to finish it.
  - There were problems with ISO date format.
