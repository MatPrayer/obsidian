>**Proposizione**
>Sia $V$ uno [[Spazio vettoriale]] reale di dimensione $n$ e sia $A=\lbrace\underline{a}_{1},\dots \underline{a}_{n}\rbrace$ [[Basi|base]] di $V$.
>Sia $V'$ uno spazio vettoriale reale e siano $\underline{b}_{1},\dots \underline{b}_{n}$ elementi di $V'$
>Allora esiste un'unica [[Funzioni lineari|funzione lineare]] $f:V\to V'$ tale che $f(a_{i})=b_{i}$ per ogni $i=1,\dots,n$.

*Costruiamo ora la matrice che rappresenta $f:V\to V'$

- $A=\lbrace\underline{a}_{1},\dots \underline{a}_{n}\rbrace$ base di $V\qquad$ ($\dim(V)=n$)
- $B=\lbrace\underline{b}_{1},\dots \underline{b}_{n}\rbrace$ base di $V'\qquad$($\dim(V')=m$)
- $f:V\to V'$

- $f(\underline{a}_{1})=\sum_{i=1}^m\alpha_{i_{1}}\underline{b}_{i}\in V'$
- - $f(\underline{a}_{2})=\sum_{i=1}^m\alpha_{i_{2}}\underline{b}_{i}\in V'$
- $\dots$
- $f(\underline{a}_{n})=\sum_{i=1}^m\alpha_{i_{n}}\underline{b}_{i}\in V'$

$$\begin{bmatrix}
\alpha_{11}&&\alpha_{12}&&\dots&&\alpha_{1n}\\ \\
\alpha_{21}&&\alpha_{22}&&\dots&&\alpha_{1n}\\ \\
\dots&&\dots&&..&&\dots\\ \\
\alpha_{m1}&&\alpha_{m2}&&\dots&&\alpha_{mn}\\
\end{bmatrix}=M_{A}^B(f)=[\alpha_{ij}\in M_{m,n}(\Re)]$$
$M_{A}^B(f)$ è detta **matrice rappresentativa di $f$ rispetto alle basi $A$ e $B$.

# [[Coordinate]] e matrici rappresentative

Dati $V,V'$ spazi vettoriali reali con rispettive basi $A$ e $B$,
$f:V\to V'$ funzione lineare, $M=M_{A}^B(f)$

Dati $V, A$, possiamo definire una funzione lineare 
$$T_{A}:V\to\Re^n,\quad\underline{v}\to(v_{1},\dots,v_{n})\qquad \text{ove }\underline{v}=\sum_{i=1}^nv_{i}\underline{a}_{i}$$
Mettendo tutto assieme si ottiene un diagramma:

![[Pasted image 20231128181753 1.png]]

>**Nota bene**
>Il diagramma è *commutativo*, ossia $T_{M}=T_{B}\circ f\circ(T_{A})^{-1}$ (oppure $f=(T_{B})^{-1}\circ T_{M}\circ T_{A}$)

>**Corollario ([[Nucleo|nucleo]] e [[Immagine di una funzione lineare|immagine]])**
>$\ker(T_{M}=T_{A}(\ker(f)))$
>$Im(T_{M})=T_{B}(Im(f))$

