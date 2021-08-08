# Практическая часть, курс ReactJS (geekbrainds.ru) 

#### [Урок 1. Знакомство с ReactJS. Первые компоненты]()
1. Развернуть новый проект с использованием create-react-app.
2. Создать компонент Message, отображающий переданный ему пропсом текст.
3. Изменить компонент App так, чтобы тот рендерил Message и передавал ему пропсом текст (константу).
4. Стилизовать компоненты через css (при желании можно использовать less или sass, однако для sass нужно дополнительно установить node-sass: документация CRA).
5. Установить расширение React Devtools.


#### [Урок 2. Жизненный цикл компонента]()
1. Добавить в компонент App поле стейта messageList. В нем хранить массив объектов - сообщений (объект должен содержать, как минимум, поля text и author). Начальное значение - пустой массив).
2. Рендерить список сообщений через map.
3. Добавить и стилизовать форму - поле для ввода текста и кнопка для отправки сообщения. При отправке сообщения обновление UI должно происходить за счет обновления стейта App.
4. Добавить в App useEffect - на каждое отправленное пользователем сообщение должен отвечать робот (должно автоматически отправляться сообщение с фиксированным текстом) - для этого необходимо проверять автора последнего сообщения.
5. * Сделать задержку ответа робота - сообщение от него должно отправляться через некоторый промежуток времени после отправки сообщения пользователя (напр., 1.5 сек).


#### [Урок 3. Virtual DOM. Material UI. PropTypes]()
1. Установить material-ui. Переделать форму с использованием компонентов из material-ui.
2. Добавить автофокус на текстовое поле при открытии страницы и после отправки сообщения.
3. Исправить ошибку в консоли, связанную с отсутствием key у сообщений.
4. Добавить “массив чатов” - массив объектов с полями name и id (в качестве id можно выбрать любую уникальную строку). Добавить список чатов - он должен отображаться слева от списка сообщений. Используйте List и ListItem из material-ui (список пока не несет никакой функциональности).
5. * Добавить тему material-ui.


#### [Урок 4. Children. Роутинг в React]()
1. Установить react-router-dom. Добавить домашнюю страницу по адресу “/” со списком ссылок на страницу чатов и страницу профиля.
2. Добавить страницу профиля (пока не несет никакой функциональности, можно сделать ее пустой).
3. Настроить разделение приложения на чаты с помощью роутера (использовать параметры url). Приложение должно корректно работать, если пользователь вводит идентификатор несуществующего чата или если идентификатора чата нет (т.е. адрес “/chats/”).
4. * Добавить возможность удаления и добавления чатов.
