Una classe di funzioni [[Integrale di Reimann|integrabili]] elementarmente è data dalle funzioni razionali, ovvero le funzioni che si scrivono come rapporto di due polinomi:
$$
f(x)=\frac{P_{n}(x)}{Q_{m}(x)}
$$

con $P_{n}(x)$ e $Q_{m}(x)$ polinomi di grado $n \ge0$ e $m \ge 1$ rispettivamente.

- **Grado del numeratore maggiore o uguale al grado del denominatore** ($n \ge m$):
	Si effettua la ***divisione tra polinomi***, in modo da ricondursi al caso $n<m$.

- **Denominatore di grado 1**:
	L'integrazione produce un logaritmo:
	$$
\int \frac{A}{ax+b} \, dx = \frac{A}{a}\int \frac{a}{ax+b} \, dx = \frac{A}{a}\log \mid ax+b\mid+c  
$$
- **Denominatore di secondo grado**:
	L'integrale si presenta nella forma:
$$
\int \frac{{\alpha x+\beta}}{ax^2+bx+c} \, dx 
$$
	È necessario distinguere tre ulteriori sotto-casi, a seconda del discriminante del denominatore:
$$
\Delta = b^2-4ac
$$
1. $\Delta>0$: Il denominatore ha due radici distinte 
	Si procede con la **scomposizione in fratti semplici**:
	$$
\frac{P(x)}{Q(x)}=\frac{{\alpha x+\beta}}{ax^2+bx+c}=\frac{{\alpha x+\beta}}{a(x-x_{1})(x-x_{2})}=\frac{A}{x-x_{1}}+\frac{B}{x-x_{2}}
$$
	Dove i coefficienti $A$ e $B$ sono da determinare.

2. $\Delta=0$: il denominatore è un quadrato perfetto
	$$
ax^2+bx+c=a(x-x_{0})^2
$$
	In questo caso, la [[Integrazione per sostituzione|sostituzione]] $t=(x-x_{0})$ permette di calcolare l'integrale.

3. $\Delta<0$: il denominatore non si scompone
	In generale si segue questo procedimento:
	- Si opera sul numeratore per farvi figurare la derivata del denominatore
	- Si scrive l'integrale come somma di due integrali
	- Si calcola il primo integrale (logaritmo)
	- Si calcola il secondo integrale 
	- Si sommano i risultati ottenuti

- **Denominatore di grado superiore al secondo**:
	Si scompone il denominatore in fattori e si scrive la frazione algebrica come somma di frazioni con denominatori di primo e secondo grado, riconducendosi al calcolo di integrali dei tipi descritti in precedenza.
