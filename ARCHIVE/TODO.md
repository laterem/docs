# В разработке / планы на будущее

### Спринт на 23.02.23

- [x] CSV загрузка пользователей
  - [x] ФРОНТ `Зарезервировано: Жура`
  - [x] БЭК `Зарезервировано: Спайд`
- [x] Справка по LTC `Зарезервировано: Спайд`
- [ ] Полировка
  - [x] Исправление ошибок 500 `Зарезервировано: Спайд`
  - [x] Убрать описание групп `Зарезервировано: Жура`
  - [ ] CRUD полнота
    - [x] Починить изменение пользователей `Зарезервировано: Жура`
    - [ ] Добавить изменение названий шаблонов задач
      - [ ] ФРОНТ `Зарезервировано: Жура`
      - [ ] БЭК `Зарезервировано: Спайд`
    - [x] Реализовать удаление работ и категорий `Зарезервировано: Спайд`
    - [x] Реализовать удаление групп `Зарезервировано: Спайд`
  - [x] Исправление ошибки с .0 `Зарезервировано: Спайд`
  - [x] Убрать кнопку "импорт" из страницы работ `Зарезервировано: Жура`
  - [ ] Изменить редактирование заголовков (кнопка "Отменить изменения" и подтверждение по событию ввода) `Зарезервировано: Жура`
- [ ] Коллаб с Егором
- [x] Форма багрепортов `Зарезервировано: Жура`
  - [ ] Прикрепление скриншотов
- [ ] Добавить возможность прикреплять файлы к задачам
- [ ] Сообщение об ошибках логина `Зарезервировано: Жура, Спайд`

***

### Сайт

- [ ] Добавить варнинги
  - [ ] Работа без заданий
  - [ ] Несоответствие LTC и HTML | Ошибки компиляции LTC

- [ ] Панель управления учителя:
  - Окно взаимодействия с базой учеников
    - [ ] Дополнительный функционал: пакетная загрузка CSV файла с пользователями
      - [ ] ФРОНТ
        - [ ] ЗАЩИТА ОТ ДУРАКА
      - [ ] БЭК
        - [ ] ЗАЩИТА ОТ ДУРАКА
    - [ ] Изменение учеников
      - [ ] ФРОНТ
      - [ ] БЭК
    - [ ] Назначение работ ученикам
      - [ ] ФРОНТ
      - [ ] БЭК
  - Окно взаимодействия с группами учеников
    - [ ] Настройка прав пользователям групп
      - [ ] ФРОНТ
      - [ ] БЭК
  - Окно взаимодействия с работами
    - [ ] Редактирование работ
      - [ ] Смена порядка задач в работах
        - [ ] ФРОНТ
        - [ ] БЭК
      - [ ] Изменение задач в работах
        - [ ] ФРОНТ
        - [ ] БЭК

- [ ] Сделать защиту от дурака
  - [x] Сделать выпадающие списки в энумо-подобных полях (выбор пользователей, выбор типа задачи и т.д.)
  - [ ] Добавить окна "Вы уверены?" в ответ на запрос удаления сущностей

- [ ] Добавить закладки на задачах - пометка приоритета выполнения
- [ ] Сделать подсказки при наведении на кнопки
- [ ] Сделать сохранение состояний дерева
- [ ] Кнопка закрытия всплывающего окна (который с blackout'ом)
- [ ] Вставить нужные иконки
- [ ] Просмотр файлов задачи (CRUD-полнота)
- [ ] Возможность дублирования и редактирования типов
- [ ] Редактирование задач на сайте

## Система данных

- [ ] Разграничить права на сущности между учителями

## Глобальные задания

- [ ] Переделать систему определения доступности работы
- [ ] Учитель должен видеть лог авторизации

### Рефакторинг

- [ ] Переписать весь используемый в проекте функционал модуля os.path под pathlib `Свободно`
- [ ] Переписать все рекурсивные функции под использование стэка

### Движок задач (Основной ответственный - Спайд)

- [ ] Перегрузка функций
- [ ] Арифметика
- [ ] Перегрузка операторов парсинга по арности операций (бинарный и унарный минус это один символ)
- [ ] Синтаксический сахар для систем счисления?
- [ ] Исправить ошибки связанные с запрещаторами в LTC
- [ ] Добавить переопределение установки вердикта в LTC (?)
- [ ] Добавить включения (наследования) в LTC
- [ ] Генерация картинок задачей

### Состояния

- [ ] danger.md - Есть неисправленные уязвимости.

- [ ] structure.md - Неактуален `Ответственный: Жура`
- [x] secret_data.py - Up to date `Ответственный: Жура`
- [x] LTCCompiler.compile - Up to date `Ответственный: Спайд`
- [ ] LTCCompiler.compile_alt - Неактуален `Ответственный: Спайд`

***

### Надумки на далекое светлое будущее со свободным временем

- [ ] Задачи в которых ученик должен что-то себе скачать (пример, программу, схему и тп)
- [ ] Сделать конструктор задач (С интерфейсиком, автоматической подкачкой в нужную дирректорию)
- [ ] Внедрение старых обучающих проектов кафедры на сайт
- [ ] С внешней проверкой (Ответы отправляются учителю, а он отправляет вердикт)
- [ ] Интерактивные задачи (Например, соединение элементов)
- [ ] Цветные темы
- [ ] Сделать диаграмму архитектуры проекта?
- [ ] Трекеры времени
- [ ] Разграничение прав учителей

***

## Архив

- [x] Убедиться, что сессии не хранятся у клиентов и DTCJsonы не находятся в кукизах. `Сделано: Спайд`
- [x] Сделать README.md `Сделано: Жура Скорректировано: Спайд`
- [x] Изучить вопрос абсолютных путей к шаблонам `Сделано: Спайд`
- [x] Сделать quickrun.bash с зависимостью от ОС `Сделано: Жура`
- [x] Добавить обработку исключений `Сделано: Спайд`
- [x] Подчистить ненужную отладку `Сделано: Спайд`
- [x] Исправить проблему неотсортированности директории по алфавиту в rdir_to_tree `Сделано: Спайд`
- [x] Комбобокс -> несколько кнопок в странице выбора задач `Сделано: Жура`
  - [x] Исправить баг с нечисловыми названиями заданий (в идеале перейти на систему ID и разделить отображаемое название и программный идентификатор) `Сделано: Жура`
- [x] Объединить задания в сессии в словарь `Сделано: Спайд`
- [x] Выделить хост для защиты
- [x] БД система, поддерживающая сущности данных, описанных выше `Сделано: Спайд`
- [x] Переписать _submenu
  - [x] убрать path
- [x] Сделать так, чтобы Джанго дополнял view.html общими строками `Сделано: Жура`
- [x] Добавить обработку исключений. (Список известных "невозможных" действий можно посмотреть в danger.md)

### Бренд и косметика

- [x] Переименовать всё с DEW на Laterem `Сделано: Спайд`
- [x] Изменить размеры svg `Сделано: Спайд`
- [x] ~~Перевести фронт в формат table~~ (или как-то по другому расстолбить сайт) `Сделано: Жура`
- [x] Настроить фавиконы `Сделано: Жура`
- [x] Вынести основные цвета сайта в отдельный файл  `Сделано: Спайд`
- [x] Улучшить качество изображения svg `Сделано: Жура`

### Движок задач

- [x] Добавить тип данных списка `Сделано: Спайд`
  - [x] Исправить баги с парсингом списка `Сделано: Спайд`
  - [x] Добавить вложенные списки? (списки->множества->кортежи->списки) `Сделано: Спайд`
- [x] Установить стиль B по умолчанию. Сделать возможность переключения на стиль A в заголовке DTC. `Сделано: Спайд`
- [x] Желательно сделать ООП структуру работы с самими задачами (пакетами config.dtc + view.html). Условно чтобы можно было создать объект Task(путь к пакету) и из него легко добывать всё необходимое `Сделано: Спайд`
- [x] Сделать нормальную проверку задач с чек боксами (сейчас работает только для задач с одним ответом) `Сделано: Спайд`
- [x] Добавить поддержку одинарных кавычек для скобок `Зарезервировано: Спайд`
- [x] Добавить обработку исключений `Сделано: Спайд`
- [x] Нормальная индексация форм как полей для DTC вместо одного захардкоженного answer `Сделано: Жура`
- [x] Поддержка ассетов в задачах, ~~динамическая подгрузка и выгрузка ассетов из статика~~ `Зарезервировано: Спайд(?)`
- [x] Понапридумывать встроенных LTC-функций проверки и генератора значений `Каждый из команды, когда скучно.`
- [x] Добавить возможность чтения данных ввода в LTC
- [x] Instance-unique поля
- [x] Сохранение HTML шаблонов задач сразу в static_copies без посредника через data/tasks.
- [x] Добавить запрещаторы в LTC `Сделано: Спайд`
- [ ] ~~Переработка системы отслеживания изменений задач и автоматического обновления кэшируемых данных при таковых~~

### Рефакторинг

- [x] Почистить tasks.py до его полного удаления. Не оставить ни следа ООП структуре, это рудимент и его нам не надо `Сделано: Жура`
- [x] Устроить глобальную переименовальню, как минимум чтобы oop_taskengine имел адекватное название `Сделано: Жура, Спайд`
- [x] Вывести settings.py из gitignore и сделать внутри него подгрузку секретных ключей из какого-нибудь негитуемого файла `Сделано: Жура`
- [x] Глобальная переименовальня `Сделано: Спайд`
- [x] Переделать систему наименования метадокументов о проекте. `Сделано: Спайд`

### Сайт

- [x] Расхардкодить button1 `Сделано: Жура`
- [x] Починить левое меню `Сделано: Жура`
- [x] Кнопка перехода на следующую незелёную задачу в работе `Сделано: Жура`
- [x] Переделать систему очистки request.sessions
- [x] Сделать выбор темы отдельной открывающейся менюшкой (например, список тем, в котором подсвечена выбранная тема)
- [x] Сделать базовую страницу
- [x] Шаблоны под все возможные типы задач, от которых можно отталкиваться при составлении новых
- [x] Скачивание шаблона с его страницы
- [x] Просмотр шаблонов задач на сайте
  - [x] Просмотр документов прямо на сайте
  - [x] Возможность скачать файлы
- [x] Сделать страницу профиля пользователя
  - [x] ФРОНТ
  - [x] БЭК
- Панель управления учителя:
  - [x] Окно взаимодействия с базой учеников
    - Добавление учеников
      - [x] Ручная запись
        - [x] ФРОНТ
        - [x] БЭК
    - [x] Удаление учеников
      - [x] ФРОНТ
      - [x] БЭК
  - [x] Окно взаимодействия с группами учеников
    - [x] Добавление групп
      - [x] ФРОНТ
      - [x] БЭК
    - [x] Изменение групп
      - [x] Добавление и удаление пользователей группы
        - [x] ФРОНТ
          - [x] ЗАЩИТА ОТ ДУРАКА
        - [x] БЭК
    - [x] Назначение работ группам
      - [x] ФРОНТ
      - [x] БЭК
    - [x] Удаление групп
      - [x] ФРОНТ
      - [x] БЭК
  - [x] Окно мониторинга результатов учеников
    - [x] ФРОНТ
    - [x] БЭК
  - [x] Окно взаимодействия с работами
    - [x] Добавление категорий работ
      - [x] ФРОНТ
      - [x] БЭК
    - [x] Изменение категорий
      - [x] Добавление работ в категории
        - [x] ФРОНТ
        - [x] БЭК
      - [x] Удаление работ из категорий
        - [x] ФРОНТ
        - [x] БЭК
    - [x] Удаление категорий
      - [x] ФРОНТ
      - [x] БЭК
    - [x] Добавление подкатегорий в категории
      - [x] ФРОНТ
      - [x] БЭК
    - [x] Добавление работ
      - [x] ФРОНТ
      - [x] БЭК
    - Редактирование работ
      - [x] Добавление задач в работы
        - [x] ФРОНТ
          - [x] ЗАЩИТА ОТ ДУРАКА
        - [x] БЭК
      - [x] Удаление задач в работах
        - [x] ФРОНТ
        - [x] БЭК
    - [x] Удаление работ
      - [x] ФРОНТ
      - [x] БЭК

### Система данных

- [x] Отказаться от data/works и data/userdata
  - [x] Автоматизировать регистрацию админ-пользователя при пустой БД

### Спринт на 14.02.23

- [x] Дока по функциям LTC `Зарезервировано: Спайд`
- [x] Демонстрация ответов учителю `Сделано: Жура, Спайд`

### Спринт на 06.02.23

- [x] LTC Для работы с булевыми формулами `Зарезервировано: Спайд`
- [x] Задания ЦЭ
  - [x] Соединение стрелочками `Сделано: Жура`
- [ ] ~~Кнопка чтобы бд соответствовала директории~~
- [x] Функционал удаления заданий `Сделано: Спайд`

## Спринт 10.11.2022

- [x] Добавить примеры задач для демонстрации
  - [x] Задачки по другим предметам (Математика, Физика)
    - [x] Задачки с картинками
      - [x] Внедрить картинки в задачи
  - [x] Генирируемые задачи
- [x] Сделать красивое оформление сайта для демонстрации
  - [x] Лого
  - [x] Название
  - [x] Дизайн страниц
    - [x] Нормальное дерево работ `Сделано: Жура`
    - [x] Сделать минимальную высоту меню дерева на всю страницу `Сделано: Жура`
    - [x] Цвета, шрифты и т.д.
    - [x] Навигация по задачам в работе `Сделано: Жура`
- [x] Подготовка к промежуточной защите
  - [x] Составление презентации
    - [x] Сама презентация (pptx)
    - [x] Текст доклада
      - [x] Понять, как нормально разделить доклад на двоих
  - [x] Причесать программу (только то что будет показано)
    - [x] Спрятать костыли `Сделано вроде`

Опционально

- [x] Система пользователей `Сделано: Спайд`
  - [x] Хранение прогресса по задачам `Сделано: Спайд`
  - [x] Логин-Пароль в файле `Сделано: Спайд`

- [x] Сделать возможность менять дерево работ без перезапуска сервера `Сделано: Жура; Переписано: Спайд`
  - [x] Передавать в html - файл базовой разметки html-код дерева заданий ученика `Сделано: Жура; Переписано: Спайд`
  - [x] Хранить личные особенности дерева заданий ученика (выполненные/недоступные задания и т.п.) `Сделано: Жура; Переписано: Спайд`

## Спринт 27.10.2022

- [x] Уникальная индексация задач и обсидианизация поиска имён задач `Сделано: Спайд`
- [x] Категории работ: Категория предмета, подкатегория темы, объект работы.
        В одной папке могут быть либо только файлы работ, либо только подкатегории.
  - [x] Убрать глобальную переменную с древом работ `Сделано: Жура`
  - [x] Страницы/__панель__ навигации соответствующие категории. Отдельная страница для работы `Сделано: Жура`
  - [x] Предзагрузка структуры директории работ `Сделано: Спайд`

## Спринт 20.10.2022

- [x] Сделать так, чтобы фактор рандома в DTC не влиял на то, что задача перегенерируется при каждом запросе (включая GET и POST. из-за этого нельзя проверить одну и ту же задачу) (решается через кэширование(?) задач, но надо понять как это делать) (Сохранение сессий) (Покопаться в джанге - там всё есть) `Сделано: Жура`
  - [x] Разобраться с cookie `Сделано: Жура`
  - [x] Сделать класс DTCTask JSON serializable `Сделано: Спайд`
  - [x] Поменять систему ключей с названия задачи на название задачи + соль. `Сделано: Жура`
  - [x] Наладить систему очистки request.session `Сделано: Спайд`
- [x] Задачи с чек-боксами. (Может быть радио-боксы, дроп-боксы, картинки и т.д.) `Свободно`
  - [x] Поддержка чек-боксов. `Сделано: Жура`
    - [x] Поддержка ~~кортежей множеств~~ списков (для checkbox) в dtc `Сделано: Спайд`
    - [x] Кликабельная кнопка чекбокса `Сделано: Жура`

## Спринт 13.10.2022

- [x] Сделать текстовый формат конфигурации задач. `Сделано: Спайд`
  - [x] Связать формат с сайтом. `Сделано: Жура`

## Спринт 06.10.2022

- [x] Сделать оболочку для сайта. `Сделано: Жура`
- [x] Разместить на сайте 3 примера задач. `Сделано: Спайд, Жура`

## Спринт 29.09.2022

- [x] Классифицировать задачи из архива ЦЭ `Сделано: Жура, Спайд`