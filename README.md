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

## Add new lang:

```
data-ya-lang="{CODE}"
```

All available languages and their code can be found [here](https://yandex.ru/dev/translate/doc/dg/concepts/api-overview.html).

### Example

[Demo Page](http://demo.l2banners.ru/yandex-translate-custom-widget)

## More

Sometimes there may be some content on your page that you don't want to
translate. You can now add translate="no" to any HTML element to prevent
that element from being translated. For example, you may want to do something
like:

`Email us at <span translate="no">sales at mydomain dot com</span>`


### Поддержать проект:

Данная модификация предоставляется абсолютно бесплатно, поэтому вы можете
отправить **благодарность по реквизитам**:

- Visa (usd) - 4149629331519363
- Visa (uah) - 4731185620908514
- Binance pay id: 463795904
- USDT trc-20: TUDPzTVicb51L6sH1KyDVxNx6TJrncN5X7
- Карта МИР: 2204120117672887
- https://yoomoney.ru/to/410018011293312

_Любая ваша поддержка это мотивация выкладывать в общий доступ другие наработки
и поддерживать их._

