# Научиться Учиться
Проект об обучении, о том, как правильно учиться. Это мой второй проект. В первом проекте не хватало анимации и видео, а также дополнительной информации для обучения, все это было решено реализовать во втором проекте.

__Проект написан на HTML5 и CSS.__
___

# ___Технологии, использованные в проекте:___
1. Nested-структура и привязка ```@import```
```css
@import url(../blocks/resources/resources.css);
```
2. ```@keyframes```
```css
@keyframes move_bg {
    0% {
      transform: rotate(0deg);
    }
    100% {
      transform: rotate(360deg);
    }
  }
```
3. ```iframe```
```html
<ul class="video__iframes">
      <li class="video__iframe"><iframe width="515" height="316" src="https://www.youtube.com/embed/5MgBikgcWnY" title="YouTube video player" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
      </li>
</ul>
```