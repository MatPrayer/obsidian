# Proprietà dell'[[Integrale di Reimann |integrale]]

Siano $f,g:[a,b]\to\Re$ funzioni integrabili in $[a,b]$.
Valgono allora le seguenti proprietà:

- **Linearità**: per ogni $\alpha,\beta\in\Re$, $\alpha f+\beta g$ è integrabile in $[a,b]$ e $$\int_{a}^b (\alpha f(x)+\beta g(x)) \, dx=\alpha \int_{a}^b f(x) \, dx+\beta \int_{a}^b g(x) \, dx  $$
- **Addittività rispetto al dominio di integrazione**: se $r\in(a,b)$, allora $f$ è integrabile in $[a,r]$ e in $[r,b]$ e
$$\int_{a}^b f(x)\ dx=\int_{a}^r f(x) \, dx+\int_{r}^b f(x) \, dx  $$
- **Positività**: se $f\ge0$ in $[a,b]$, allora
$$\int_{a}^b f(x)  \, dx\ge 0$$
- **Monotonia**: se $f\ge g$ in $[a,b]$, allora
$$\int_{a}^b f(x) \, dx\ge\int_{a}^bg(x)  \, dx  $$
- $\mid \int_{a}^b f(x)  \, dx\mid\le\int \mid f(x)\mid  \, dx$
	**Osservazione**: se $f$ è continua e cambia segno, allora la disuguaglianza è stretta