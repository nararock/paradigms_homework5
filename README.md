#Мое решение<br>
sum_arr([], 0). <br>
sum_arr([H|T], Sum) :- <br>
   sum_arr(T, R),<br>
   Sum is H + R.<br>
