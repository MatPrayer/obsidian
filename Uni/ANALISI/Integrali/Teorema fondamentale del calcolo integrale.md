Sia $f:[a,b]\to\Re$ una [[Criteri di integrabilità|funzione integrabile]] e sia $x_{0}\in[a,b]$.
Sia poi $F(x)=\int_{x_{0}}^xf(t)  \, dt$ la [[La funzione integrale|funzione integrale]] di $f$. Allora:
- $f$ è [[Funzioni continue|continua]]
- se $f$ è continua in un punto $\overline{x}\in(a,b)$ allora $F$ è [[Definizione di Derivata#^46cfc1|derivabile]] in $\overline{x}$ e
$$F'(\overline{x})=f(\overline{x})$$
>**Osservazione**
>In particolare, dal teorema segue che se $f:[a,b]\to\Re$ è **continua** in $[a,b]$, allora $F$ è derivabile in $(a,b)$ e
>$$F'(x)=f(x)\qquad\forall x \in(a,b)$$

>**Osservazione**
>	- Se $f$ è continua in $[a,b]$, segue che $F\in C^1([a,b])$.
>		Infatti $F$ è derivabile e $F'=f$, quindi $F$ è continua.
>	- Se $f\in C^1([a,b])$, allora $F\in C^2([a,b])$.
>	- Se $f\in C^k([a,b])$, allora $F\in C^{k+1}([a,b])$.

