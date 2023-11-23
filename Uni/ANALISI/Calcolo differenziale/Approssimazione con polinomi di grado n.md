### Approssimazione con polinomi di grado $n$

**Problema:** Data la funzione $f:(a,b)\to\Re, x_0\in (a,b)$,  possiamo [[Formula di Taylor#La retta tangente come migliore approssimante affine |approssimare]] $f$ ***vicino ad $x_0$*** con un polinomio $T_n(x)$ di grado $\le n$?

- Se $f$ è derivabile in $x_{0}$, è possibile con un polinomio di grado $\le 1$:
$$T_{1}(x)=f(x_{0})+f'(x_{0})(x-x_{0})$$
	Il polinomio $T_{1}$ ha le proprietà:
	- $T_{1}(x_{0})=f(x_{0})$
	- $T'_{1}(x_{0})=f'(x_{0})$

- Supponendo che $f$ sia derivabile $n$ volte in $x_{0}$, il polinomio $T_{n}(x)$ di grado $\le n$ è tale che:
	- $T_{n}(x_{0})=f(x_{0})$
	- $T'(x_{0})=f'(x_{0})$
	- $\dots$
	- $T_{n}^{(n)}(x_{0})=f^{(n)}(x_{0})$