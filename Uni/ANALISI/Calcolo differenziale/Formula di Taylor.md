---
~
---
Sia $f:(a,b)\to\R$ una funzione derivabile in un punto $x_0\in (a,b)$:
$$\lim_{x\to x_0} \frac{f(x)-f(x_0)}{x-x_0}=f'(x_0)$$
equivale a:
$$\lim_{x\to x_0} \frac{f(x)-f(x_0)}{x-x_0}-f'(x_0)=0$$
ovvero:
$$\lim_{x\to x_0} \frac{f(x)-[f(x_0)+f'(x_0)(x-x_0)]}{x-x_0}=0$$

Utilizzando il simbolo di **o-piccolo** possiamo riscrivere la definizione di derivata come:
$$\lim_{x\to x_0} \overbrace{\frac{f(x)-[f(x_0)+f'(x_0)(x-x_0)]}{x-x_0}}^{f(x)-[f(x_0)+f'(x_0)(x-x_0)=o(x-x_0)\;\text{per }x\to x_0}=o(1)\quad \text{per }x\to x_0$$

La retta $f(x_0)+f'(x_0)(x-x_0)$ approssima il grafico della funzione $f(x)$ meglio di qualunque altra retta, perché $f(x)-[f(x_0)+f'(x_0)(x-x_0)$ è molto più piccolo di $x-x_0$.

### La retta tangente come migliore approssimante affine
Definizione equivalente di $f(x)$ derivabile in $x_0$:
$$f(x)=\underbrace{f(x_0)+f'(x_0)(x-x_0)}_{T_1(x)}+\underbrace{o(x-x_0)}_{\text{resto o errore}}\quad\text{per } x\to x_0$$
