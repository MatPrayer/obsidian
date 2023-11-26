# Sviluppi di [[Polinomio di Taylor - MacLaurin |MacLaurin]] fondamentali

Per $x\to 0$ valgono gli sviluppi delle funzioni elementari:

- **Funzione esponenziale**
$$e^x=\sum_{k=0}^n \frac{x^k}{k!}+o(x^n)$$
- **Funzione logaritmica naturale**
$$\ln(1+x)=\sum_{k=1}^n (-1)^{k-1}\frac{x^k}{k}+o(x^n)$$
- **Funzione seno** 
$$\sin(x)=\sum_{k=0}^{n}(-1)^k\frac{x^{2k+1}}{(2k+1)!}+o(x^{2n+2})$$
- **Funzione coseno**
$$\cos(x)=\sum_{k=0}^n(-1)^k\frac{x^{2k}}{(2k)!}+o(x^{2n+1})$$
- **Funzione seno iperbolico**
$$\sin(x)=\sum_{k=0}^{n}\frac{x^{2k+1}}{(2k+1)!}+o(x^{2n+2})$$
- **Funzione coseno iperbolico**
$$\cos(x)=\sum_{k=0}^n\frac{x^{2k}}{(2k)!}+o(x^{2n+1})$$
- **Funzione tangente**
$$\tan(x)=x+\frac{x^3}{3}+\frac{2}{15}x^5+o(x^6)\qquad\text{per }|x|<\frac{\pi}{2}$$
- **Funzione tangente inversa**
$$\arctan(x)=\sum_{k=0}^n(-1)^k\frac{x^{2k+1}}{2k+1}+o(x^{2n+1})$$
- **Sviluppo del binomio** *(con [[coefficiente binomiale]])*
$$(1+x)^\alpha=\sum_{k=0}^{n}\binom{\alpha}{k}x^k+o(x^n)$$
- **Sviluppo del binomio per $\alpha=-1$**
$$\frac{1}{1+x}=\sum_{k=0}^n(-1)^kx^k+o(x^n)$$
