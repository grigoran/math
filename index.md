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
| 8   | $f(t)=(2+t)^2e^{-2t}+e^tcos4t$                                  | [Go](#8)  |
| 9   | $F(p)=\frac{e^p}{p-4}+\frac{p}{p^2+3p+\frac{5}{2}}$             | [Go](#9)  |
| 10  | $\int\limits_{-\frac{\pi}{2}}^{\frac{\pi}{2}}\frac{dx}{1+cosx}$ | [Go](#10) |
| 11  | $y''-4y'+3y=xe^x$                                               | [Go](#11) |
| 12  | $xy'-y+xtg\frac{y}{x}=0$                                        | [Go](#12) |
| 13  | $\int\frac{3xdx}{2x^2+3x-2}$ хз какие пределы интегрирования    | [Go](#13) |
| 14  | Не понятно                                                      | -         |
| 15  | $\sum\limits_{n=1}^\infin\frac{4^n}{n}(x-2)^n$                  | [Go](#15) |
| 16  | очко                                                            | -         |
| 17  | очко                                                            | -         |
| 18  | $\int\limits_0^1 xe^{-x}dx$                                     | [Go](#18) |
| 19  | $xy'-y=x^3$                                                     | [Go](#19) |
| 20  | $y''-4y'+3y=cos2x$                                              | [Go](#20) |
| 21  | $\sum\limits_{n=1}^\infin\frac{(-1)^n(n+2)}{n^2+4n-1}$          | [Go](#21) |
| 22  | $\sum\limits_{n=0}^\infty\frac{n}{3n-2}x^n$                     | [Go](#22) |

# Кратко

1.  $(x^2 - 2xy)dy=(xy-y^2)dx$

    - $\frac{y}{x}=u, y=ux, y'=u+u'x$

2.  $\int\limits_{-\frac{1}{7}}^{1}\frac{xdx}{\sqrt{8+2x-x^2}}$
    - В числителе +1-1
    - В знаменателе выделить полный квадрат
3.  $y'' +4y = 2cos2x$
    1.  $Y=e^{0x}(C_1cos2x+C_2sin2x)=C_1cos2x+C_2sin2x$
    2.  $\widetilde{y}=Axcos2x+Bxsin2x$ (подобрали с помощью таблицы по [ссылке](http://mathprofi.ru/kak_podobrat_chastnoe_reshenie_dy.pdf))
    3.  $y=Y+\widetilde{y}$
4.  $\sum\limits_{n=1}^\infin(\frac{4n+1}{3n^2+5})^n$
    - Признак Коши, лекции стр.152
    - Лопиталь
5.  $\int\limits_0^{e-1}ln(x+1)dx$
    - По частям
6.  $y'+\frac{1}{x}y=\frac{sinx}{x}$
    - $y=uv, y'=u'v+uv'$
7.  $\sum\limits_{n=1}^\infin\frac{2n+1}{n!}x^n$
    - $R=lim_{n\to\infin}|\frac{a_n}{a_{n+1}}|$ - радиус сходимости
8.  $f(t)=(2+t)^2e^{-2t}+e^tcos4t$
    - Теорема смещения
    - табличка
9.  $F(p)=\frac{e^p}{p-4}+\frac{p}{p^2+3p+\frac{5}{2}}$
    - Теорема запаздывания
    - Теорема смещения
    - табличка
10. $\int\limits_{-\frac{\pi}{2}}^{\frac{\pi}{2}}\frac{dx}{1+cosx}$
    - Повысить степень косинуса
11. $y''-4y'+3y=xe^x$
    1.  $Y=C_1e^x+C_2e^{3x}$
    2.  $\widetilde{y}=x(Ax+B)e^x$ (подобрали с помощью таблицы по [ссылке](http://mathprofi.ru/))
    3.  $y=Y+\widetilde{y}$
12. $xy'-y+xtg\frac{y}{x}=0$
    - $u=\frac{y}{x}; y=ux; y'=u+u'x$
13. $\int\frac{3xdx}{2x^2+3x-2}$
    - Разложение знаменателя на множетели
    - +2-2
    - Разложение на простые дроби
14. Не понятно
15. $\sum\limits_{n=1}^\infin\frac{4^n}{n}(x-2)^n$
    - $R=lim_{n\to\infin}|\frac{a_n}{a_{n+1}}|$ - радиус сходимости
    - На забыть проверить концы
16. 0
17. 0
18. $\int\limits_0^1 xe^{-x}dx$
    - по частям
19. $xy'-y=x^3$

    - $y=uv, y'=u'v+uv'$

20. $y''-4y'+3y=cos2x$
    1.  $Y=C_1e^{3x}+C_2e^x$
    2.  $\widetilde{y}=Acos2x+Bsin2x$
21. $\sum\limits_{n=1}^\infin\frac{(-1)^n(n+2)}{n^2+4n-1}$
    - достаточный признак сходимости рядов с членами произвольных знаков
22. $\sum\limits_{n=0}^\infty\frac{n}{3n-2}x^n$
    - $R=lim_{n\to\infin}|\frac{a_n}{a_{n+1}}|$ - радиус сходимости

# 1

> **Есть в лекции, стр.86**

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

> **Есть в лекции стр.152**

$\sum\limits_{n=1}^\infty(\frac{4n+1}{3n^2+5})^n$

Признак Коши, лекции стр.152

$\underset{n\to\infty}{lim}\frac{4n+1}{3n^2+5}=[\frac{\infty}{\infty}]$

Применим правило Лопиталя

$\underset{n\to\infty}{lim}\frac{4n+1}{3n^2+5}=
\underset{n\to\infty}{lim}\frac{4}{6n}=0$

Ответ: ряд сходится

# 5

> **Берман: №2264, стр 146**

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

> **Есть в лекции стр.89**

![number6](./img/6.png)

См. Лекции стр. 89

# 7

> **Есть в лекцииб стр.169**

В этом номере степенной ряд
$\sum\limits_{n=0}^\infty\frac{n}{3n-2}x^n$
В теории степенных рядов центральное место занимает следующая
теорема:

![teorema](img/teorema_7.png)

Решение:

![number7](./img/7.png)

Ответ: ряд сходится на всей числовой прямой

# 8

$f(t)=(2+t)^2e^{-2t}+e^tcos4t$

$(2+t)^2e^{-2t} = (t^2+4t+4)e^{-2t} = t^2e^{-2t} +4te^{-2t} +4e^{-2t}$

$(2+t)^2e^{-2t} \doteqdot \frac{2}{(p+2)^3}+\frac{4}{(p+2)^2}+\frac{4}{p+2}$

$e^tcos4t \doteqdot \frac{p-1}{(p-1)^2+16}$

Ответ: $F(p)=\frac{2}{(p+2)^3}+\frac{4}{(p+2)^2}+\frac{4}{p+2}+\frac{p-1}{(p-1)^2+16}$

# 9

$F(p)=\frac{e^p}{p-4}+\frac{p}{p^2+3p+\frac{5}{2}}$

> $\frac{e^p}{p-4}, \tau=-1 \doteqdot e^{4(t+1)}$ (По теореме запаздывания)

$\frac{p}{p^2+3p+\frac{5}{2}} = \frac{p}{p^2+3p+\frac{9}{4}+\frac{1}{4}}=$
$\frac{p+\frac{3}{2}-\frac{3}{2}}{(p+\frac{3}{2})^2+\frac{1}{4}}=$
$\frac{p+\frac{3}{2}}{(p+\frac{3}{2})^2+\frac{1}{4}}-3\frac{\frac{1}{2}}{(p+\frac{3}{2})^2+\frac{1}{4}}$
$\doteqdot e^{-\frac{3}{2}t}cos\frac{t}{2}-3e^{-\frac{3}{2}t}sin\frac{t}{2}$ (по теореме смещения)

$f(t)=e^{4(t+1)}+e^{-\frac{3}{2}t}cos\frac{t}{2}-3e^{-\frac{3}{2}t}sin\frac{t}{2}$

# 10

> **Берман: №2251, стр 146**

$$
\int\limits_{-\pi/2}^{\pi/2}\frac{dx}{1+\cos{x}}
=2\int\limits_{0}^{\pi/2}\frac{dx}{1+\cos{x}}
=2\int\limits_{0}^{\pi/2}\frac{d\left(\frac{x}{2}\right)}{\cos^2\frac{x}{2}}
=2\cdot\left.\tg\frac{x}{2}\right|_{0}^{\pi/2}
=2.
$$

# 11

> **Есть в лекции, стр.107**

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
  $\sum\limits_{n=0}^\infty\frac{n}{3n-2}x^n$
  $-ln(sinu)=lnx-lnc$

$ln(\frac{1}{sinu})=ln(\frac{c}{x})$

Ответ: $c\cdot sin\frac{y}{x}=x$

# 13

$\int\frac{3xdx}{2x^2+3x-2}$

- $2x^2+3x-2=(x+2)(x-\frac{1}{2})$ (Разложил на множители)

$3\int\frac{(x+2-2)dx}{(x+2)(x-\frac{1}{2})}=3\int\frac{dx}{x-\frac{1}{2}}-6\int\frac{dx}{(x+2)(x-\frac{1}{2})}$

- $\frac{1}{(x+2)(x-\frac{1}{2})}=\frac{2}{5}\frac{1}{x-\frac{1}{2}}-\frac{2}{5}\frac{1}{x+2}$ (Разложил на простые дроби)

$\int\frac{3xdx}{2x^2+3x-2}=\frac{3ln|x-\frac{1}{2}|+12ln|x+2|}{5}+c$

# 15

$\sum\limits_{n=1}^\infin\frac{4^n}{n}(x-2)^n$

$R=lim_{n\to\infin}|\frac{a_n}{a_{n+1}}|$

$R=lim_{n\to\infin}\frac{n+1}{n\cdot4\cdot(x-2)}=\frac{1}{4}, -\frac{1}{4}<x-2<\frac{1}{4}\Rightarrow(\frac{7}{4};\frac{9}{4})$

$x=\frac{7}{4}: lim_{n\to\infin}\frac{4^n}{n}(-\frac{1}{4})^n=0 \Rightarrow$ сходится

$x=\frac{9}{4}: lim_{n\to\infin}\frac{4^n}{n}(\frac{1}{4})^n=0 \Rightarrow$ сходится

Ответ: интервал сходимости $[\frac{7}{4};\frac{9}{4}]$

# 18

> **Берман: №2259, стр 146**

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

> **Есть в лекции, стр. 89, 100**

## Вариант 1

![number19](./img/19.png)

См. Лекции стр. 89

## Вариант 2 (Метод вариации произвольной постоянной)

![number19](./img/19_2.png)

См. Лекции стр. 100

# 20

$y''-4y'+3y=cos2x$

1. $r^2-4r+3=0$

   $r_1=3,r_2=1$

   $Y=C_1e^{3x}+C_2e^x$

2. $\widetilde{y}=Acos2x+Bsin2x$

   $\widetilde{y}' = -2Asin2x +2Bcos2x$

   $\widetilde{y}''=-4Acos2x-4Bsin2x$

   $(8A-B)sin2x+(-8B-A)*cos2x=cos2x$

   $
   \begin{cases}
   8A-B=0\\
   -8B-A=1
   \end{cases}
   $,
   $
   \begin{cases}
   B=-\frac{8}{65}\\
   A=-\frac{1}{65}
   \end{cases}
   $

   $\widetilde{y}=-\frac{1}{65}cos2x-\frac{8}{65}sin2x$

3. $y=Y+\widetilde{y}=C_1e^{3x}+C_2e^x-\frac{1}{65}cos2x-\frac{8}{65}$

# 21

$\sum\limits_{n=1}^\infin\frac{(-1)^n(n+2)}{n^2+4n-1}$(1)

$lim_{n\to\infin}\frac{n+2}{n^2+4n-1}=0 \Rightarrow$
ряд (1) сходится по достаточному признаку сходимости ряда с членами произвольных знаков

# 22

> **Есть в лекции стр.168**

![number22](./img/22.png)
