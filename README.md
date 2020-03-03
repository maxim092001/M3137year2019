# Конспекты М3137

Если вы хотите помочь, всё, чего не хватает в конспектах - [тут](https://github.com/Jovvik/M3137year2019/issues/2)

Если нашли ошибку, пишите в [issues](https://github.com/Jovvik/M3137year2019/issues) или мне в телеграм @aeriu.

## 2 семестр

### Матанализ
- [Конспект к первому опросу](analysis/2sem/opros1.pdf)
- [Лекция #1](analysis/2sem/1.pdf)
- [Лекция #2](analysis/2sem/2.pdf)
- [Лекция #3](analysis/2sem/3.pdf)
- [Практика #1](analysis/2sem/practice/1.pdf)
- [Практика #2](analysis/2sem/practice/2.pdf)

### Линейная алгебра
- [Практика #1](linear%20algebra/2sem/practice/1.pdf)
- [Практика #3](linear%20algebra/2sem/practice/3.pdf)
- [Практика #4](linear%20algebra/2sem/practice/4.pdf)
- [Лекция #1](linear%20algebra/2sem/1.pdf)
- [Лекция #2](linear%20algebra/2sem/2.pdf)
- [Лекция #3](linear%20algebra/2sem/3.pdf)
- [Лекция #4](linear%20algebra/2sem/4.pdf)

### Дискретная математика
- [Лекция #1](discrete/2sem/1.pdf)
- [Лекция #2](discrete/2sem/2.pdf)
- [Лекция #3](discrete/2sem/3.pdf)

## 1 семестр

### Линейная алгебра
- [Конспект к экзамену](linear%20algebra/1sem/main.pdf) _(рендер pdf с векторами в github'e не работает, поэтому надо pdf скачивать)_

### Матанализ
- [Опрос #1](analysis/1sem/opros.pdf)
- [Опрос #2](analysis/1sem/opros2.pdf)
- [Конспект к экзамену](analysis/1sem/final.pdf)


## Как компилировать самому

Билд делается через `xelatex`, потому что я ~тупой и не понял сразу, как включить русский в нормальном латехе~ хотел адекватную поддержку русского. Но в `pdflatex` билдится, багов не замечал. Зависимостей тонны, так что проще сразу ставить самый полный набор пакетов, который можете, иначе будет боль с `tlmgr`.

Все, кроме конспектов лекций и первого опроса по матану, писалось с минимизацией копипаста через импорты кусков других файлов с помощью `catchfilebetweentags`, поэтому по отдельности ничего не компилируется.

В 1 семе первые пара лекций написаны в markdown, при этом из-за добавления тегов для импортов они теперь сломанные, но пдфки в оригинальном виде оставлены.
