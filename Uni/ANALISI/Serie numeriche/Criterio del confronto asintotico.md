Date due [[Successioni|successioni]] $(a_{n})_{n}$ e $(b_{n})_{n}$ a [[Serie a termini positivi|termini positivi]], diciamo che sono ***asintotiche*** per $n\to +\infty$ (in simboli, $a_{n}\backsim b_{n}$ per $n\to +\infty$) se si ha: ^1ff502
$$
\lim_{ n \to \infty } \frac{a_{n}}{b_{n}}=1\quad\text{ovvero}\quad a_{n}=b_{n}+o(b_{n})\quad\text{per }n\to +\infty
$$
>**Nota bene**
>La relazione di *asintotico* è un'equivalenza (quindi riflessiva, simmetrica e transitiva).

## Teorema del criterio del confronto asintotico
Siano $a_{n}$ e $b_{n}$ a termini positivi. Supponiamo che esista $\lim_{ n \to \infty } \frac{a_{n}}{b_{n}}=L$. Allora:

1. Nel caso $L=0$,$$
\sum_{n=0}^{+\infty}b_{n}<+\infty\implies\sum_{n=0}^{+\infty}a_{n}<+\infty
$$
2. Nel caso $L=+\infty$, $$
\sum_{n=0}^{+\infty}b_{n}=+\infty\implies\sum_{n=0}^{+\infty}a_{n}=+\infty
$$
3. Nel caso $0<L<+\infty$, le due serie $\sum_{n=0}^{+\infty}a_{n}\text{ e }\sum_{n=0}^{+\infty}b_{n}$ hanno lo stesso carattere.

In particolare, se $a_{n}$ e $b_{n}$ sono successioni a termini positivi e verificano $a_{n}\backsim b_{n}$ per $n\to +\infty$, allora le due serie $\sum_{n=0}^{+\infty}a_{n}$ e $\sum_{n=0}^{+\infty}b_{n}$

### Esempi

- $\log\left( 1+\frac{1}{n} \right)\sim \frac{1}{n}$, quindi la **serie armonica** $\sum_{n=1}^{+\infty} \frac{1}{n}$ è divergente a $+\infty$
- $\frac{1}{n(n+1)}\sim \frac{1}{n^2}$, quindi la serie $\sum_{n=1}^{+\infty} \frac{1}{n^2}$ è convergente


