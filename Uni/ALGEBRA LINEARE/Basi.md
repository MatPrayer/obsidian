## Basi [🔗](https://www.andreaminini.org/matematica/spazio-vettoriale/base-algebra-lineare)

In uno [spazio vettoriale](Spazio%20vettoriale.md) $V$ un insieme di vettori $B=\lbrace v_1,...,v_2\rbrace$ [generatori](generatori) di $V$ è una ***base*** di $V$ se è composto da vettori [linearmente indipendenti](Dipendenza%20e%20indipendenza%20lineare#indipendenza).

>Esempi
>1. $V=\Reals^n, \quad B=\lbrace1,0,...,0),(0,1,...,0),(0,0,...,1)\rbrace$ è la **base canonica** di $\Reals^n$
>2. $M_2(\Reals), \quad B=\Bigg\lbrace\begin{bmatrix}1&&0\\0&&0\end{bmatrix},\begin{bmatrix}0&&1\\0&&0\end{bmatrix},\begin{bmatrix}0&&0\\1&&0\end{bmatrix},\begin{bmatrix}0&&0\\0&&1\end{bmatrix}\Bigg\rbrace$
>3. $\Reals_d[x], \quad B=\lbrace 1,x,x^2,...,x^d\rbrace$ *(spazio dei polinomi in $x$ di grado al più $d$ a coefficienti reali)*

<br>

### Teorema

Sia $V$ spazio vettoriale finitamente generato, $V\ne\lbrace\underline{0}\rbrace$:
- $V$ ammette una base
- $B = \lbrace v1,...,v_n\rbrace$ è una base di $V\iff\forall v\in V$ si scrive in modo unico come combinazione lineare di elementi di $B$

<br>

### Come estrarre una base da un sistema di generatori (WIP)