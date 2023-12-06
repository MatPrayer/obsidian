# Definizione di serie numerica
Consideriamo una [[Successioni|successione]] $(a_{n})_{n\ge 0}$ di numeri reali.
Definiamo la **successione delle somme parziali** $(S_{k})_{k\ge 0}$:
$$S_{k}=\sum_{n=0}^k a_{n} = a_{0}+a_{1}+\dots+a_{k},\quad \text{quindi}\quad \begin{cases}
S_{0}= a_{0}\\S_{1}=a_{0}+a_{1}\\S_{2}= a_{0}+a_{1}+a_{2}\\\dots
\end{cases}$$
Chiamiamo ***serie numerica*** il **limite delle somme parziali**:
$$
\sum_{n=0}^{+\infty}a_{n}=\lim_{ n \to \infty }S_{k}=\lim_{ n \to \infty }\sum_{n=0}^k a_{n}  
$$
## Carattere di una serie

- La serie è detta **[[Condizione necessaria per la convergenza di una serie|convergente]]** se il limite di $S_{k}$ *esiste finito* ^a217d7
- La serie è detta **divergente** se il limite di $S_{k}$ esiste e *vale $\pm\infty$* ^9c26fa
- La serie è detta **indeterminata** se il limite di $S_{k}$ *non esiste* ^80d54f

### Osservazioni

- La serie $\sum_{n=0}^{+\infty} a_{n}$ ha lo stesso carattere di $\sum_{n=n_{0}}^{+\infty} a_{n}$, in quanto se si escludono i primi $n_{0}$ termini si ottiene solo una variazione finita della somma.
	- Il carattere di $\sum_{n=0}^{+\infty} a_{n}$ dipende infatti dall'andamento asintotico della successione $a_{n}$, e non dal valora specifico dei suoi primi $n_{0}$ termini
- La somma di una serie convergente dipende da tutti i termini della successione, per cui modificandone o escludendone alcuni si può modificare il valore della somma