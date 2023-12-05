Se $f:[a,b]\to\Re$ è una [[Funzioni continue|funzione continua]], il [[Teorema fondamentale del calcolo integrale]] garantisce l'esistenza di una finzione la cui derivata è $f$: infatti la funzione integrale
$$
F(x)=\int_{x_{0}}^x f(t)  \, dt \quad\text{è derivabile e } F'(x)=f(x)  
$$
Chiamiamo ***primitiva*** di $f$ una qualunque funzione con tale proprietà
## Definizione di primitiva
Sia $I\subset\Re$ un intervallo, e sia $f:I\to \Re$. Si dice ***primitiva*** di $f$ in $I$ una qualunque funzione $G:I\to\Re$ [[Definizione di Derivata#^46cfc1|derivabile]] e tale che
$$G'(x)=f(x)\qquad\forall x \in I$$
### Caratterizzazione dell'insieme delle primitive
Dalla definizione di primitiva si ha che:
1. Se $G$ è una primitiva di $f$ in $I$, allora anche $G+c$ è una primitiva di $f$, $\forall c\in\Re$ costante
2. Se $G_{1}$ e $G_{2}$ sono primitive di $f$ in $I$, allora $G_{1}-G_{2}=c$, con $c\in\Re$ costante