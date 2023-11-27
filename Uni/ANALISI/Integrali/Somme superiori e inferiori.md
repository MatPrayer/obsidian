Sia $f:[a,b]\to\Re$ **limitata**.
Consideriamo una qualunque ***suddivisione*** o ***partizione*** dell'intervallo $[a,b]$:
$$D={x_{0},x_{1},x_{N}}$$
dove $N\in\mathbb{N}$,
$a=x_{0}<x_{1}<\dots<x_{N-1}<x_{N}=b$

Definiamo per $i=1,\dots,N$
- $m_{i}= \inf_{x\in[x_{i-1},x_{i}]}f(x)$
- $M_{i}= \sup_{x\in[x_{i-1},x_{i}]}f(x)$

Definiamo quindi ***somma inferiore*** e ***somma superiore*** di $f$, relativa alla suddivisione $D$:

- **Somma inferiore**
$$s^-(D,f)=\sum_{i=1}^Nm_{i}(x_{i}-x_{i-1})$$
![[Pasted image 20231127182308.png]]
- **Somma superiore**
$$s^+(D,f)=\sum_{i=1}^NM_{i}(x_{i}-x_{i-1})$$
![[Pasted image 20231127182349.png]]

## Interpretazione geometrica
Supponiamo $f\ge 0$:
- Abbiamo costruito su ciascun intervallo $[x_{i-1},x_{i}]$ due rettangoli, rispettivamente di altezza $m_{i}$ ed $M_{i}$.
- Le unioni di tali rettangoli costituiscono un'approssimazione *dall'interno* e *dall'esterno* del sottografico di $f$
- Le somme **inferiori** e **superiori** rappresentano le aree delle unioni dei rettangoli e forniscono quindi due approssimazioni dall'alto e dal basso dell'area del sottografico di $f$

La costruzione fatta dipende dalla suddivisione $D$ scelta. Osserviamo che, per ogni $D_{1},D_{2}$ suddivisioni di $[a,b]$:
$$(b-a)\cdot\inf_{[a,b]}f\underbrace{\le}_{1} s^-(D_{1},f)\underbrace{\le}_{2} s^+(D_{2},f)\underbrace{\le}_{3} (b-a)\cdot sup_{[a,b]}f$$
1. Il membro di sinistra è ottenuto prendendo la partizione banale $x_{0}=a,\;x_{1}=b$.
2. Il membro di sinistra rappresenta l'arco di una figura contenuta nell'oggetto rappresentato dal membro di destra.
3. Il membro di destra è ottenuto prendendo la partizione banale $x_{0}=a,\;x_{1}=b$.

>**Osservazione**
>Se $D'$ è un [[Raffinamento |raffinamento]] di $D$ allora:
>	- $s^-(D',f)\ge s^-(D,f)$ 
>		Ovvero le somme inferiori sono crescenti rispetto al raffinamento
>	- $s^+(D',f)\le s^+(D,f)$
>		Ovvero le somme superiori sono descrescenti rispetto al raffinamento 