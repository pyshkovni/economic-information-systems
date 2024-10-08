# Работа с клиентской базой в Bitrix24

## Клиентская база в Bitrix24

1. Основные элементы клиентской базы 
   - **Контакты**: физические лица (сотрудники компаний или потребители).
   - **Компании**: юридические лица (поставщики, подрядчики, клиенты).
   - К сделкам можно привязывать несколько контактов и компаний, а также связывать контакты с компаниями (например, указать сотрудников компании).

2. **Добавление контактов и компаний**:
   - Для добавления новых данных используются кнопки **«Добавить контакт»** и **«Добавить компанию»**.
   - При добавлении заполняются поля, которые можно настраивать в зависимости от особенностей бизнеса.
     - Пример: для школы английского языка важно указать уровень ученика (Beginner, Intermediate и т.д.).
   - Настройка полей помогает позже фильтровать контакты и компании по нужным критериям.

3. **Сегментация клиентской базы**:
   - Со временем количество контактов и компаний увеличивается, поэтому сегментация становится важным инструментом.
   - Фильтрация по нужным параметрам (например, по видам клиентов, как водители для логистической компании или подрядчики для пекарни) помогает эффективно управлять базой.

## **Настройка карточки клиента**

   - В карточке отображается:
     - Основное меню (сверху) — для выполнения действий.
     - Слева — сделки и поля для заполнения информации о клиенте.
     - Справа — история взаимодействий (звонки, заметки, комментарии, задачи по звонкам, встречам, письмам).

1. **Настройка и заполнение полей**

   - Для заполнения информации создаются различные типы полей.
   - Примеры типов полей:
     - Строка: для ввода текста (например, имя собаки клиента).
     - Список: выбор из заранее заданных вариантов (например, сфера деятельности — транспорт, банки, IT и т.д.).
     - Даты и время: для указания значимых дат (дата рождения клиента, дата подписания договора).
     - Бронирование ресурсов: для управления доступом к ресурсам (например, бронирование стула в салоне).
     - Адрес: отображение адреса на карте.
     - Ссылка: хранение ссылок на сайт, социальные сети клиента.
     - Файлы: возможность прикреплять документы (шаблоны договоров, презентации и т.д.).
     - Деньги: для учета сумм (сколько клиент заплатил, затраты на обслуживание).
     - Чекбокс (да/нет): для указания факта (например, проведена ли встреча).
     - Число: для ввода числовых значений.
     - Привязка к контактам: например, привязка к базе водителей.

2. **Применение и сегментация клиентов**:
   - После настройки полей можно сегментировать клиентов по различным критериям:
     - Выбор клиентов из определенной сферы (логистика, IT и т.д.).
     - Отправка рассылок или работа с клиентами по определённым характеристикам (например, владельцы собак).
   - Это помогает оптимизировать работу менеджеров, фокусируя их на наиболее перспективных клиентах, что способствует увеличению продаж.

3. **Заключение**:
   - Использование полей в Bitrix24 позволяет детализировать информацию о клиентах, улучшить сегментацию, автоматизировать взаимодействие и повысить эффективность работы с клиентами.

## Интеграции контакт-центра

**Основные каналы связи, доступные для интеграции**:
   - **Email**: Возможность подключить электронную почту для получения и обработки сообщений от клиентов.
   - **IP-телефония**: Система телефонии, интегрируемая с Bitrix24.
   - **Call-трекинг**: Следит за источником звонков с рекламных кампаний и фиксирует их в системе.
   - **Виджеты и формы на сайт**: Позволяют интегрировать формы для заявок с сайта напрямую в Bitrix24.
   - **Социальные сети и мессенджеры**:
     - **ВКонтакте**: Интеграция позволяет собирать заявки из рекламы в этих социальных сетях.
     - **Онлайн-чат на сайте**: Возможность вести общение с клиентами через чат, размещенный на сайте компании.

### IP-телефония

1. **Что такое IP-телефония?**  
   - IP-телефония — это система телефонии, которая работает через интернет, а не через традиционные сим-карты.
   - Звонки осуществляются через специальные программы (софтфоны) на компьютерах или телефонах. Пример: операторы колл-центров, которые разговаривают через интернет.

2. **Зачем подключать IP-телефонию к Bitrix24?**  
   - **Фиксация звонков**: Каждый входящий и исходящий звонок фиксируется в CRM, что помогает автоматизировать процесс обработки лидов.
   - **Запись разговоров**: Все звонки сохраняются в карточке клиента, что позволяет менеджерам и руководителям анализировать качество взаимодействия и использовать записи в спорных ситуациях.
   - **Статистика звонков**: Руководители могут отслеживать продолжительность звонков, количество разговоров и оценивать производительность сотрудников.

3. **Способы подключения IP-телефонии к Bitrix24**:
   - **Аренда номера у Bitrix24**:
     - Самый простой способ — арендовать номер у официального провайдера Bitrix24.
     - Процесс подключения включает в себя заполнение заявки на аренду номера и его интеграцию с Bitrix24.
   - **Подключение существующей АТС (офисной или виртуальной)**:
     - Если у компании уже есть собственная телефонная станция (АТС), её можно подключить через SIP-коннектор (офисная или облачная СИП АТС).
     - Требуется техническая помощь специалистов для настройки логина, пароля и адреса сервера, а также оплата модуля (примерно 5000 тенге в месяц).
   - **Подключение сторонних приложений**:
     - Bitrix24 поддерживает интеграцию с более чем 130 сторонними решениями для IP-телефонии.
     - Эти решения можно найти в разделе «Телефония» в Bitrix24 Marketplace, выбрать по отзывам, цене и качеству, и подключить к CRM.

4. **Основные компоненты для работы с IP-телефонией в Bitrix24**:
   - **SIP-номер**: Номер телефона, который предоставляет оператор IP-телефонии.
   - **АТС (автоматическая телефонная станция)**: Офисное или облачное решение, которое подключает телефонную сеть к CRM.
   - **CRM Bitrix24**: Место, где происходит фиксация всех звонков и взаимодействий с клиентами.

5. **Пример работы IP-телефонии с Bitrix24**:
   - При входящем звонке IP-телефония фиксирует новый лид или сделку в CRM.
   - Автоматически открывается карточка клиента с записью звонка, номером телефона и информацией о контакте.
   - Менеджер может уточнить имя клиента, внести дополнительные данные и продолжить работу с ним в CRM.

6. **Преимущества использования IP-телефонии с Bitrix24**:
   - Автоматизация процесса обработки звонков и лидов.
   - Возможность контролировать работу сотрудников и улучшать клиентский сервис за счет сохранения записей разговоров.
   - Улучшенная аналитика и статистика по звонкам для более эффективного управления ресурсами компании.

### Мессенджеры

1. **WhatsApp и другие мессенджеры**:
   - На текущий момент WhatsApp не может быть бесплатно интегрирован на территории СНГ через Bitrix24. Однако можно арендовать номера из других стран или использовать сторонние решения для интеграции.
   - **Viber** и **Telegram** можно интегрировать через стандартные функции Bitrix24, что позволяет также обрабатывать сообщения и заявки через мессенджеры.

2. **Работа с интегрированными мессенджерами**:
   - После подключения мессенджеров можно настроить автоматическое распределение сообщений между менеджерами или работать с клиентами по очереди.
   - Вся история переписки и взаимодействий с клиентами сохраняется в карточке лида, что упрощает обработку заявок и взаимодействие с клиентами напрямую из Bitrix24.

3. **Процесс подключения Telegram-бота к Bitrix24**:
   a. Создание бота (если его нет)
      - Зайти в контакт-центр Bitrix24
      - Выбрать пункт Telegram
      - В Telegram найти @BotFather
      - Следовать инструкциям BotFather для создания бота
        * Использовать команду /newbot
        * Выбрать название бота
        * Задать username для бота
        * Получить токен (ключ) для интеграции
   b. Подключение бота к Bitrix24
      - Ввести полученный токен в настройках Bitrix24
      - Создание канала и подключение к Bitrix24
   c. Работа с обращениями в Bitrix24
      - Раздел "Открытые линии" для просмотра сообщений
      - Возможность завершения диалога
      - Перевод неуспешных сделок в соответствующий статус
   d. Пример использования
      - Клиент пишет боту "Добрый день"
      - Сообщение появляется в Bitrix24
      - Менеджер отвечает клиенту через интерфейс Bitrix24

### Интеграция Bitrix24 с сайтом

1. **Цель интеграции сайта с Bitrix24**:
   - Когда клиент заходит на ваш сайт (например, из рекламы или поиска), важно, чтобы он мог быстро и удобно связаться с компанией.
   - Публикация на сайте телефона или email не всегда эффективна — лучше использовать CRM-формы и виджеты, которые помогают клиентам оставить свои данные для обратной связи.

2. **CRM-формы и виджеты**:
   - **CRM-форма**: Это форма, которую клиенты заполняют на сайте для связи с компанией. Когда клиент заполняет форму, данные автоматически попадают в CRM-систему Bitrix24, где их можно обрабатывать.
   - **Онлайн-чат**: Через него клиенты могут задавать вопросы в режиме реального времени, а сотрудники компании — отвечать на них прямо из Bitrix24.

3. **Что такое виджет на сайт**:
   - Виджет — это элемент на сайте (обычно внизу экрана), который предлагает клиентам начать общение с компанией через чат или оставить заявку на обратный звонок.
   - Помимо чата, через виджет можно также заполнить форму обратной связи или заказать обратный звонок.

### Настройка CRM-форм в Bitrix24

   - Для создания и настройки CRM-формы необходимо зайти в раздел **CRM** > **Еще** > **CRM-формы**.
   - В Bitrix24 уже есть предустановленные формы, которые можно редактировать или создавать новые.
   - После выбора формы (например, формы обратной связи) можно редактировать ее внешний вид и поля.

    a. **Настройка полей CRM-формы**:
    - Поля формы можно настраивать в зависимости от нужд бизнеса. Например:
        - Добавить поля, такие как должность клиента или его сайт.
        - Убрать ненужные поля (например, email, если он не требуется).
        - Обязательно включать поле **соглашение о сборе персональных данных** — это важное требование для работы с клиентами.

    b. **Сущности CRM и обработка данных**:
    - После того, как клиент заполнил CRM-форму, важно указать, как данные будут обрабатываться:
        - Можно создать **сделку + клиента**.
        - Если клиент уже есть в базе данных, форма будет прикреплена к существующему профилю клиента.

    c. **Настройка заголовков и кнопок**:
    - Можно изменять заголовки формы и кнопку отправки данных. Например, вместо кнопки "Отправить" можно использовать "Получить материалы".
    - Это помогает сделать форму более привлекательной для пользователей.

    d. **Защита от спама и правила показа полей**:
    - Включена функция защиты от спама, чтобы предотвратить массовую отправку ненужных данных.
    - Можно настроить **правила показа полей**: разные поля могут отображаться для разных категорий клиентов (например, для водителей одно поле, для логистов — другое).

    e. **Действия после отправки формы**:
    - После заполнения формы клиенту можно показывать сообщение с благодарностью (например, "Спасибо, ваше сообщение отправлено").
    - Можно также задать значения по умолчанию для некоторых полей (например, код страны в номере телефона).

    f. **Подключение аналитики и рекламы**:
    - Форму можно связать с сервисами аналитики для отслеживания эффективности.
    - CRM-формы также могут быть интегрированы с рекламными кампаниями в ВКонтакте, что позволяет автоматически добавлять клиентов, заполнивших формы в рекламе, в Bitrix24.

    g. **Публикация CRM-формы на сайте**:
        - Сохранить форму на сайте можно несколькими способами:
        - В виде ссылки, которую можно разместить на кнопке «Заполните форму».
        - Встроить форму с помощью скрипта, если на сайте работают IT-специалисты.
        - Это позволяет значительно увеличить конверсию с сайта: больше клиентов будут заполнять формы, увеличивая число потенциальных заявок.

### Настройка виджетов на сайт в Bitrix24

   - Для настройки виджета нужно зайти в раздел **CRM** > **Еще** > **Виджет на сайт**.
   - В разделе виджетов уже есть предустановленные варианты, которые можно редактировать:
     - **Открытая линия** для общения с клиентами через чат.
     - **Форма обратной связи** для получения заявок.
     - **Форма обратного звонка** для быстрого контакта.

    a. **Взаимодействие с IP-телефонией**:
    - Если у вас подключена IP-телефония (через SIP-коннектор, облачную или офисную АТС), клиенты могут заказывать обратный звонок через виджет.
    - Настраивая виджет, можно указать номер телефона, на который будет направлен звонок клиента.

    b. **Редактирование виджета**:
    - Для установки виджета на сайт нужно скопировать и вставить специальный код в HTML-код сайта.
    - В настройках виджета можно указать:
        - **Каналы связи**: через виджет клиенты могут писать в Telegram, WhatsApp и другие мессенджеры, подключенные к Bitrix24.
        - **Рабочее время**: можно указать, когда виджет будет активен для общения.
        - **Отображение на страницах**: настроить, на каких страницах сайта будет показываться виджет.

    c. **CRM-форма и обратный звонок**:
    - Виджет может включать CRM-форму, которую клиенты заполняют для связи с компанией.
    - Обратный звонок настраивается через подключение IP-телефонии. Клиент оставляет свой номер телефона, система автоматически связывается с менеджером, и звонок сразу перенаправляется клиенту.

    d. **Автоматическое приветствие**:
    - В настройках виджета можно включить автоматическое приветствие. Например, сообщение «Здравствуйте, можем вам помочь?» будет появляться через несколько секунд после того, как клиент зайдет на сайт.
    - Приветствие можно персонализировать, указав имя сотрудника и его фотографию.

1. **Подключение виджета на сайт**:
   - Виджет можно подключить на любой сайт, указав параметры отображения и настроив привлечение клиентов через различные каналы.
   - При активной работе через виджет менеджеры смогут быстро реагировать на обращения клиентов, что повышает шансы на успешное закрытие сделки.


## CRM-маркетинг в Bitrix24**

1. **CRM-маркетинг в Bitrix24**:
   - CRM-маркетинг — это инструмент для работы с клиентской базой и привлечения новых клиентов. С его помощью можно проводить рассылки, рекламные кампании и использовать генератор продаж для работы с существующими клиентами.

2. **Основные инструменты CRM-маркетинга**:
   - **Рассылки**:
     - В Bitrix24 доступны различные типы рассылок: email, SMS, рассылки в мессенджерах (например, Telegram), инфозвонки и аудиозвонки.
     - Эти инструменты позволяют поддерживать связь с клиентами, информировать их о новостях, акциях и продуктах.
   - **Рекламные кампании**:
     - Вы можете выбирать целевую аудиторию и запускать таргетированную рекламу через рекламные кабинеты (например, Яндекс Директ). Это особенно эффективно, так как вы нацеливаетесь на тех, кто уже взаимодействовал с вашей компанией.
   - **Генератор продаж**:
     - Инструмент для повторной работы с клиентами, которые ранее обращались в вашу компанию. Генератор создает новые лиды и сделки на основе вашей клиентской базы, что позволяет менеджерам активизировать работу с потенциально заинтересованными клиентами.

3. **Создание рассылок**:
   - Для создания рассылки нужно зайти в раздел CRM-маркетинга и выбрать тип рассылки.
   - **Процесс создания email-рассылки**:
     1. Выбор шаблона рассылки.
     2. Настройка названия рассылки (например, сегмент «Клиенты из магазина»).
     3. Выбор сегмента получателей (например, клиенты, обратившиеся в определенный период).
     4. Заполнение темы письма и настройки отправителя.
     5. Редактирование контента письма в визуальном редакторе (добавление изображений, текста, UTM-меток).
     6. Тестовая отправка письма для проверки.

4. **Анализ эффективности рассылки**:
   - После отправки рассылки в разделе «Рассылки» можно увидеть статистику по проведенной кампании.
   - Основные метрики:
     - Количество отправленных писем.
     - Количество открытий писем (процент открываемости).
     - Переходы по ссылкам в письме (если включен call to action).
     - Число клиентов, которые отписались от рассылки.
   - Эти данные помогают анализировать эффективность рассылки, а также корректировать будущие кампании.

5. **Пример успешной рассылки**:
   - В одном из примеров была создана email-рассылка с темой «Вопрос по CRM», что привлекло внимание клиентов благодаря живому и персонализированному подходу.
   - Рассылку отправили 937 клиентам, 300 из которых открыли письмо (35% открываемости, что считается высоким показателем).
   - Ключ к успеху — актуальная база клиентов и привлекательный заголовок письма.

6. **Рекомендации по работе с рассылками**:
   - Для предотвращения попадания писем в спам важно делать рассылки по небольшим группам клиентов, которые проявили интерес к вашему бренду или продуктам.
   - Избегайте массовых бесконтрольных рассылок, так как это может снизить репутацию вашей email-кампании.
