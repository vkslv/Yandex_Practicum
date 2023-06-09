# Выбор локации для скважины

Необходимо разработать модель, которая позволит поможет определить регион, где добыча принесёт наибольшую прибыль.

*Данный проект был выполнены в ходе обучения на программе "Специалист по Data Science" в Яндекс.Практикуме.*

| Описание           | Используемые библиотеки                     |
| :--------------------- |:---------------------------|
| Допустим, вы работаете в добывающей компании «ГлавРосГосНефть». Нужно решить, где бурить новую скважину. Вам предоставлены пробы нефти в трёх регионах: в каждом 10 000 месторождений, где измерили качество нефти и объём её запасов. Проанализируйте возможную прибыль и риски техникой Bootstrap.| pandas, numpy, matplotlib, scipy, sklearn|

## Вывод

- В самом начале мы подготовили данные для анализа, изучили их типы, проверили на наличие дубликатов, вывели описательную статистику по каждому региону.
- Затем была написана функция, которая разбивает данные на выборки, скалирует их, строит модель линейной регрессии для того, что предсказать объемы нефти в каждой из скважин.
- Далее, с помощью Bootstrap был найден 95% доверительный интервал.
- Наименее рискованным является второй регион, где риск составил 1.1%, средняя прибыль также является наибольшей для второго региона.
- С точки зрения перспектив разработки, наиболее привлекательным является второй регион.

