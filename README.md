**Мое решение**<br>
sum_arr([], 0). <br>
sum_arr([H|T], Sum) :- <br>
&nbsp; sum_arr(T, R),<br>
&nbsp; Sum is H + R.<br>
