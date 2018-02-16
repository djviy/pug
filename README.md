# pug
Заметки и приёмы по препроцессору Pug  
![pug logo](https://github.com/djviy/pug/blob/master/pug-icon.svg "Pug logo")

## Итерации с классами
### pug
```pug
each color in ['black', 'brown','purple']
  div(class="catalog-item-" + color)
```
### html
```html
<div class="catalog-item-black"></div>
<div class="catalog-item-brown"></div>
<div class="catalog-item-purple"></div>
```
