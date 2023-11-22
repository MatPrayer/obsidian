**Domanda:** il [[Polinomio di Taylor - MacLaurin |polinomio di Taylor]] $T_n(x)$ di una funzione $f$ centrato in un punto $x_0$ è una *buona approssimazione* di $f$ vicino al punto $x_0$?

Per $n=1$, sappiamo che $t_1(x)=f(x_{0})+f'(x_{0})(x-x_{0})$ rappresenta la retta tangente al grafico di $f$ nel punto $(x_{0}),f(x_{0})$ e vale:
$$f\text{ derivabile in }x_{0}\quad\implies\quad f(x)=T_1(x)+o(x-X_0)\text{ per }x\tox_0$$
Vale una proprietà analoga per il polinomio di Taylor di ordine $n>1$:

## Teorema della [[Formula di Taylor |formula di Taylor]] con resto di Peano

Sia $f:(a,b)\to\Re$ derivabile $n$ volte ($n\ge 1$) in un punto $x_0\in(a,b)$. Allora

$$T_{n}(x)=\sum_{k=0}^n\frac{f^k(x_{0})}{k!}(x-x_{0})^k+\color{#00BDFF}o((x-x_0)^n)\color{#ffffff}\quad\text{per }x\to x_0$$

>**Osservazione**
>Il significato della formula è che *l'errore che si commette approssimando $f$ con il suo polinomio di Taylor di ordine $n$ centrato in $x_0$ è* $o((x-x_0)^n$, cioè *tende a 0 più velocemente di $(x-x_0)^n$ per $x\to x_0$*.

>**Attenzione**
>Il ***resto nella forma di Peano***  **non permette una stima quantitativa dell'errore** in un punto $x\ne x_0$, per quanto vicino $x$ possa essere ad $x_0$ . 
>Si tratta invece di un'informazione sull'**ordine di convergenza** a zero dell'errore per $x\to x_0$.