La definizione di [[Integrale di Reimann]] $\int_{a}^b f(x) \, dx$ richiede che:
- il dominio di integrazione $[a,b]$ sia un intervallo **limitato**
- la funzione integranda $f$ sia una funzione **limitata**

È possible considerare situazioni più generali:
- **Funzione illimitata** in un intervallo limitato
- Funzione limitata in un **intervallo illimitato**

# Definizione di integrale generalizzato in un intervallo limitato

Sia $f:(a,b]\to\Re$ integrabile in $[a+\epsilon,b]$ per ogni $\epsilon>0$.
Definiamo l'***integrale improprio o generalizzato*** di $f$ in $(a,b)$ come il limite (se esiste):

$$
\int_{a}^b f(x) \, dx := \lim_{ \epsilon \to 0^+ } \int_{a+\epsilon}^b f(x)  \, dx  
$$
Similmente, se $f$ è integrabile in $[a,b-\epsilon]$ per ogni $\epsilon>0$ poniamo:
$$
\int_{a}^b f(x) \, dx := \lim_{ \epsilon \to 0^+ } \int_{a}^{b-\epsilon} f(x)  \, dx  
$$

Se il limite è finito, diciamo che $f$ è ***integrabile in senso generalizzato in $(a,b)$*** e che l'integrale improprio è [[Serie numeriche#^a217d7|convergente]].
Se il limite vale $\pm \infty$, diciamo che l'integrale improprio è [[Serie numeriche#^9c26fa|divergente]].

![[Screenshot 2023-12-07 at 11.33.20.png]]