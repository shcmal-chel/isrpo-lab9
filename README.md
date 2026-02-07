# Лабораторная работа №9. Адаптивная верстка: Медиа-запросы
 **ФИО**: Шмаль Иван Максимович
 **Группа**: ИСП-232
 **Дата**: 08/02/26
___
## Описание работы
**Цель работы:** Изучить принципы адаптивной верстки и медиа-запросов. В конце
создать адаптивную страницу портфолио, которая корректно отображается на всех
устройствах.
**Адаптивная верстка** — это подход к созданию веб-страниц, при котором дизайн
и контент автоматически подстраиваются под размер экрана устройства (компьютер,
планшет, смартфон).
___
## Структура проекта
* `index.html` — пустой файл
* `responsive.html` — основной HTML-файл
* `responsive.css` — набор правил для `responsive.html`
* `nav-practice.html` - первое задание
* `nav-practice.css` — набор правил для `nav-practice.html`
* `flexbox-practice.html` - второе задание
* `flexbox-practice.css` — набор правил для `flexbox-practice.html`
* `README.md` — описание лабораторной работы
* `img/` — скриншоты
___

## Медиа-запросы

### Примеры:
```CSS
* Tablet (768px и больше) */
@media (min-width: 768px) {
.header {
flex-direction: row;
justify-content: space-between;
align-items: center;
}
.nav {
flex-direction: row;
gap: 15px;
}
.nav a {
background-color: transparent;
}
.features {
flex-direction: row;
}
.cards {
grid-template-columns: repeat(2, 1fr);
}
}
```