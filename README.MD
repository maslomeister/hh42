# hh42

Беспроводная эрго сплит клавиатура заточенная под руки владельца репозитория, MX LP и [ZMK](https://zmk.dev/).

Спасибо [Corne](https://github.com/foostan/crkbd) за вдохновление.

![keyboardimage](https://github.com/maslomeister/hh42/blob/main/img/kicad_3d.png?raw=true)

# Гербер файлы

Скачать гербер файлы ПЦБ можно [ТУТ](https://github.com/maslomeister/hh42/blob/main/pcb/production/hh42.zip)

# Стоимость сборки

| Предмет                 | Цена в $                                                                                        | Комментарий             | Ссылка                                                                                                                              |
| ----------------------- | ----------------------------------------------------------------------------------------------- | ----------------------- | ----------------------------------------------------------------------------------------------------------------------------------- |
| ПЦБ                     | 25                                                                                              | Цена за 5 комплектов    | https://aliexpress.ru/item/1005006573905744.html                                                                                    |
| MX LP свитчи            | 27                                                                                              | Цена за 60 штук         | https://aliexpress.ru/item/1005006328228130.html                                                                                    |
| Ножки                   | 4.6                                                                                             | Цена за 100 штук        | https://aliexpress.ru/item/32963141746.html                                                                                         |
| SuperMini               | 4.8                                                                                             | Клон nice nano 2.0      | https://aliexpress.ru/item/1005006035267231.html                                                                                    |
| Диоды                   | 0.85                                                                                            | Цена за 100 штук        | https://aliexpress.ru/item/32849879904.html                                                                                         |
| PCM12SMTR переключатель | 4                                                                                               | Цена за 5 штук          | https://aliexpress.ru/item/1005005366298406.html                                                                                    |
| Reset кнопка            | 1.5                                                                                             | 4.3ММ; Цена за 100 штук | https://aliexpress.ru/item/32882161197.html                                                                                         |
| Сокеты для контроллера  | 1.9                                                                                             | Цена за 100 штук        | https://aliexpress.ru/item/32980406694.html                                                                                         |
| Пины для контроллера    | 4.3                                                                                             | Цена за 100 штук        | https://aliexpress.ru/item/32858430771.html                                                                                         |
| Аккумулятор 110 mah     | 4.2                                                                                             | -                       | https://www.ozon.ru/product/akkumulyator-dlya-videoregistratora-akb-batareya-3-7v-130mah-5x12x30-li-pol-2-provoda-501230-1047383524 |
| Итог за 1 клавиатуру    | <!--5+27+4.6/100*30+4/8+4/8+0.85/100*42+4/5*2+1.5/10*2+1.9/100*48+4.3/100*48+4.2+4.2--> **~48** |

# Прошивка и раскладка

Готовые файлы прошивки [ТУТ](https://github.com/maslomeister/hh42/tree/main/firmwares), репозиторий с исходниками [ТУТ](https://github.com/maslomeister/zmk-configs)

### Основной слой

![основной_слой](https://github.com/maslomeister/hh42/blob/main/img/layout1.png?raw=true)

### Lower слой

![lower_слой](https://github.com/maslomeister/hh42/blob/main/img/layout2.png?raw=true)

### Raise слой

![raise_слой](https://github.com/maslomeister/hh42/blob/main/img/layout3.png?raw=true)

### Combined слой (Lower+Raise)

![combined_слой](https://github.com/maslomeister/hh42/blob/main/img/layout4.png?raw=true)

# Сборка

Контроллеры паяются диодами вверх, все остальное видно на шелкографии. Аккумулятор на 110 mah паять к пинам под контроллерами чтобы питание можно было отключать через переключатель.
