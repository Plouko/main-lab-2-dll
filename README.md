# main-lab-2-dll
Программа, загружающая квадратную функции из библиотеки Lib2-1.dll и рисующая график этой функции.
## Нахождение кэффицентов a, b, c функции
y=a*x^2+b*x+c

при помощи анализа функции можно понять, что вершина параболы - x0 = 0, y0 = - 9<br />
нахождение коэффицента a<br />
произвольная координата функции - x = 3.2, y = 60<br />
у=a(х-x0)^2 + y0  ==  60 = a (3.2 - 0)^2 - 9<br />
=> a = 48,387<br />
находим коэффицент b<br />
x0 = -b/2a<br />
=> b = 0<br />
находим коэффицент c<br />
у = ax^2 + bx + c  ==  -9 = 48,387 * 0 + 0 * 0 + c<br />
=> c = - 9<br />

формула - y = 48,387 * x^2 - 9<br />
