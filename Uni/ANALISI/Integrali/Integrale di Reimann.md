Come visto in [[Somme superiori e inferiori]], l'idea è di considerare suddivisioni sempre più [[Raffinamento |fini]] dell'intervallo $[a,b]$, in modo da approssimare sempre meglio l'area del sottografico di $f$.
Questo è possibile prendendo l'estremo superiore delle somme inferiori e l'estremo inferiore delle somme superiori:

- $\sup_{D}s^-(D,f)=\sup\lbrace s^-(D,f):D\text{ suddivisione di }[a,b]\rbrace$
- $\inf_{D}s^+(D,f)=\inf\lbrace s^+(D,f):D\text{ suddivisione di }[a,b]\rbrace$

In generale, 
$$\sup_{D}s^-(D,f)\le\inf_{D}s^+(D,f)$$
La definizione di ***funzione integrabile di Reimann*** è data dall'uguaglianza nella condizione precedente.

# Definizione di integrale di Reimann

Sia $f[a,b]\to\Re$ limitata.
La funzione $f$ si dice ***integrabile secondo Reimann*** in $[a,b]$ se:
$$\sup_{D}s^-(D,f)=\inf_{D}s^+(D,f)$$
Il valore comune è detto **integrale di Reimann** di $f$ in $[a,b]$ e si indica con:
$$\int_{a}^b f(x)\, dx$$
Dove:
- $[a,b]$ estremi di integrazione
- $f(x)$ funzione integranda
- $dx$ differenziale di $x$