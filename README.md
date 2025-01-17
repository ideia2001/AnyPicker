# AnyPicker Ideia 2001

Este plugin é utilizado para o campo de pesquisa **"De" - "Até"** implementado pela primeira vez no aplicativo da ZEN. O fork foi necessário para colocar o código minificado deste projeto no mobile-core. Fizemos uma alteração para remover o import do jquery, pois os aplicativos da empresa já possuem o jQuery, que é importado no index.html, e portanto não se encontra no package.json. O SEG Automotive é o aplicativo que requereu esta implementação.

### Como efetuar uma atualização no AnyPicker e passá-la ao **mobile-core**?

- Realizar a alteração necessária na pasta *src*.
- Rodar o comando "grunt" para gerar o código minificado na pasta *dist*.
- Copiar os "anypicker.min.js" e "anypicker.min.css" para a pasta "mobile-core/src/lib/anypicker".
- Pronto!!!

## AnyPicker - Picker Library for Mobile OS 


## What is AnyPicker?
AnyPicker is a jQuery Picker Library for Android, iOS & Windows Phone. eg **Date Picker**, **Time Picker**, **DateTime Picker**, **Rating Picker**, **Custom Select** etc. It simulates native picker functionality as seen in iOS, Android & Windows Phone & has many customizable features. 
 
## Where can I use AnyPicker?
You can use AnyPicker in your 
- Web applications
- Mobile websites
- Native mobile applications using webview
- Hybrid mobile applications created using Phonegap, Titanium etc.

## Browser Support
- Chrome, Firefox, Safari, Opera, IE 10+
- Android 2.3+, iOS 6+, Windows Phone 8


##Installations

- npm

  `npm install anypicker`

- bower

  `bower install anypicker`

##CDN
[AnyPicker is hosted on jsDelivr](https://www.jsdelivr.com/package/npm/anypicker).

Files - Latest

```
<link rel="stylesheet" type="text/css" href="//cdn.jsdelivr.net/npm/anypicker@latest/dist/anypicker-all.min.css" />
<script type="text/javascript" src="//cdn.jsdelivr.net/npm/anypicker@latest/dist/anypicker.min.js"></script>
<!-- For i18n -->
<script type="text/javascript" src="//cdn.jsdelivr.net/npm/anypicker@latest/dist/i18n/anypicker-i18n.js"></script>
```

Files - Particular Version

```
<link rel="stylesheet" type="text/css" href="//cdn.jsdelivr.net/npm/anypicker@<version>/dist/anypicker-all.min.css" />
<script type="text/javascript" src="//cdn.jsdelivr.net/npm/anypicker@<version>/dist/anypicker.min.js"></script>
<!-- For i18n -->
<script type="text/javascript" src="//cdn.jsdelivr.net/npm/anypicker@<version>/dist/i18n/anypicker-i18n.js"></script>
```

## Authors
[Neha Kadam](https://github.com/nehakadam): Developer<br/> 
[Lajpat Shah](https://github.com/lajpatshah): Concept & Design Contributor

## Thank You
- [All Contributors](https://github.com/nehakadam/DateTimePicker/contributors)

<br/> <br/> 

Copyright 2017 [Lajpat Shah](https://github.com/lajpatshah)

##License

Licensed under the MIT License
