# Как быть победителем в казино? Возможно ли это?
Для ответа на этот вопрос размещаю здесь результат исследования - график исходов вариантов игры.
Оказывается, что бы выиграть в казино, нужно изменить правила игры.
<br>
<br/>
<img src="https://github.com/IYuminov/Casino_to_be_a_winner/blob/main/casino_plot.png?raw=true" height="400"/>
<br>
<br/>
<h3> 
Некоторые подробности: 
</h3>

- Количество денег на счету установлено 1.000.000 у.е., для каждой стратегии;

- Ставка всегда 1.000 у.е. и на однин цвет ячейки (черное);

- Игр в каждой стратегии было 39.764;

- В роли рулетки выступал randint из библиотеки random.
<br/>
<h3> 
Стратегия 1:
</h3>
Классический вариант игры - то как и играют в казино (18 черных ячеек, 18 красных и 1 зеленая - zero)
<br>
Исход стратегии 1:
<img src="https://github.com/IYuminov/Casino_to_be_a_winner/blob/main/I_strategy.png?raw=true" height="80"/>

Осталось 11.000 у.е. (!!!) сыграв 
<br/>
<h3>
Стратегия 2:
</h3>
Меняю правила игры - 18 черных ячеек, 18 красных, без zero.
<br>
Исход стратегии 2:
<img src="https://github.com/IYuminov/Casino_to_be_a_winner/blob/main/II_strategy.png?raw=true" height="80"/>

Осталось около 818.000 у.е.
<br/>
<h3>
Стратегия 3:
</h3>
Новые правила игры - 18 черных ячеек, 17 красных, без zero.
<br>
Исход стратегии 3:
<img src="https://github.com/IYuminov/Casino_to_be_a_winner/blob/main/III_strategy.png?raw=true" height="80"/>

Выигрыш составил около 1.600.000 у.е.
<br/>

# Вывод:
Выиграть или выйти в ноль получится только если увеличить количество выигрышных вариантов, то есть заменить рулетку.
В ином случае рулетка будет неуклонно уменьшать размер кошелька. 
