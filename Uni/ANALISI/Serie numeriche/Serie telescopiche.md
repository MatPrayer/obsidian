Importante esempio di [[Serie numeriche]].
Siano $(a_{n})_{n\ge 0}$ e $(b_{n})_{n\ge0}$ due [[Successioni]], tali che la prima si ottenga dalla seconda in base alla formula:
$$
a_{n}=b_{n+1}-b_{n}\qquad \text{per ogni }n\in \mathbb{N}
$$
Allora la somma parziale $k$-esima relativa alla sere $\sum^{+\infty}_{n=0}a_{n}$ è data da:
$$
S_{k}=a_{0}+a_{1}+a_{2}+\dots+a_{k-1}+a_{k}= (b_{1}-b_{0})+(b_{2}-b_{1})+(b_{3}-b_{2})+\dots+(b_{k}-b_{k-1})+(b_{k+1}-b_{k})
$$
Da cui si ottiene:
$$b_{k+1}-b_{0}$$
Quindi la conclusione è:
$$
\sum_{n=0}^{+\infty}a_{n}=\lim_{ k \to \infty }b_{k+1}-b_{0} 
$$
Esempi di serie di tipo telescopico sono:

- **La serie di Méngoli**: 
$$
\sum_{n=1}^{+\infty}\frac{1}{n(n+1)}
$$
$a_{n}=n(n+1),\quad \frac{n+1}{(n+1n)}-\frac{n}{(n+1)n}=\underbrace{\frac{1}{n}}_{-b_{n}}-\underbrace{\frac{1}{n+1}}_{-b_{n+1}}\implies a_{n}=b_{n+1}-b_{n}\implies \sum_{n=1}^{+\infty}a_{n}=\underbrace{\lim_{ k \to \infty }b_{k+1}}_{0}-\underbrace{b_{1}}_{-1}=-b_{1}=1$ Converge a $1$.

- **La serie logaritmica:**
$$
\sum_{n=1}^{+\infty}\log\left( 1+\frac{1}{n} \right)
$$
$a_{n}=\log\left( 1+\frac{1}{n} \right),\quad\log(\frac{n+1}{n}=\underbrace{\log(n+1)}_{b_{n+1}}-\underbrace{\log(n)}_{b_{n}}\implies \sum_{n=1}^{+\infty}a_{n}=\underbrace{\lim_{k\to\infty}(b_{k+1})}_{+\infty}-\underbrace{b_{1}}_{0}=+\infty$
Diverge a $+\infty$.