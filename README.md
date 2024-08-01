2024.08.01
# 13.02-WebPack-2
2. Клонировал себе.
3. Скопировал из папки "ci-template test 100%", кроме: .git, README.md, coverage, node_modules.
4. В Git Bash Here:
    Alex@38-PK MINGW64 /c/_GitHub_/13.02-WebPack-2 (main)
    $ npm install // появился каталог node_modules

npm start - http://192.168.0.15:8080/ открыл css работает

npm run build // появился каталог dist - произошла сборка проекта - запускаем его:
npm run show:dist // выдал: "live-server" не является внутренней или внеш ...
npm install --save-dev live-server
npm run show:dist // http://127.0.0.1:8080/ - открылся, css - работает



_______________________________________________________________________________________________
# 13.02-WebPack-2
npm install mini-css-extract-plugin --save-dev



# 13.02-WebPack-2
1. Создал пустой репозиторий на GitHub
2. Клонировал себе.
3. Скопировал из папки "ci-template test 100%", кроме: .git, README.md.
4. npm install



______________________________________
нет:
Собираем WebPack по своим лекциям:

Установка
npm init -y
npm install --save-dev webpack webpack-cli babel-loader
В скриптах заменим build:
"scripts": {
... 

"build": "webpack --mode production"

},
--------------------------------------