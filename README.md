# Код для sha256 у Раймона Кено

## Зачем?

Код был написан для практического решения задачи, сформулированной в этом посте на Хабре: «[Как я намайнил первое в мире биткоин-стихотворение](https://habr.com/ru/articles/728944/)».

## Над чем?

Речь про комбинаторный сборник Раймона Кено «[Сто тысяч миллиардов стихотворений](https://ru.wikipedia.org/wiki/%D0%A1%D1%82%D0%BE_%D1%82%D1%8B%D1%81%D1%8F%D1%87_%D0%BC%D0%B8%D0%BB%D0%BB%D0%B8%D0%B0%D1%80%D0%B4%D0%BE%D0%B2_%D1%81%D1%82%D0%B8%D1%85%D0%BE%D1%82%D0%B2%D0%BE%D1%80%D0%B5%D0%BD%D0%B8%D0%B9)» (Cent mille milliards de poèmes).

## Что внутри?

[Тетрадка с кодом на питоне](https://github.com/nevmenandr/queneau/blob/main/Queneau.ipynb) содержит:

* Майнинг данных из сети;
* Тупой генератор перебора;
* Оценку времени на обсчет всех вариантов;
* Попытку в многопоточность.

## Сколько?

«В лоб» обсчитано около полутора миллиардов вариантов. Нужные варианты не найдены. На полный перебор на текущей скорости уйдет 38 с половиной лет.
 
