# Restaurant-Website
(学校の課題)高級レストランをイメージして作成をしたWEBサイト

> 今回使用したもの↓

## Font
### Google Fonts
`https://fonts.google.com/`

> Cormorant Garamond weight400&700
`https://fonts.google.com/specimen/Cormorant+Garamond?query=Cormorant+Garamond`

> Montserrat weight400
`https://fonts.google.com/specimen/Montserrat?query=Montserrat`

## icon
### Font-awesome CDN
`https://fontawesome.com/v5.15/how-to-use/customizing-wordpress/snippets/setup-cdn-webfont`

> 使用方法

###### 手順
headタグにcdnを追加する

```html
  <link
      rel="stylesheet"
      href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css"
      integrity="sha512-Fo3rlrZj/k7ujTnHg4CGR2D7kSs0v4LLanw2qksYuRlEzO+tcaEPQogQ0KaoGN26/zrn20ImR1DfuLWnOo7aBA=="
      crossorigin="anonymous"
      referrerpolicy="no-referrer"
    />
```

## slideshow
### Slick Carousel
`https://kenwheeler.github.io/slick/`

## animation
### animation on scroll
`https://github.com/michalsnik/aos`

> 使用方法

###### 手順
headタグに追加する:

```html
  <link rel="stylesheet" href="https://unpkg.com/aos@next/dist/aos.css" />
```

bodyタグの直下に貼り付ける:
```html
  <script src="https://unpkg.com/aos@next/dist/aos.js"></script>
  <script>
    AOS.init();
  </script>
```

## Library
### jQuery
`https://jquery.com/`

> 使用方法

###### 手順
bodyタグの直下に貼り付ける

```html
  <script
      src="https://cdnjs.cloudflare.com/ajax/libs/jquery/3.5.1/jquery.slim.min.js"
      integrity="sha512-/DXTXr6nQodMUiq+IUJYCt2PPOUjrHJ9wFrqpJ3XkgPNOZVfMok7cRw6CSxyCQxXn6ozlESsSh1/sMCTF1rL/g=="
      crossorigin="anonymous"
      referrerpolicy="no-referrer"
    ></script>
```
