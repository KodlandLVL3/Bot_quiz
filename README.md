# Бот для проведения Квиза
## Начало игры
1. Преподаватель устанавливает бота на свой сервер и начинает игру отправив команду !quiz. 
2. Студенты подключаются к серверу. 
3. У студентов на сервере появляется сообщение с кнопками и списком игроков в командах

## Процесс игры
- При нажатии на кнопку игрок добавляется в команду
- Игроку в личные сообщения приходит сообщение с вопросом и кнопкой ответить
- Вопросы смешиваются в случайном порядке внутри этапа
- При нажатии на кнопку ответить, открывается модальное окно, в котором он вписывает ответ
- Если ответ верный, вопрос в сообщении обновляется
- После ответа присылается сообщение верно или неверно
- За каждый правильный ответ на вопрос игрок получает фрагмент фразы
- Чтобы перейти на следующий этап необходимо отправить корректную фразу

###### В сообщении с вопросом отображается количество очков, текущие фрагменты слов и разгаданные слова
