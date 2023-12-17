# Sviluppi di [[Polinomio di Taylor - MacLaurin |MacLaurin]] fondamentali

Per $x\to 0$ valgono gli sviluppi delle funzioni elementari:

- **Funzione esponenziale**
$$e^x=\sum_{k=0}^n \frac{x^k}{k!}+o(x^n)$$
$$
e^x=1+x+\frac{x^2}{2}+\frac{x^3}{6}+\frac{x^4}{24}+\dots+\frac{x^n}{n|}+o(x^n)
$$
- **Funzione logaritmica naturale**
$$\ln(1+x)=\sum_{k=1}^n (-1)^{k-1}\frac{x^k}{k}+o(x^n)$$
$$
\ln(1+x)=x-\frac{x^2}{2}+\frac{x^3}{3}-\frac{x^4}{4}+\dots+\frac{(-1)^{n+1}}{n}x^n+o(x^n)
$$
- **Funzione seno** 
$$\sin(x)=\sum_{k=0}^{n}(-1)^k\frac{x^{2k+1}}{(2k+1)!}+o(x^{2n+2})$$
$$
\sin(x)=x-\frac{x^3}{6}+\frac{x^5}{120}-\frac{x^7}{5040}+\dots+\frac{(-1)^nx^{2n+1}}{(2n+1)!}+o(x^{2n+1})
$$
- **Funzione coseno**
$$\cos(x)=\sum_{k=0}^n(-1)^k\frac{x^{2k}}{(2k)!}+o(x^{2n+1})$$
$$
\cos(x)=1-\frac{x^2}{2}+\frac{x^4}{24}-\frac{x^6}{720}+\dots+\frac{(-1)^nx^{2n}}{(2n)!}+o(x^{2n})
$$
- **Funzione seno iperbolico**
$$\sin(x)=\sum_{k=0}^{n}\frac{x^{2k+1}}{(2k+1)!}+o(x^{2n+2})$$
$$
\sinh(x)=x+\frac{x^3}{6}+\frac{x^5}{120}+\frac{x^7}{5040}+o(x^7)
$$
- **Funzione coseno iperbolico**
$$\cos(x)=\sum_{k=0}^n\frac{x^{2k}}{(2k)!}+o(x^{2n+1})$$
$$
\cosh(x)=1+\frac{x^2}{2}+\frac{x^4}{24}+\frac{x^6}{720}+o(x^{6})
$$
- **Funzione tangente**
$$\tan(x)=x+\frac{x^3}{3}+\frac{2}{15}x^5+o(x^6)\qquad\text{per }|x|<\frac{\pi}{2}$$
- **Funzione arcotangente**
$$\arctan(x)=\sum_{k=0}^n(-1)^k\frac{x^{2k+1}}{2k+1}+o(x^{2n+1})$$
$$
\arctan(x)=x-\frac{x^3}{3}+\frac{x^5}{5}-\frac{x^7}{7}+o(x^7)
$$
- **Sviluppo del binomio** *(con [[coefficiente binomiale]])*
$$(1+x)^\alpha=\sum_{k=0}^{n}\binom{\alpha}{k}x^k+o(x^n)$$
$$
(1+x)^\alpha=\frac{\alpha(\alpha-1)(\alpha-2)\ldots(\alpha-n+1)}{n!}x^n
$$
- **Sviluppo del binomio per $\alpha=-1$**
$$\frac{1}{1+x}=\sum_{k=0}^n(-1)^kx^k+o(x^n)$$

