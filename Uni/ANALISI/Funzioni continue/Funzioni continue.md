---
~
---
Sia $f:D\to\R,\;x_0\in D$. Se $x_0$ è punto di accumulazione per $D$, $f$ è ***continua*** se
$$\lim\limits_{x\to x_0}f(x)=f(x_0)$$

>OSSERVAZIONE 1
>La definizione di limite $\lim\limits_{x\to x_0}f(x)$ non richiede nulla sul comportamento della funzione in $x_0$, ma solo nei punti vicini (il valore di $f$ in $x_0$ potrebbe essere $x_0\notin D$).
>
>La nozione di continuità esprime un *legame tra il comportamento di $f$ vicino a; punto $x_0$ ed il suo valore in $x_0$*.

>OSSERVAZIONE 2
>Se $f$ è continua in $x_0$, allora
> *per ogni successione di punt*i $x_n\in D,\; x_n\to x_0 \implies f(x_n)\to f(x_0)$

* * *
## Continuità da destra e da sinistra
- $f$ è ***continua da destra*** in $x_0$ se $\quad \lim\limits_{x\to x_0^+}=f(x_0)$
- $f$ è ***continua da destra*** in $x_0$ se $\quad \lim\limits_{x\to x_0^-}=f(x_0)$
* * *
## Continuità in un intervallo
Sia $f:D\to\R$, e sia $A\subset D$. \
$f$ è ***continua in $A$*** se $f$ è continua in $x_0,\forall x_0\in A$.\
Si scrive che $f\in C^0(A)$.
* * *
## Tipi di discontinuità


### Discontinuità eliminabile
$f$ ha una ***discontinuità eliminabile*** in $x_0$ se: 
- esiste ed è finito il limite di $f$ in $x_0$
- $\lim\limits_{x\to x_0}f(x)\ne f(x_0)$

### Discontinuità a salto
$f$ ha una ***discontinuità a salto*** in $x_0$ se: 
- esistono e sono finiti i limiti da destra e da sinistra di $f$ in $x_0$
- $\lim\limits_{x\to x_0^+}f(x)\ne\lim\limits_{x\to x_0^-}f(x)$

### Discontinuità essenziale
$f$ ha una ***discontinuità essenziale*** in $x_0$ se non vale nessuno dei casi precedenti.

* * *
## Continuità delle funzioni elementari
Tutte le funzioni elementari *(elevamento a potenza, funzioni trigonometriche, funzioni esponenziali, e le loro funzioni inverse)* sono continue in tutto il loro dominio.

* * *
## Algebra delle funzioni continue
Se $f$ e $g$ sono continue in un punto $x_0$, allora sono continue anche le funzioni:
$$f(x)\pm g(x)\qquad\qquad f(x)\cdot g(x)\qquad\qquad \frac{f(x)}{g(x)} \color{#99A39E}\quad (g(x_0)\ne 0)$$