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

- Se il limite è finito, diciamo che $f$ è ***integrabile in senso generalizzato in $(a,b)$*** e che l'integrale improprio è ***convergente***. ^991ad9
- Se il limite vale $\pm \infty$, diciamo che l'integrale improprio è ***divergente***.

![[Screenshot 2023-12-07 at 11.33.20.png]]

***
## Integrabilità di $\frac{1}{x^\alpha}$ per $x\to 0$

$$
\int_{0}^1 \frac{1}{x^\alpha}  \, dx = \begin{cases}
\frac{1}{1-\alpha} \text{ se } 0<\alpha<1\\ \\
+\infty \text{ se } \alpha\ge 1
\end{cases} 
$$
***
# Definizione di integrale generalizzato in un intervallo illimitato

Sia $f:[a,+\infty)\to\Re$ integrabile in $[a,M]$ per ogni $M>a$.
Definiamo l'***integrale improprio o generalizzato*** di $f$ in $(a,+\infty)$ come il limite (se esiste): ^f420f4
$$
\int_{a}^{+\infty} f(x)  \, dx := \lim_{M\to +\infty}\int _{a}^M f(x) \, dx  
$$
Similmente, se $f$ è integrabile in $[M,b]$ per ogni $M<b$ poniamo:
$$
\int_{-\infty}^b f(x)  \, dx := \lim_{ n \to -\infty }\int_{M}^b f(x)  \, dx   
$$
![[Screenshot 2023-12-07 at 11.47.21.png]]
***
## Integrabilità di $\frac{1}{x^\alpha}$ per $x\to \infty$
$$
\int_{0}^\infty \frac{1}{x^\alpha}  \, dx = \begin{cases}
\frac{1}{\alpha-1} \text{ se } \alpha > 1 \\ \\
+\infty \text{ se } \alpha\le 1
\end{cases} 
$$
***
