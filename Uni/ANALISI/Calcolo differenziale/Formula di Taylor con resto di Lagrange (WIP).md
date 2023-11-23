## Teorema della [[Formula di Taylor |formula di Taylor]] con resto di Lagrange

Sia $f:(a,b)\to\Re,\quad x_0\in(a,b),\quad f$ derivabile $n+1$ volte in $(a,b)$.
Allora $\forall x\in(a,b), x\ne x_0$,  esiste un punto $\xi$ compreso tra $x_0$ ed $x$ tale che:
$$f(x)=\sum_{k=0}^n\frac{f^{(k)}(x_0)}{k!}(x-x_0)+\color{#00BDFF}\frac{f^{(n+1)}(\xi)}{(n+1)!}(x-x_0)^{n+1}$$
>Il punto $\xi$ dipende da $x,x_0$ e $n$

>Per $n=0$ otteniamo che 
>$$f(x)=f(x_0)+f'(\xi)(x-x_{0})$$
>per un punto $\xi$ compreso tra $x_{0}$ ed $x$, cioè il [[Teorema di Lagrange]]

>**Osservazione**
>Il ***resto nella forma di Lagrange*** permette una **stima quantitativa** dell'errore che si commette nell'approssimazione in un punto $x\ne x_{0}$