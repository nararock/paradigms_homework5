#Мое решение
sum_arr([], 0).
sum_arr([H|T], Sum) :-
   sum_arr(T, R),
   Sum is H + R.
