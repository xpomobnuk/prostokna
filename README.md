# Установка и запуск проекта
1. **Скачать и установить Node JS** [тут](https://nodejs.org/en/download/)
2. **Скачать и установить GIT** [тут](https://git-scm.com/downloads)
3. **Задаем переменную среды**<br>
В поиске Windows вводите "изменение переменных среды" и добавляете: `NODE_ENV = development` [Скрин](http://joxi.ru/krDgMojfEXZQqA)
4. **Форкаем текущий репозиторий** [Скрин](http://joxi.ru/l2ZKkoltwQNK4A)<br>
Таким образом в Вашем аккаунте появляется копия репозитория
5. **Клонируем репозиторий на рабочую машину** (не скачиваем, а именно клонируем)<br>
Для этого запускаем Git bash (ранее установленный), определяем папку где будет распологаться проект (к примеру на `C:/Project`)<br>
Выполняем:<br>
`cd C:/Project`<br>
`git clone https://github.com/ [ Ваш аккаунт ] /prostokna.git`
В выбранной папке появляется папка с названием `prostokna`<br>
`cd prostokna`
7. **Установка зависимостей**<br>
Выполняем<br>
`npm i`
8. **Создаем в корне файл `.env`**<br>
и добавляем содержимое `PORT = 3000`
9. **Запуск**
Выполняем в Git bash в 3-х разных окнах<br>
`npm run start`<br>
`gulp watch`<br>
`gulp bs`