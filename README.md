# gamedev_project

- [TEASER TRAILER](https://youtu.be/J9pHRrZdp-s)
- [Gameplay Trailer](https://youtu.be/rfQKVlO3wtc)

Made with Unreal Engine 4 (1/10/2020-25/11/2020)

### Основа
- Сюжетный платформер, завязанный на физике зеркал;
- Длинные комбинации зеркал (головоломки) для прохождения уровней;
- Пространство состоит из некоторых единиц измерения пространства (квадраты).

### Геймплей
1. Комнаты между собой закрыты древними каменными дверями, которые можно открыть только с помощью света (на двери должен быть постоянно направлен свет)
2. Зеркала можно двигать и вращать (наличие статических и динамических зеркал)
3. Наличие монстров (летающих и передвигающихся по земле):
    1. Пытаются убить игрока
    2. Есть некоторый радиус агро (статическое местоположение, некоторые бродят в некотором радиусе от своего спавна, некоторые могут появляться из различных структур уровня, например из гроба), монстр прекращает преследование, как только не может проследовать за игроком дальше, ждет некоторое время и возвращается на свое место
    3. Задача игрока отогнать монстра с помощью света, монстров можно убить светом (прижать к стене светом, с двух сторон светом)
    4. Если монстр идет по принуждению (за счет света), он по мере движения ломает статические зеркала и двигает подвижные зеркала; если при этом зеркала сталкиваются с объектом (различные стены, блоки, фурнитуры), они ломаются
    5. Монстры не могут двигаться по лестницам (зеркала тоже), но летающие могут двигаться через дыры (но не через лестницу)

### Сюжет
ГГ узнает о местоположении затерянного города древней цивилизации, поклоняющейся солнцу, он приходит по координатам и проваливается вниз (в комнату самой верхней точки города), сквозь образовавшуюся при его падении дыру просачивается солнечный свет и падает на необычное зеркало, физические свойства этого зеркала крайне неестественны, оно не рассеивает свет а всего лишь идеально отражает его в один луч, гг понимает, что это зеркало здесь с какой-то целью.
