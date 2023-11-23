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
- $o(1)\cdot$