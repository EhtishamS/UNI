2025-07-19 12:33:11

Status: Adult

Tags: [[Mathematics]]

# Funzioni iniettive, suriettive e biiettive

Una funzione è una relazione tra gli elementi di due **insiemi** $A$ e $B$, che associa ad ogni elemento $A$ uno ed uno solo elemento di $B$. 

Una funzione è definita assegnando:
1. un insieme di A ($dominio$)
2. un insieme di B ($codominio$)
3. una relazione $f \colon A \rightarrow B$  (f è una funzione da A a B) che ogni elemento di $A$ associa uno ed uno solo elemento di $B$. 

Facciamo un esempio: 

$A = \{1, 2, 3\}$ $B = \{a, b, c, d\}$

La relazione $f$ è definita da $f(1) = b$, $f(2) = a$ e $f(3) = b$

![[funzione_esempio.excalidraw]]

L'insieme di $f(A) = \{ b \in B \colon b = f(a)$ $per$ $qualche$ $a \in A\} \subseteq B$ è detto **immagine** di $A$ tramite $f$ (o immagine di $f$). Questa nozione matematica indica che $f(A)$ è l'insieme degli elementi del codominio B che sono immagine di elementi del dominio A, che in effetti è sottoinsieme di $B$. 
In questo caso $f(A) = \{a, b\} \subseteq B$

Quando nella funzione il dominio non viene indicato è sotto intesto di prendere l'insieme più grande per la quale la funzione abbia senso.

### Funzione iniettiva

Una funzione è detta **iniettiva** quando ciascun elemento del dominio A corrisponde ad elementi **distinti** del codominio B. 

Per provare a capire se una funzione è iniettiva dobbiamo prendere due elementi distinti a e b che appartengono al dominio tale $f(A) = f(B) \Leftrightarrow a = b$.

$a, b \in \mathbb{D}, f(a) = f(b) \Leftrightarrow a = b$

Esempio:

![[funzione_iniettiva_esempio.excalidraw]]

### Funzione suriettiva

Una funzione è detta **suriettiva** quando ciascun elemento del codominio è l'immagine di **almeno uno elemento** del dominio.

Per provare a vedere se una funzione è suriettiva bisogna prendere un numero $y$ che appartiene al codominio che capire se esiste un x tale che la funzione $f(x) = y$. 

$y \in \mathbb{C}, \exists x \colon f(x) = y$

Esempio:

![[funzione_suriettiva_esempio.excalidraw]]

### Funzione biiettiva

Una funzione si dice che è biiettiva quando è sia iniettiva che suriettiva.

Esempio:

![[funzione_biiettiva_esempio.excalidraw]]

# Flash Cards
#funzioni

Cos'è una funzione e cosa serve per definirne una?
?
Una funzione è una relazione tra due insieme A e B, che associata ogni elemento di A uno e uno solo elemento di B. 
|
Per definire una funzione serve:
1. un insieme A (dominio)
2. un insieme B (codominio)
3. una relazione $f \colon A \rightarrow B$ che associa ogni elemento di A uno ed uno solo elemento di B.

Cos'è l'immagine di A tramite $f$?
?
L'immagine di A tramite $f$ meglio scritto $f(A)$ è l'insieme degli elementi $b$ che appartengono all'insieme $B$ tale che b = $f(a)$ per qualche elemento $a$ che appartiene all'insieme $A$. $f(A) = \{b \in B \colon b = f(a)$ $per$ $qualche$ $a \in A\}$

Quand'è che una funzione è iniettiva, scrivimi anche la sua condizione sufficiente necessaria?
?
Una funzione iniettiva è quando ogni gli elementi del dominio A ha un immagini distinta nel codominio B. 
![[funzione_iniettiva_esempio.excalidraw]]
|
$a, b \in \mathbb{D}, f(a) = f(b) \Leftrightarrow a = b$ 

Quand'è che una funzione è suriettiva, scrivimi anche la sua condizione sufficiente necessaria?
?
Una funzione suriettiva è quando ogni elemento del codominio B è l'imamagine di  almeno un elemento nel dominio A.
![[funzione_suriettiva_esempio.excalidraw]]
|
$y \in \mathbb{C}, \exists x \colon f(x) = y$

Quand'è che una funzione è biiettiva?
?
Una funzione è biiettiva quando è sia iniettiva che suriettiva.

Data la funzione $f \colon \mathbb{R} \rightarrow \mathbb{R}$, $f(x) = 2x - 3$ capire se è iniettiva, suriettiva o biiettiva?
?
Biiettiva.

Data la funzione $f \colon \mathbb{R} \rightarrow \mathbb{R},$ $f(x) = x^{2}$ capire se è iniettiva, suriettiva o biiettiva?
?
Non né iniettiva né suriettiva. 

Data la funzione $f \colon \mathbb{R} \rightarrow [0, + \infty]$, $f(x)=x^{2}$
?
Non è iniettiva ma è suriettiva.

# References