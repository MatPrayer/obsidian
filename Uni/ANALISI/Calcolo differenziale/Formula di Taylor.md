---
~
---
Sia $f:(a,b)\to\Re$ una funzione derivabile in un punto $x_0\in (a,b)$:
$$\lim_{x\to x_0} \frac{f(x)-f(x_0)}{x-x_0}=f'(x_0)$$
equivale a:
$$\lim_{x\to x_0} \frac{f(x)-f(x_0)}{x-x_0}-f'(x_0)=0$$
ovvero:
$$\lim_{x\to x_0} \frac{f(x)-[f(x_0)+f'(x_0)(x-x_0)]}{x-x_0}=0$$

Utilizzando il simbolo di **o-piccolo** possiamo riscrivere la definizione di derivata come:
$$\lim_{x\to x_0} \overbrace{\frac{f(x)-[f(x_0)+f'(x_0)(x-x_0)]}{x-x_0}}^{f(x)-[f(x_0)+f'(x_0)(x-x_0)=o(x-x_0)\;\text{per }x\to x_0}=o(1)\quad \text{per }x\to x_0$$

La retta $f(x_0)+f'(x_0)(x-x_0)$ approssima il grafico della funzione $f(x)$ meglio di qualunque altra retta, perché $f(x)-[f(x_0)+f'(x_0)(x-x_0)$ è molto più piccolo di $x-x_0$.

### La retta tangente come migliore approssimante affine
Possiamo approssimare la funzione con un polinomio di grado $\le 1$, vicino al punto $x_0$:
$$f(x)=\underbrace{f(x_0)+f'(x_0)(x-x_0)}_{T_1(x)}+\underbrace{o(x-x_0)}_{\text{resto o errore}}\quad\text{per } x\to x_0$$
dove l'errore che si commette è un **infinitesimo di ordine superiore** a $x-x_0$ per $x\to x_0$.

### Approssimazione con polinomi di grado $n$

Data la funzione $f:(a,b)\to\Re, x_0\in (a,b)$,  possiamo approssimare $f$ ***vicino ad $x_0$*** con un polinomio $T_n(x)$ di grado $\le n$:

- Se $f$ è derivabile in $x_{0}$, è possibile con un polinomio di grado $\le 1$: