---
tags:
  - гто
  - GTOpluse
  - pokerrockets
---
[Полный разбор интерфейса GTO+: кнопки, ползунки, настройки #покеробучение #gto - YouTube](https://www.youtube.com/watch?v=XxCOhk1u1b4)

<span style="color:rgb(0, 176, 240)">File</span>-> <span style="color:rgb(0, 176, 240)">Open: Convert to basic Storage</span>
	- сохранять обрезанные "легкие" деревья
нужен для ресерчных деревьев где не нужно играть в тренажере, а нужно смотреть аналитику и быстро подгружать

<span style="color:rgb(0, 176, 240)">Undo</span> : Ctrl+Z
<span style="color:rgb(0, 176, 240)">Redo</span> Ctrl+Y

 ![[Pasted image 20250206223825.png]]
 Ползунки для протягивания ренжа

<span style="color:rgb(0, 176, 240)">Apply groups to selection</span>:
Выделяет группы рук цветами - и потом показывает аналитику по ним :![[Pasted image 20250206224136.png]]

<span style="color:rgb(0, 176, 240)">Колесико</span>:
![[Pasted image 20250206224532.png]]
Настройка цветов отображения карт в матрице (зеленый синий красный - дефолт)

<span style="color:rgb(0, 176, 240)">Пересчитать дерево</span>: <span style="color:rgb(255, 99, 71)">Run solver</span>
![[Pasted image 20250206225029.png|333]]
Эти <span style="color:rgb(0, 176, 240)">0.2%</span> будут считаться от размера банка (<span style="color:rgb(0, 176, 240)">60</span> в нашем случае)
![[Pasted image 20250206225454.png|333]]
Нормальная эксплуатируемость стратегии: 1бб /100
0.5х60=12 (/10=<span style="color:rgb(255, 140, 0)">1.2бб /100</span>) Это рассчет хорошей точности.
точность 0.5% и 0.2% могут сильно отличаться, потому берем <span style="color:rgb(255, 99, 71)">0.2%</span>
0.5% = примерно 2.5 бб /100
Мы размеры в ББ умножали на 10 (когда получили 60 префлоп пот, чтобы работать без точек)

<span style="color:rgb(0, 176, 240)">Basic/Extensive</span> - нужны ли нам терны

![[Pasted image 20250206230534.png]]
Если считать через папку - фоном посчитает и сохранит изменения.

##### Для 3бет потов, точность нужно ставить выше - 0.1% вместо 0.2%, т.к. больше начальный банк.

Не забываем нажимать <span style="color:rgb(0, 176, 240)">IMPORT TREE</span> если меняем ренжи.

<span style="color:rgb(0, 176, 240)">Action colors</span>:
![[Pasted image 20250206231227.png]]

<span style="color:rgb(218, 112, 214)">Цвета</span>:
> [!faq]- pic
>  ![[Pasted image 20250206231428.png]]

Можно пойти также в <span style="color:rgb(0, 176, 240)">Instructions</span>
![[Pasted image 20250207001317.png]]
Мои настройки цветов как в ПИО

<span style="color:rgb(0, 176, 240)">Выгрузить и посчитать НОД</span>
![[Pasted image 20250207001347.png]]
<span style="color:rgb(218, 112, 214)">Пример</span>. У нас есть 3 сайза на терне: 
мы можем выгрузить с этого места и пересчитать за моно сайз:
> [!faq]- pic
>  ![[Pasted image 20250207001511.png]]

<span style="color:rgb(255, 99, 71)">90, 90, 90</span> - это серый фон!!!

> [!faq]- pic
>  ![[Pasted image 20250207002016.png]]

Кастомные статы: (шестеренка)
![[Pasted image 20250207004621.png]]
