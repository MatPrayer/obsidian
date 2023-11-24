## Liste semplicemente concatenate
Una ***lista concatenata*** è un insieme di oggetti, dove ogni oggetto è inserito in un nodo contenente anche un **link** ad un altro nodo.
Per convenzione, il nodo finale ha *next* a NULL.

Inserimento dati in lista:
- In testa
- In coda
- In posizione ordinata
- In posizione generica

````
typedef struct Tdato{
	//Dati
	//costruttori, distruttore, stampa
}Tdato

typedef struct Tnodo{
	Tdato dato
	Tnodo* next;

	Tnodo(){ dato= Tdato(); next =NULL;}
	Tnodo(Tdato d){ dato = d; next = NULL;}
	Tnodo(Tdato d, Tnodo* n){dato = d; next = n;}
}
````