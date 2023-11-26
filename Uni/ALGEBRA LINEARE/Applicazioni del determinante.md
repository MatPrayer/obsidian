### Applicazioni del determinante

- [[#Invertibilità di una matrice|Invertibilità di una matrice]]
- [[#Calcolo di matrici inverse|Calcolo di matrici inverse]]
- [[#Soluzione di sistemi lineari|Soluzione di sistemi lineari]]
- [[#Determinante e geometria dello spazio|Determinante e geometria dello spazio]]

* * *
#### Invertibilità di una matrice
Sia $A\in M_n(\Re)$, le seguenti condizioni sono equivalenti: 
- $det(A)\ne0$
- $rg(A)=n$
- $A$ è invertibile
> ***Corollario***
> Un insieme di $n$ ennuple $\lbrace \underline{n_1},...,\underline{n_n}\rbrace \in\Re^n$ formano una **base** di $\Re^n$ se e solo se $det([ \underline{n_1}|...|\underline{n_n}]\ne0$

***
#### Calcolo di matrici inverse

>**Definizione di cofattore**
>Data $A \in M_n(\Re), A=[a_{ij}]$
>Il ***cofattore*** dell'elemento $a_{ij}$ è lo scalare
>$$a'_{ij}=(-1)^{i+j}det(A_{ij})$$
>La ***matrice dei cofattori*** di $A$ è $A'=[a'_{ij}]\in M_n(\Re)$

Se $A\in M_n(\Re)$ è invertibile:
$$A^{-1}=\frac{1}{det(A)}(A')^T$$
***
#### Soluzione di sistemi lineari
Sia $A\underline{x}=\underline{b}$ un sistema lineare **quadrato** di ordine $n$. 
Indichiamo con $A_j(\underline{b})$ la matrice ottenuta sostituendo la j-esima colonna di $A$ con il vettore colonna $\underline{b}$.

La soluzione di $A\underline{x}=\underline{b}$, quando $det(A)\ne0$:

$$\begin{equation}
    \begin{cases}
      x_1=\frac{det(A_1(\underline{b})}{det(A)}\\
      ...\\
	  x_n=\frac{det(A_n(\underline{b})}{det(A)}
    \end{cases}
\end{equation}$$
***
#### Determinante e geometria dello spazio (WIP)
