# pug
Заметки и приёмы по препроцессору Pug  
![pug logo](https://github.com/djviy/pug/blob/master/pug-icon.svg "Pug logo")

## Итерации с классами
### pug
```pug
each color in ['black', 'brown','purple']
  div(class="catalog-item-model__colors-" + color)
```
### html
```html
<div class="catalog-item-model__colors-black"></div>
<div class="catalog-item-model__colors-brown"></div>
<div class="catalog-item-model__colors-purple"></div>
```
