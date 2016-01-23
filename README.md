# TürkçeScript: Türkçe anahtar kelimelerle JavaScript uygulamaları yazın

Bu depo, Türkçe anahtar kelimeler kullanarak JavaScript uygulamaları yazmanızı sağlayan bir Babel eklentisidir.


```js
değişken x = 4;
x = x + 1;
eğer (x === 5) {
    console.log("x 5'e eşit");
} değilse {
    console.log("x 5'e eşit değil");
}
```


# Demo

http://ustun.github.io/turkcescript/ adresinden TürkçeScript'i kullanabilirsiniz.


# Kurulum

```bash
npm install turkcescript
```

```js
var turkcescript = require('turkcescript');
```js
eval(turkcescript(`
    değişken x = 4;
    x = x + 1;
    eğer (x === 5) {
        console.log("x 5'e eşit");
    } değilse {
        console.log("x 5'e eşit değil");
    }
`))
```
