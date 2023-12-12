# Definizione di autovalori ed autovettori
Sia $f:V\to V$ una [[Funzioni lineari|funzione lineare]] (endomorfa).

- Un vettore $\underline{v}\in V,\:\underline{v}\neq 0$ è detto ***autovettore*** se $\exists \lambda \in\Re$ tale che $f(\underline{v})=\lambda \underline{v}$
- Uno scalare $\lambda \in\Re$ è detto ***autovalore*** se $\exists \underline{v}\in V,\: \underline{v}\neq \underline{0}$ tale che $f(\underline{v})=\lambda \underline{v}$
- Dato $\lambda\in\Re$ autovalore, l'***autospazio*** relativo a $\lambda$ è il sottospazio di $V$ seguente:
$$
E(\lambda)=\lbrace\underline{v}\in V |f(\underline{v})=\lambda \underline{v}\rbrace 
$$

>**Proposizione**
>Sia $f:V\to V$ lineare.
>Siano $\lambda_{1},\dots,\lambda_{k},\quad k$ autovalori distinti di $f$
>Siano $\underline{v}_{1},\dots,\underline{v}_{k}\in V$ tali che $f(\underline{v}_{i})=\lambda_{i}\underline{v}_{i},\quad\forall i=1,\dots,k$
>
>Allora $\lbrace \underline{v}_{1},\dots,\underline{v}_{k}\rbrace$ è [[Dipendenza e indipendenza lineare#^a95079|linearmente indipendente]].

## Come si trovano gli autovalori?
Sia $f:V\to V$, sia $A$ base di $V$, $A=M_{A}^A(f)$.

$\lambda$ è autovalore di $f \iff f(\underline{x})=\lambda \underline{x}$ per qualche $\underline{x}\in V\iff A\underline{x}=\lambda \underbrace{I\underline{x}}_{\underline{x}}\iff(A-\lambda I)\underline{x}= \underline{0}\iff$ sistema lineare omogeneo associato a $A-\lambda I$ ammette soluzioni non banali $\iff \det(A-\lambda I)=0$ 

*Continua da polinomio caratterisitico*

