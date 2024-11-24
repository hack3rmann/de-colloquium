## Понятие решения ОДУ. Постановка задачи с начальными данными (задача Коши) для разрешенного относительно производной ОДУ 1-го порядка. Геометрический смысл задачи Коши.

### Понятие решения ОДУ

Фукнция $\phi: [a, b] \rightarrow \mathbb{R}$ называется **решением дифференциального уравнения** $F(x, y, y', \dots, y^{(n)}) = 0$, если $\forall x \in [a, b]: F(x, \phi(x), \phi'(x), \dots, \phi^{(n)}(x)) = 0$. График функции $\phi$ называется **интегральной кривой**.

### Постановка задачи с начальными данными (задача Коши) для разрешенного относительно производной ОДУ 1-го порядка

Пусть функция $f(x, y)$ определена и непрерывна в прямоугольнике $\Pi = [x_0 - A, x_0 + A] \times [y_0 - B, y_0 + B]$, тогда система $$\begin{cases}
	y'(x) = f(x, y(x)) \\
	y(x_0) = y_0
\end{cases}$$на отрезке $[x_0 - A, x_0 + A]$ называется **задачей с начальными данными** или **задачей Коши**.

Рассмотрим отрезок $[x_1, x_2]$ такой, что $x_0 - A \le x_1 < t_2 \le x_0 + A, x_0 \in [x_1, x_2]$. Функция $\overline{y}(x)$ называется решением задачи Коши на отрезке $[x_1, x_2]$, если

1. $\overline{y} \in C^1[x_1, x_2]$
2. $\forall x \in [x_1, x_2]: \left|\overline{y}(x) - y_0\right| \le B$
3. Функция $\overline{y}$ удовлетворяет системе задачи Коши

### Геометрический смысл задачи Коши

Пусть $y(x)$ – решение задачи Коши на отрезке $[a, b]$. Рассмотрим на плоскости множество точек $(x, y(x)), \: x \in [a, b]$. Это множество представляет собой интегральную кривую. Из определения решения следует, что в каждой точке интегральной кривой существует касательная. Направляющий вектор касательной к интегральной кривой в точке $(x_0, y(x_0))$ равен $(1, f(x_0, y(x_0))$.

![[InitialConditionProblemGeometricMeaning.png]]