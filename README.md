

# Gulp бандл

## Файловая структура

**Вся файловая структура генерируется автоматически. Руками ничего создавать не нужно!**

Сборщик имеет следующую файловую структуру:

```
├── src                 # папка сборки проекта
  └── assets/           # ресурсы
      ├── fonts/        # используемые шрифты
      ├── images/       # используемые картинки в проекте
      ├── js/           # скрипты в проекте
      └── scss/         # файл стилей Основные вотчеры (разложены по папкам в соответствии с типом отслеживаемых файлов)
  ├── tpl/              # основная папка с проектом
      ├── data/         # входной файл с данными, принимающий json данные
      ├── layouts/      # шаблоны страниц
      └── partials/     # компоненты страницы (части html)
  ├── contact.html      # используемый шаблон пример
  └──index.html         # главная страница 
├── package.json        # основные зависимости
├── gulpfile.js         # gulpfile сборщика
└── README.md           # описание данной сбоки

```

## Структура отдельного компонента 
