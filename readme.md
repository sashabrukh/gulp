Сборка gulp-webpack
=============================

УСТАНОВКА
---

Webpack собирает только js, всё остальное делает gulp

Основные команды для npm:

      yarn               Установка пакетов
      gulp               Включение слежки за файлами, компиляция pug, scss, обновление браузера, пересборка библиотек 
      webpack            Включение слежки за js файлами и сборка в бандл
      sprite:svg (png)   Для png в папке sprites создастся scss файл со стилями
      gulp clear         Очистка кэша
      gulp build         Итоговый билд


Библиотеки css и js автоматически собираются при слежении в файлы libs.min.css и libs.min.js.

Билд: перед установкой удаляется и создается папка dist, далее туда переносятся уже готовые файлы(обработанные, сжатые, минифицированые и тд).

> **HTML файлы копируются в одну папку, после билда их необходимо разложить по папкам как они лежали у вас в исходниках**
