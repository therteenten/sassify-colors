# [Sassify](https://github.com/therteenten/sassify) Colors
🎨 Набор различных цветовых палитр, предоставляемых в виде Sass-переменных (Variables) и карт (Maps).

```sh
npm install @therteenten/sassify-colors
```

## Начало работы
После установки зависимости в свой проект, импортируйте модуль Sassify Colors:

```scss
@use 'node_modules/@therteenten/sassify-colors' as colors;
```

Теперь вся палитра из Sassify Colors доступна через пространство `colors`:

```scss
// _styles.scss
.text-warning {
	color: colors.$md-red--500;
}

.card {
	background-color: colors.$md-grey--200;
	color: colors.$md-grey--900;
}
```

```css
/* styles.css */
.text-warning {
	color: #f44336;
}

.card {
	background-color: #eeeeee;
	color: #212121;
}
```

> Вся цветовая палитра из Sassify Colors задокументирована с помощью комментариев SassDoc. Документация доступна по [этой](https://therteenten.github.io/sassify-colors/) ссылке.

## Лицензия
```
MIT License

Copyright (c) 2023 Haba Kudzaev (therteenten)

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```
