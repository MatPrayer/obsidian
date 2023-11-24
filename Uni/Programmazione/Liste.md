## Liste semplicemente concatenate
Una ***lista concatenata*** è un insieme di oggetti, dove ogni oggetto è inserito in un nodo contenente anche un **link** ad un altro nodo.
Per convenzione, il nodo finale ha *next* a NULL.

Inserimento dati in lista:
- In testa
- In coda
- In posizione ordinata
- In posizione generica

Cancellazione dati in lista:
- In testa
- In coda
- In posizione ordinata

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

### Inserimento di un elemento
Per inserire un Nodo *t* in una lista concatenata nella posizione successiva a quella occupata da un dato Nodo x:

````
void insert_node(Nodo* x, Nodo* t){
	t->next = x->next;
	x->next = t;
}
````
