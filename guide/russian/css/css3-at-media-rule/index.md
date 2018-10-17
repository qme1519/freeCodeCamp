---
title: CSS3 at Media Rule
localeTitle: CSS3 в правиле СМИ
---
## CSS3 в правиле СМИ

Правило CSS3 Media является правилом, которое позволяет использовать медиа-запросы. Запросы в средствах массовой информации позволяют вам стилизовать вашу веб-страницу (либо ее часть, либо все ее) по-разному на основе разных типов или устройств.

Медиа-запрос создается с помощью тега `@media` и затем предоставляет правило для проверки таких вещей, как:

*   Ширина и высота текущего окна просмотра
*   Ориентация устройства (это относится к планшетам или телефонам)
*   Текущее разрешение
*   И больше

В настоящее время существует четыре возможных типа носителей:

*   all (По умолчанию - это будет предназначено для всех устройств)
*   print (Используется для принтеров, например, для отдельных стилей печати)
*   экран (используется для компьютеров, телефонов, планшетов и т. д.)
*   речь (используется для доступа к устройствам, таким как экранное устройство, которое повествует содержимое веб-страницы)

Запросы в СМИ используются для всех видов фиордов, поскольку они позволяют использовать многие функции мультимедиа. Одним из наиболее распространенных способов использования медиа-запроса является отрисовка веб-страницы; то есть он будет вести себя по-разному на основе размера экрана.

Пример медиа-запроса выглядит следующим образом:

```CSS
@media screen and (max-width: 1000px) { 
  body { 
    background: #000; 
  } 
 } 
```

CSS в правиле Media Query применяется только в том случае, когда правило имеет значение true. Например, глядя на фрагмент выше, фон тела будет изменен на `#000` только тогда, когда пользователь посещает страницу с устройством шириной 1000 пикселей или менее. Если выше 1000px, это правило не применяется.

#### Дополнительная информация:

*   [Правило CSS @media](https://www.w3schools.com/cssref/css3_pr_mediaquery.asp)
*   [Использование медиа-запросов](https://developer.mozilla.org/en-US/docs/Web/CSS/Media_Queries/Using_media_queries)