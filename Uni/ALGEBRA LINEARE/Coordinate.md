Sia $V$ uno [[Spazio vettoriale]] [[Generatori|finitamente generato]], $V\ne\lbrace \underline{0}\rbrace$.
Sia $B=\lbrace \underline{b}_{1},\dots,\underline{b}_{n}\rbrace$ una [[Basi|base]] di $V$ (in particolare $\dim(V)=n$)
Sia $\underline{v}\in V$, abbiamo:
$$\underline{v}=\sum_{i=1}^nv_{i}\underline{b}_{i}\qquad\text{(in modo unico)}$$
Gli scalari $v_{1},\dots,v_{n}\in\Re$ sono detti ***coordinate*** di $\underline{v}$ rispetto alla base $V$.

Definiamo una funzione che ad ogni $\underline{v}\in V$ associa una ennupla, ossia il vettore delle coordinate di $\underline{v}$ rispetto a $B$.
$$T_{B}:V\to\Re^n,\quad \underline{v}\to(v_{1},\dots,v_{n})$$
>**Proposizione**
>$T_{B}$ è **biunivoca** e **lineare**

- **Biunivoca**: ad ogni elemento di $V$ corrisponde uno ed un solo elemento di $\Re^n$
- **Lineare**: $\forall \underline{v},\underline{w}\in V,\quad\forall\lambda,\mu\in\Re\qquad T_{B}(\lambda \underline{v}+\mu \underline{w})=\lambda T_{B}(\underline{v}+\mu T_{B}(\underline{w})\qquad$ *$T_{B}$ preserva la combinazione lineare*

>**Proposizione**
>$\lbrace \underline{v}_{1},\dots,\underline{v}_{m}\subseteq V\rbrace\quad$è [[Dipendenza e indipendenza lineare|linearmente indipendente]] (rispetto al sistema di generatori, rispetto alla base)
>$$\iff$$
>$\lbrace T_{B}(\underline{v}_{1}),\dots,T_{B}(\underline{v}_{m})\subseteq\Re^n\quad$ è linearmente indipendente (rispetto al sistema di generatori, rispetto alla base)

>**Slogan**
>*Possiamo studiare le proprietà di $V$ riconducendoci a $R^n$ (ove tutto è più semplice)*

