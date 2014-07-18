ya-flags
========

BEM-flavoured flags icons. 
Similar with icons used by Yandex in their projects.


#Usage:

As it uses [BEM](http://bem.info/) methodology, each node needs 3 classes:

* General definition: `b-country-flag`;
* Size definition: `b-country-flag_size_(16|24|32|48|64)`;
* Nation definition: `b-country-flag_size-48_(ad|al|am|ar...za|zw)` (see full list of available flags below).

Note, that all classes are hidpi-friendly: all image assets automatically double their resolution on retina displays.


###Examples:

####64&times;48:
![KR flag](http://yastatic.net/fifa14-frontend/_/DT7Mkk-UZWDfB1Q1PhCwLKjeE6Y.png)
```html
<span class="b-country-flag b-country-flag_size_48 b-country-flag_size-64_kr"></span>
```

####48&times;36:
![DE flag](http://yastatic.net/fifa14-frontend/_/wxDcDfTV7OUhSaP7zr0YH_V6s_E.png)
```html
<span class="b-country-flag b-country-flag_size_48 b-country-flag_size-48_de"></span>
```

####36&times;24:
![BR flag](http://yastatic.net/fifa14-frontend/_/PwEFC-cn0BvVLtVvMdQE4Hr-I_w.png)
```html
<span class="b-country-flag b-country-flag_size_48 b-country-flag_size-36_br"></span>
```

####24&times;16:
![BE flag](http://yastatic.net/fifa14-frontend/_/7xjRM15pRfVrZKJF9c8DyLkR4fE.png)
```html
<span class="b-country-flag b-country-flag_size_48 b-country-flag_size-24_be"></span>
```

####16&times;12:
![RU flag](http://yastatic.net/fifa14-frontend/_/KbUTsZq6ePAcVcZpzG5V36PZKxM.png)
```html
<span class="b-country-flag b-country-flag_size_48 b-country-flag_size-16_ru"></span>
```

##List of available countries:

- ad al am ar at au az
- ba be bg bm br bs by
- ca ch cl cn co cr cy cz
- de dk do dz
- ee es et
- fi fr
- gb ge gh gr
- hk hr hu
- ie il in ir is it
- jm jp
- ke kg kp kr ky kz
- lb li lt lu lv
- ma mc md me mk mn mt mx
- nl no np nz
- pe ph pk pl pt py
- ro rs ru
- se si sk sm sn
- tg th tj tl to tr tw
- ua us uz 
- ve vg vi
- za zw