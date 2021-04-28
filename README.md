# yandex-translate-custom-widget

![](https://raw.githubusercontent.com/get-web/Examples/main/yandex-translate-custom-widget/yandex-translate-custom-widget.gif)

# Install:

### Add Files

```
   <script src="./js/yatranslate.js"></script>
   <link rel="stylesheet" href="./css/yatranslate.css">
```

### Add html:

```
<div class="lang lang_fixed">
   <div id="ytWidget" style="display: none;"></div>
   <div class="lang__link lang__link_select" data-lang-active="">
       <img class="lang__img lang__img_select" src="./images/lang/lang__ru.png" alt="Ru">
   </div>
   <div class="lang__list" data-lang-list="">
       <a class="lang__link lang__link_sub" data-ya-lang="ru">
           <img class="lang__img" src="./images/lang/lang__ru.png" alt="ru">
       </a>
       <a class="lang__link lang__link_sub" data-ya-lang="en">
           <img class="lang__img" src="./images/lang/lang__en.png" alt="en">
       </a>
       <a class="lang__link lang__link_sub" data-ya-lang="de">
           <img class="lang__img" src="./images/lang/lang__de.png" alt="de">
       </a>
       <a class="lang__link lang__link_sub" data-ya-lang="zh">
           <img class="lang__img" src="./images/lang/lang__zh.png" alt="zh">
       </a>
       <a class="lang__link lang__link_sub" data-ya-lang="fr">
           <img class="lang__img" src="./images/lang/lang__fr.png" alt="fr">
       </a>
   </div>
</div>
```

### Example

[Demo Page](http://demo.l2banners.ru/yandex-translate-custom-widget)
