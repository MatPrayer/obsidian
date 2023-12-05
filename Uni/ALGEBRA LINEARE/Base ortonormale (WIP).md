## Definizione di base ortonormale
Sia $V$ uno [[Spazio vettoriale euclideo]].
- $\lbrace \underline{v}_{1},\dots,\underline{v}_{m}\rbrace \subseteq V$ è ***ortonormale*** se:
$$\underline{v}_{i},\dots,\underline{v}_{j}=\delta ij=\begin{cases}
1\qquad i=j\\0\qquad i\neq j\quad \text{(ortogonali a coppie)}
\end{cases}$$
- Se $\lbrace \underline{v}_{1},\dots,\underline{v}_{m}\rbrace \subseteq V$ è anche una [[Basi|base]], è detta ***base ortonormale***.

### Metodo di Gram-Schmidt
Per ottenere basi ortonormali.

- Input: insieme di vettori [[Dipendenza e indipendenza lineare|linearmente indipendenti]] $\lbrace \underline{v}_{1},\dots,\underline{v}_{m}\rbrace$
- Output: insieme di vettori ortonormale $\lbrace \underline{a}_{1},\dots,\underline{a}_{m}\rbrace$ tale che $<\underline{v}_{1},\dots,\underline{v}_{m}> = <\underline{a}_{1},\dots,\underline{a}_{m}>$


