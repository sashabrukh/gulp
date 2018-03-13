Сборка gulp-webpack

Webpack собирает только js, всё остальное делает gulp

Команды для npm:

Общее:

Установка пакетов в npm
yarn 

Включение слежки за файлами, компиляция pug, scss, обновление браузера, пересборка библиотек 
gulp

Включение слежки за js файлами и сборка в бандл
webpack

Спрайты: 
Положить картинки по назначению(forsprite > png или forsprite > svg)
sprite:svg или sprite:png (для png в папке sprites создастся scss файл со стилями)

Библиотеки css и js: 
Автоматически собираются при слежении в файлы libs.min.css и libs.min.js

Билд:
gulp build
Перед установкой удаляется и создается папка dist, далее туда переносятся уже готовые 
(обработанные, сжатые, минифицированые и тд)
HTML файлы копируются в одну папку, после билда их необходимо разложить по папкам как они лежали у вас в исходниках

Очистка кэша:
gulp clear