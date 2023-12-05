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
- La serie è detta **convergente** se il limite di $S_{k}$ *esiste finito*
- La serie è detta **divergente** se il limite di $S_{k}$ esiste e *vale $\pm\infty$*
- La serie è detta **indeterminata** se il limite di $S_{k}$ *non esiste*
