## Il simbolo $o(1)$
Il simbolo di $o(1)$ viene utilizzato per indicare una generica funzione infinitesima: 
se $f$ è infinitesima per $x\to x_{0}$, si scrive
$$f(x)=o(1)\qquad\text{per }x\to x_{0}$$
Anche la condizione di limite finito si può riscrivere utilizzando il simbolo di $o(1)$:
$$\lim_{ n \to x_{0} }f(x)=l\iff f(x)=l+o(1)\quad\text{per }x\to x_{0}$$
Questo permette di *alleggerire* la notazione nel calcolo di un limite.

## Il simbolo $o(f(x))$
$$o(f(x))=f(x)\cdot o(1)\quad\text{ per }x\to x_{0}$$
Dalla definizione precedente segue che:
$$g(x)=o(f(x))\quad\text{ per }x\to x_{0}\iff \lim_{ x \to x_{0} }\frac{g(x)}{f(x)}=0$$
## Algebra degli $o$ piccoli
Per $x\to x_{0}$ vale che:

- $o(1)+o(1)=o(1)$
- $o(1)\cdot o(1)=o(1)$
- $l\cdot o(1)=o(1)$ (se $l\in\Re$)

- **Somma**
	- In una somma di $o$-piccoli di $x$ per $x\to x_{0}$ si tiene solo il termine con potenza più bassa:
		- $o(x)+o(x)=o(x)$
		- $o(x)+o(x^2)+o(x^5)=o(x)$

- **Altre operazioni**
- $o(c\cdot x^\alpha)=o(x^\alpha)$
- $x^\alpha\cdot o(x^\beta)=o(x^{\alpha+\beta})$
- $(o(x^\alpha))^\beta=o(x^{\alpha\beta})$