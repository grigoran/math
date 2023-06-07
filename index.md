<!-- title: Вопросы матан -->

| №   | Задание                                                         | Решение   |
| --- | --------------------------------------------------------------- | --------- |
| 1   | $(x^2 - 2xy)dy=(xy-y^2)dx$                                      | [Go](#1)  |
| 2   | $\int\limits_{-\frac{1}{7}}^{1}\frac{xdx}{\sqrt{8+2x-x^2}}$     | [Go](#2)  |
| 3   | $y'' +4y = 2cos2x$                                              | [Go](#3)  |
| 4   | $\sum\limits_{n=1}^\infin(\frac{4n+1}{3n^2+5})^n$               | [Go](#4)  |
| 5   | $\int\limits_0^{e-1}ln(x+1)dx$                                  | [Go](#5)  |
| 6   | $y'+\frac{1}{x}y=\frac{sinx}{x}$                                | [Go](#6)  |
| 7   | $\sum\limits_{n=1}^\infin\frac{2n+1}{n!}x^n$                    | [Go](#7)  |
| 8   | -                                                               | -         |
| 9   | -                                                               | -         |
| 10  | $\int\limits_{-\frac{\pi}{2}}^{\frac{\pi}{2}}\frac{dx}{1+cosx}$ | [Go](#10) |
| 11  | $y''-4y'+3y=xe^x$                                               | [Go](#11) |
| 12  | $xy'-y+xtg\frac{y}{x}=0$                                        | [Go](#12) |
| 13  | -                                                               | -         |
| 14  | -                                                               | -         |
| 15  | -                                                               | -         |
| 16  | -                                                               | -         |
| 17  | -                                                               | -         |
| 18  | $\int\limits_0^1 xe^{-x}dx$                                     | [Go](#18) |
| 19  | $xy'-y=x^3$                                                     | [Go](#19) |
| 20  | -                                                               | -         |
| 21  | -                                                               | -         |
| 22  | -                                                               | -         |

# 1

**Есть в лекции**

![number1](./img/1.png)

Дифференциальное уравнение первого порядка называется однородным
если оно может быть представлено в виде 𝑦′ = 𝑓(𝑥, 𝑦). См. Лекции стр. 86

# 2

$$
\int\limits_{-\frac{1}{7}}^{1}\frac{xdx}{\sqrt{8+2x-x^2}} =
\int\limits_{-\frac{1}{7}}^{1}\frac{(x-1+1)dx}{\sqrt{9-(x-1)^2}} =
\int\limits_{-\frac{1}{7}}^{1}\frac{(x-1)dx}{\sqrt{9-(x-1)^2}}+
\int\limits_{-\frac{1}{7}}^{1}\frac{dx}{\sqrt{9-(x-1)^2}} =
arcsin(\frac{x-1}{3}) - \sqrt{9-(x-1)^2} \Bigg|_{-\frac{1}{7}}^1
$$

# 3

Решить неоднородное дифференциальное уравнение
второго порядка $y'' +4y = 2cos2x$

1. Сначала нужно найти общее решение $Y$ соответствующего однородного уравнения.
2. Необходимо найти какое-либо частное решение $\widetilde{y}$ неоднородного уравнения
3. составить общее решение $y=Y+\widetilde{y}$ неоднородного уравнения

Решение:

1. $\lambda^2+4=0$

   $\lambda^2=-4$

   $\lambda=\pm2i$

   $Y=e^{0x}(C_1cos2x+C_2sin2x)=C_1cos2x+C_2sin2x$

2. $\widetilde{y}=Axcos2x+Bxsin2x$ (подобрали с помощью таблицы по [ссылке](http://mathprofi.ru/kak_podobrat_chastnoe_reshenie_dy.pdf))

   $\widetilde{y}'=Acos2x-2Asin2x+Bsin2x+2Bcos2x$

   $\widetilde{y}''=-2Asin2x-2Asin2x-4Axcos2x+2Bcos2x+Bcos2x-4Bxsin2x=$

   $=4(-Asin2x-Axcos2x+Bcos2x-Bxsin2x)$

   Подставляем в исходное уравнение

   $4(-Asin2x-Axcos2x+Bcos2x-Bxsin2x)+4(Axcos2x+Bxsin2x)=$

   $=-4Asin2x+4Bcos2x=f(x), f(x) = 2cos2x$

   $-4Asin2x+4Bcos2x=2cos2x$

   $A=0; B=\frac{1}{2}$

   $\widetilde{y}=\frac{1}{2}xsin2x$ (частное решение)

3. $y=Y+\widetilde{y}$

   Ответ: $y=C_1cos2x+C_2sin2x+\frac{1}{2}xsin2x$

# 4

$\sum\limits_{n=1}^\infty(\frac{4n+1}{3n^2+5})^n$

Признак Коши, лекции стр.152

$\underset{n\to\infty}{lim}\frac{4n+1}{3n^2+5}=[\frac{\infty}{\infty}]$

Применим правило Лопиталя

$\underset{n\to\infty}{lim}\frac{4n+1}{3n^2+5}=
\underset{n\to\infty}{lim}\frac{4}{6n}=0$

Ответ: ряд сходится

# 5

**Берман: №2264, стр 146**

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

**Есть в лекции**

![number6](./img/6.png)

См. Лекции стр. 89

# 7

**Есть в лекции**

В этом номере степенной ряд

В теории степенных рядов центральное место занимает следующая
теорема:

![teorema](img/teorema_7.png)

Решение:

![number7](./img/7.png)

Ответ: ряд сходится на всей числовой прямой

# 10

**Берман: №2251, стр 146**

$$
\int\limits_{-\pi/2}^{\pi/2}\frac{dx}{1+\cos{x}}
=2\int\limits_{0}^{\pi/2}\frac{dx}{1+\cos{x}}
=2\int\limits_{0}^{\pi/2}\frac{d\left(\frac{x}{2}\right)}{\cos^2\frac{x}{2}}
=2\cdot\left.\tg\frac{x}{2}\right|_{0}^{\pi/2}
=2.
$$

# 11

**Есть в лекции**

![number19](./img/11.png)

См. Лекции стр. 107

# 12

$xy'-y+xtg\frac{y}{x}=0$

$y'=\frac{y}{x}-tg\frac{y}{x}$

$u=\frac{y}{x}; y=ux; y'=u+u'x$

$u+u'x=u-tgu$

$\frac{x}{dx}=-\frac{tgu}{du}$

$\int\frac{-1}{tgu}du=\int\frac{dx}{x}$

- $\int\frac{-1}{tgu}du=-\int\frac{cosu}{sinu}du = -\int\frac{1}{sinu}dsinu=-ln(sinu)+c$

$-ln(sinu)=lnx-lnc$

$ln(\frac{1}{sinu})=ln(\frac{c}{x})$

Ответ: $c\cdot sin\frac{y}{x}=x$

# 18

**Берман: №2259, стр 146 но нет в решебнике**

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

**Есть в лекции**

## Вариант 1

![number19](./img/19.png)

См. Лекции стр. 89

## Вариант 2 (Метод вариации произвольной постоянной)

![number19](./img/19_2.png)

См. Лекции стр. 100
