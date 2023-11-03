# Анализ статистики заболеваемости раком различной локализации в РФ по данным на конец 2021г. 
[HTML] (https://datalens.yandex/r4alttrrpbqkg)     
[ipynb](in_process)

## Описание проекта

Исследование строится на данных, представленных в ежегодном исследовании “Состояние онкологической помощи населению России в 2021 году” под редакцией главного онколога страны, Карпина А.Д. Оргигинальные данные представлены в виде отдельных таблиц (всего более 100 таблиц). 
В ходе работы отдельные гугл-таблицы (с содержимым на нескольких листах) при помощи инструментов python были обработаны и объединены в единый датасет в формате .csv - файла, который в дальнейшем был использован в Yandex DataLens для построения дашборда. 

## Ссылки на оригинальные данные 

[HTML](https://drive.google.com/file/d/1x6wjJ2k8ZNCaIFusbcH6Zkt8a8xOdxhW/view)
[HTML](https://drive.google.com/file/d/1x6wjJ2k8ZNCaIFusbcH6Zkt8a8xOdxhW/view)
 

## Навыки и инструменты

- **Yandex Datalens**
- **python**

## 

## Общий вывод
В процессе исследования доступная вся информация была разбита на отдельные смысловые блоки, вынесенные на отдельные вкладки дашборда: 
 - **Блок структурных показателей**, отражающих общую ситуацию с состоянием онкологической помощи в РФ во всех регионах страны
   Здесь представлена статистика заболеваемости по общему числу пациентов, включая в т.ч. стандартизованные данные, уровень летальности и процент активно выявляемых случаев, а также уровень выявляемости заболеваний на различных стадиях.

 - **Блок анализа качества выявляемости злокачественных новообразований (ЗНО)**
   Здесь отдельно для каждой из 4 стадий рака доступен анализ ситуации с выявляемостью ЗНО различной локализации в разрезе выбранных Федеральных округов или регионов.
   
 - **Блок, содержащий сводную таблицу по "аномальным регионам"**
   Проведя подробный сравнительный анализ  качества выявляемости ЗНО в различных регионах страны на предыдущем этапе, можно собрать все самые аномальные случаи в единую таблицу, указав интересующие "отсечки" по уровню выявляемости заболеваний на каждой из стадий и отсортировав данные в нужном порядке.      

**Вывод исследования**: дашборд позволяет четко определить самые сложные с точки зрения своевременности выявления злокачественные новообразования (ЗНО), позволяет увидеть, насколько разнятся цифры с выявляемостью ЗНО на одной и той же стадии от региона к региону, что в дальнейшем позволяет профильному медицинскому персоналу искать причины, которые обуславливают такую разницу. Дашборд позволяет найти своеобразные "болевые точки", что должно позволить профильным ведомствам разобраться в проблеме и более рационально подходить к использованию ограниценных финансовых и временных ресурсов для улучшения ситуации с онкологической помощью в стране.