## Интенсив по верстке "Сайт автоковриков" ##

### Day 1 ###
Создание каркаса сайта\
Часть 1. Создаем каркас проекта\
Часть 2. Пишем код для шапки и подвала сайта\
Публикуем сайт на Github

*в подвале декор можно сделать псевдоэлементами либо фоном*

necolas.github.io/normalize.css — Normalize CSS
https://svgsprit.es/ - Sprite generator

### Day 2 ###
Верстаем блоки с вложенностью и фоном\
Сегодня подключим шрифт к нашему проекту, а дальше продолжим писать HTML и CSS код.\
Сделаем фон для вложенных блоков, поработаем с меню, кнопкой и гридами, оформим мини-карточки

fonts.google.com — сервис бесплатных шрифтов от Google\

В свойствах css не так давно появилась возможность сделать плавный скрол при нажатии на пункты меню\
(например) без использования js. Предлагаю тем, кто успевает, применить этот момент в нашем проекте.

### Day 3 ###
Слайдер отзывов\
Верстаем и оживляем слайдер с отзывами, используем swiperJS

*Полезные ссылки*\
swiperjs.com — плагин слайдера на JavaScript\
https://bennettfeely.com/clippy/ - ресурс для генерации clip-path свойства

УСЛОЖНЕННОЕ ЗАДАНИЕ: 
Добавьте в файле js настройки для отображения слайдера на мобильном устройстве в соответствии с макетом,\
а также предложите ваше решение как добавить затемнение для слайдера с выделением активного слайда.

### Day4 ###
Работаем с модальным окном\
Верстаем мобильное меню и оживляем его с помощью нативного js, стилизуем элементы формы\
Ссылка на сетку медиазапросов\
`
*,
*::before,
*::after {
    box-sizing: border-box;
}

*:focus:not(:focus-visible) {
    outline: none;
}

html,
body {
    font-size: 62.5%;
    font-family: 'Roboto', sans-serif;
    font-weight: normal;
}

img {
    width: 100%;
    height: 100%;
    object-fit: contain;
}

ul {
    padding-left: 0;
}

ul>li {
    list-style: none;
}

h1,
h2,
h3,
h4,
h5,
h6 {
    padding: 0;
    margin: 0;
}

.container {
    width: 120rem;
    margin: 0 auto;
}

/*сетка*/
@media (max-width: 108em) {
    html {
        font-size: 9px;
    }
}

@media (max-width: 105em) {
    html {
        font-size: 8.75px;
    }
}

@media (max-width: 91.5em) {
    html {
        font-size: 7.9px;
    }
}

@media (max-width: 91em) {
    html {
        font-size: 8.4px;
    }
}

@media (max-width: 90em) {
    html {
        font-size: 7.9px;
    }
}

@media (max-width: 80em) {
    html {
        font-size: 7.2px
    }
}

@media (max-width: 72em) {
    html {
        font-size: 6.5px;
    }
}

@media (max-width: 64em) {
    html {
        font-size: 5.5px;
    }
}

@media (max-width: 48em) {
    html {
        font-size: 10px;
    }

}

@media (max-width: 44em) {
    html {
        font-size: 9px;
    }
}

@media (max-width: 38em) {
    html {
        font-size: 8px;
    }
}

@media (max-width: 34em) {
    html {
        font-size: 7px;
    }
}

@media (max-width: 30em) {
    html {
        font-size: 6px;
    }
}

@media (max-width: 26em) {
    html {
        font-size: 4.5px;
    }
}

@media (max-width: 21em) {
    html {
        font-size: 4.4px;
    }
}

/*сетка*/
`