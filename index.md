<!-- title: Вопросы матан -->

1. $(x^2 - 2xy)dy=(xy-y^2)dx$ [Решение](#1) **Есть в лекции**
2. $\int\limits_{-\frac{1}{7}}^{1}\frac{xdx}{\sqrt{8+2x-x^2}}$ [Решение](#2) **Решил, но не нашел**
3. $y' +4y = 2cos2x$
4. $\sum\limits_{n=1}^\infin(\frac{4n+1}{3n^2+5})^n$
5. $\int\limits_0^{e-1}ln(x+1)dx$ [Решение](#5) **№2264, стр 146**
6. $y'+\frac{1}{x}y=\frac{sinx}{x}$ [Решение](#6) **Есть в лекции**
7. $\sum\limits_{n=1}^\infin\frac{2n+1}{n!}x^n$ [Решение](#7) **Есть в лекции**
8. -
9. -
10. $\int\limits_{-\frac{\pi}{2}}^{\frac{\pi}{2}}\frac{dx}{1+cosx}$ [Решение](#11) **№2251, стр 146**
11. $y''-4y'+3y=xe^x$ [Решение](#11) **Есть в лекции**
12. -
13. -
14. -
15. -
16. -
17. -
18. $\int\limits_0^1 xe^{-x}dx$ [Решение](#18) **№2259, стр 146 но нет в решебнике**
19. $xy'-y=x^3$ [Решение](#19) **Есть в лекции**
20. -
21. -
22. -

# 1

![number1](./img/1.png)

Дифференциальное уравнение первого порядка называется однородным
если оно может быть представлено в виде 𝑦′ = 𝑓(𝑥, 𝑦). См. Лекции стр. 86

# 2

$
\int\limits_{-\frac{1}{7}}^{1}\frac{xdx}{\sqrt{8+2x-x^2}} =
\int\limits_{-\frac{1}{7}}^{1}\frac{(x-1+1)dx}{\sqrt{9-(x-1)^2}} =
\int\limits_{-\frac{1}{7}}^{1}\frac{(x-1)dx}{\sqrt{9-(x-1)^2}}+
\int\limits_{-\frac{1}{7}}^{1}\frac{dx}{\sqrt{9-(x-1)^2}} =
arcsin(\frac{x-1}{3}) - \sqrt{9-(x-1)^2} \Bigg|_{-\frac{1}{7}}^1
$

# 5

Интегрируем по частям

$$
\int\limits_{0}^{e-1}\ln(x+1)dx
=\left[\begin{aligned}
& u=\ln(x+1);\;du=\frac{dx}{x+1};\\
& dv=dx;\;v=x.
\end{aligned}\right]
=\left.x\ln(x+1)\right|_{0}^{e-1}-\int\limits_{0}^{e-1}\frac{xdx}{x+1}=\\
=e-1-\int\limits_{0}^{e-1}\frac{x+1-1}{x+1}dx
=e-1-\int\limits_{0}^{e-1}\left(1-\frac{dx}{x+1}\right)dx
=e-1-\left.\left(x-\ln(x+1)\right)\right|_{0}^{e-1}
=1
$$

# 6

![number6](./img/6.png)

См. Лекции стр. 89

# 7

В этом номере степенной ряд

В теории степенных рядов центральное место занимает следующая
теорема:

![teorema](img/teorema_7.png)

Решение:

![number7](./img/7.png)

# 10

$$
\int\limits_{-\pi/2}^{\pi/2}\frac{dx}{1+\cos{x}}
=2\int\limits_{0}^{\pi/2}\frac{dx}{1+\cos{x}}
=2\int\limits_{0}^{\pi/2}\frac{d\left(\frac{x}{2}\right)}{\cos^2\frac{x}{2}}
=2\cdot\left.\tg\frac{x}{2}\right|_{0}^{\pi/2}
=2.
$$

# 11

![number19](./img/11.png)

См. Лекции стр. 107

# 18

Интегрируем по частям

$$
\int\limits_{0}^{1}xe^{-1}dx
=\left[\begin{aligned}
& u=x;du=dx\\
& dv=e^{-x}dx;v=-e^{-x}
\end{aligned}\right]
= -xe^{-x}\bigg|_0^1 + \int\limits_0^1 e^{-x}dx = (-xe^{-x} -e^{-x}) \bigg|_0^1 = -e^{-x}(x+1)\bigg|_0^1 = -2e^{-1}+e^0 = 1-\frac{2}{e}
$$

# 19

## Вариант 1

![number19](./img/19.png)

См. Лекции стр. 89

## Вариант 2 (Метод вариации произвольной постоянной)

![number19](./img/19_2.png)

См. Лекции стр. 100
