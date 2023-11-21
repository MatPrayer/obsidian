## Determinante [🔗](https://www.andreaminini.org/matematica/algebra-lineare/determinante-matrice)

>***Premessa:***
>Data una matrice quadrata $A\in M_n(\Reals)$ e due indici $j,k \in \lbrace 1,...,n \rbrace$ si indica con $A_{jk}$ la matrice di ordine $n-1$ ottenuta da >$A$ cancellando la riga $j$ e la colonna $k$.
>
>Esempio:
>$$A=\begin{bmatrix}1&2&3\\4&5&6\\7&8&9\end{bmatrix} \qquad A_{12} = \begin{bmatrix}4&6\\7&9\end{bmatrix}$$

Il ***determinante*** è una funzione che associa ad una matrice quadrata $A=[a_{ij}] \in M_n(\Reals)$ un numero reale.
- Se $n = 1$, $det(A) = a_{11}$
- Se $n \ge 2$,
$$det(A)=\sum_{i=1}^n (-1)^{i+1}a_{i1}det(A_{i1})$$

>**Esempi:**

>1) ($n=2$)
>$A=\begin{bmatrix}a_{11}&&a_{12}\\a_{21}&&a_{22}\end{bmatrix}$
>
>$det(A) = (-1)^{1+1}det(A_{11})+(-1)^{2+1}a_{21}det(a_{21}) = a_{11}a_{22} - a_{21}a_{12}$

>2) ($n=3$)
>$A=\begin{bmatrix}1&&1&&0\\2&&-1&&-1\\1&&0&&0\end{bmatrix}$
>
>$det(A)=(-1)^{1+1}1det\Bigg(\begin{bmatrix}-1&&-1\\0&&0\end{bmatrix}\Bigg)+(-1)^{2+1}2det\Bigg(\begin{bmatrix}1&&0\\0&&0\end{bmatrix}\Bigg)+(-1)^{3+1}1det\Bigg(\begin{bmatrix}1&&0\\-1&&-1\end{bmatrix}\Bigg)=\\=[(-1)\cdot0-0\cdot(-1)]-2[(1)\cdot0-0\cdot0][1\cdot(-1)-(-1)\cdot0]=-1$

### Teoremi del determinante
- **[[Teorema di Laplace]]**
- **[[Teorema di Binet]]**
- **[[Teorema di Cramer]]**

### [[Determinante e operazioni elementari]]

### [[Applicazioni del determinante]]
