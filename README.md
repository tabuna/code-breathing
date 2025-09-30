# Code Breathing Analyzer

Наверняка вы встречали на сайтах небольшие объявления вроде «Чтение этой статьи займет всего 5 минут». 
Обычно это значение вычисляется исходя из количества слов в тексте и средней скорости чтения. 
С большой долей вероятности оно оказывается достаточно точным. Но что если аналогичную методику применить к программному коду?

Попробуйте посмтреть:
```php
XXXXXXXXXXXXXXXXXXX XX XX XX XXXXXXXX XXX XX XXXXX XXX
    XXXXX XX XXXX

    XXXXXXX XXXXXXXX XXXXXXX XXXXX
        XXXXXX XXXXXXXX XXXXX XX XXXXXXX XXXXX XXXXX XXX
            XX XXXXX XXXXXXXX XXX
                XXXXXXXXXXXXXXXXXXXXXXXX 
                XXXXXXX XX XXXXXXXXXX XXXXXXXXX 
                    X XXXXX XXXXX 
                    X XXXXX XXXX
            XX XXXX
                XXXXXXX XX XXXXX
            XX
        XX
    XX

    XXXXX XXXXXXX
XX
```

Нам намного приятнее читать текст, который бы 

```php
XXXXXXXX XXXXX XXX
        XX XXXXX XXXXXXXX XXX
            XXXXX XX XXXX
        XX

    XXXXX XXXXXXX
XX
```

Во втором примере, сильно меньше текста....


Так вот 
