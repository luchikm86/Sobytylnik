# Sobutylnik.com
Sobutylnik.com – сервис позволяющий находить себе идеального друга/подругу, чьи интересы, жизненная позиция, взгляды, тип характера и пр. совпадают с твоими собственными. Этим сервисом может пользоваться абсолютно любой человек, желающий найти в этом мире как можно близкого для себя человека. На специальной странице, пользователю будут показаны топ 10 наиболее близких по духу людей. Также пользователь может найти другого человека (не вошедшего в список) и проверить совместимость вручную (нажав на специальную кнопку).
 
Данная система состоит из :

1.Главной страницы с описанием сервиса, если человек не залогинен, или Личной страницы с минимальным количеством данных (Имя и Фамилия, дата рождения и место проживания, а также результатами теста), если человек залогинен.

2.Страницей, где указаны ТОП 10 близких по духу людей. Здесь присутствует также вариант с сортировкой по полу, году рождения, местом проживания и т.д.

3.Страница с списком контактов (которых клиент решил добавить)

4.Страница с поиском новых контактов.

5.Выезжающей (слева) вкладкой с мессенджером, где находятся личные контакты, а также чат-группы, созданные пользователем.
 
Пользователь может:
- Регистрироваться: Ввести данные о себе (Имя, Фамилия, дата рождения, Страна рождения, Место проживания), пройти следующие тесты: Психологический, Политический, Религиозный, IQ, Хобби (здесь очень много разных вариантов будет внесено с помощью enum; любимые фильмы/музыка/книги будут спрашиваться в виде любимого жанра/направления музыки)
- Искать людей
- Добавлять людей в список контактов
- Списываться с контактами в чате
- Создавать чат-группы
 
Суть анализа данных: Объединить ответы пользователя в группы, например, будут несколько групп с разными IQ результатами, или, например, для психологического теста, результаты - Дон Кихот и Дюма будут в одной группе, так как имеют дуальное отношение по соционической таблице (https://socionika.info/tabl.html), или, для политического теста, фашизм и нацизм будут также содержаться в одной группе, или хобби - баскетбол и футбол будут находится в одной группе «спорт» и т.д. Проверка будет осуществляться путем сверки этих групп, куда попадают пользователи. Если есть совпадения по нескольким группам, то задействуется внутренний поиск внутри каждой из групп и сравнивается, например, – выбрали ли оба пользователя футбол, в совпавшей группе «спорт» и т.д. В конце высчитывается процент совпадения.

