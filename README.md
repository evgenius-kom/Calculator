# Calculator

Грамматика калькулятора:

expr = term
    | expr + term
    | expr - term
term = prim
    | term * prim
    | term / prim
prim = number
    | -number
number = [0-9]+
