#Мое решение
sum_arr([], 0). <br>
sum_arr([H|T], Sum) :-
   sum_arr(T, R),
   Sum is H + R.
