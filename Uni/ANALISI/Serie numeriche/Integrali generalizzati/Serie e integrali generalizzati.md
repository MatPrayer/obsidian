Una [[Serie numeriche|serie numerica]] può essere vista come un particolare [[Integrali generalizzati|integrale generalizzato]]:

- Consideriamo la serie $\sum_{n=0}^\infty a_{n}$
- Definiamo la funzione costante a tratti
	$f:[0,+\infty)\to\Re$
	$f(x)=a_{k}$ per $x \in [k,k+1)$
- Si ha che:
$$
\int_{0}^{n+1} f(x)  \, dx = \sum_{k=0}^n\int_{k}^{k+1} f(x)  \, dx = \sum_{k=0}^n a_{k} = S_{n}
$$

Perciò, se l'integrale improprio $\int_{0}^{+\infty} f(x)  \, dx$ è [[Integrali generalizzati#^991ad9|convergente]], allora la serie $\sum_{k=0}^na_{k}$ è [[Serie numeriche#^a217d7|convergente]].
$$
\int_{0}^{+\infty}f(x)  \, dx \text{ converge } \iff \sum_{k=0}^\infty a_{k}\text{ converge }
$$
Inoltre:
$$
\int_{0}^{+\infty}f(x)  \, dx = \sum_{k=0}^\infty a_{k}
$$
