# main-lab-2-dll
Программа, загружающая квадратную функции из библиотеки Lib2-1.dll и рисующая график этой функции.
** Нахождение кэффицентов a, b, c функции
y=a*x^2+b*x+c

при помощи анализа функции можно понять, что вершина параболы - x0 = 0, y0 = - 9

нахождение коэффицента a
произвольная координата функции - x = 3.2, y = 60
у=a(х-x0)^2 + y0  ==  60 = a (3.2 - 0)^2 - 9
=> a = 48,387
находим коэффицент b
x0 = -b/2a
=> b = 0
находим коэффицент c
у = ax^2 + bx + c  ==  -9 = 48,387 * 0 + 0 * 0 + c
=> c = - 9

формула - y = 48,387 * x^2 - 9
