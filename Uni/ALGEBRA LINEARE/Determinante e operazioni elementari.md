### [[Determinante]] e operazioni elementari

Grazie al [[Teorema di Laplace]] si ha che:
- $det(S_{ij})=-1$
- $det(D_i(\lambda))=\lambda$
- d$et(E_{ij}(\mu))=1$

<br>

#### Proprietà fondamentali del determinante
- Se la matrice $B$ è ottenuta dalla matrice $A$ ***scambiando*** due righe: $\textbf{det(B)=-det(A)}$
- Se la matrice $B$ è ottenuta dalla matrice $A$ ***moltiplicando*** una riga di $A$ per lo scalare $\lambda$: $\textbf{det(B)=λ det(A)}$
- Se la matrice B è ottenuta dalla matrice $A$ ***sommando*** a una riga di $A$ un multiplo di un'altra riga di $A$: $\textbf{det(B)=det(A)}$
<br>
>Grazie a queste proprietà è possibile semplificare il calcolo del determinante utilizzando *Gauss-Jordan* come segue:
 >- Riduciamo la matrice $A$ nella forma a scalini $A'$ tramite un numero finito di operazioni elementari $S_{ij}, E_{ij}$
 >- Indicando con S il numero di operazioni $S_{ij}$ utilizzate, risaliamo a $det(A)$ come segue: 
 >$$det(A)=(-1)^Sdet(A')$$