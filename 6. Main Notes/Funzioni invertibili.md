2025-07-19 19:49:14

Status: Baby

Tags: [[Mathematics]]

# Funzioni invertibili

> [!iimportant] definizione
> Una funzione $f \colon A \rightarrow B$ è invertibile quando esiste una funzione $f^{-1} \colon B \rightarrow A$, tale che:
> - $\forall a \in A, f^{-1}(f(a))=a$
> - $\forall b \in B, f(f^{-1}(b)) = b$
> 
> e la funzione è biiettiva.

___
Per esempio:

$f \colon \mathbb{R} \rightarrow \mathbb{R}, f(x)=2x+1$

$a, b \in \mathbb{R}, f(a) = f(b) \Leftrightarrow a = b$ -> $f(a) = f(b) \Leftrightarrow 2a+1 = 2b+1 \Leftrightarrow a = b$ (è **iniettiva**)

$y \in \mathbb{R}, \exists x \colon f(x) = y$  -> $2x + 1 = y \Leftrightarrow x = \frac{y-1}{2}$ (è **suriettiva**)

Se è iniettiva $\wedge$ suriettiva allora è **biiettiva**.

Adesso che abbiamo stabilito che questa funzione è biiettiva, possiamo vedere se le altre due condizioni sono valide o no

Ricavare la funzione inversa:

$y = 2x + 1$
$x = \frac{y-1}{2}$

$f^{-1} = \frac{y-1}{2}$


> Prima condizione 
> $\forall x \in \mathbb{R}, f^{-1}(f(x)) = x$

$f^{-1}(f(x)) = x$ -> $f^{-1}(2x+1) = \frac{(\cancel{2}x + \cancel{1}) - \cancel{1}}{\cancel{2}} = x$ ✅ 

> Seconda condizione: 
> $\forall y \in \mathbb{R}, f(f^{-1}(y)) = y$

$f(f^{-1}(y)) = f(\frac{y-1}{2}) = \cancel{2}(\frac{y-\cancel{1}}{\cancel{2}}) - \cancel{1} = y$ ✅

Questa funzione è **invertibile**. 

# Flash Cards
#funzioni 

Quand'è che si può dire che una funzione è invertibile?
?
Una funzione $f \colon A \rightarrow B$ è invertibile se esiste una $f^{-1} \colon B \rightarrow A$ tale che:
- $\forall a \in A, f^{-1}(f(a)) = a$
- $\forall b \in B, f(f^{-1}(b)) = b$
e deve essere biiettivo.

Dimostra se la seguente funzione è invertibile oppure no:
$f \colon \mathbb{R} \rightarrow \mathbb{R}, f(x) = 3x-5$
?
È invertibile ✅

Dimostra se la seguente funzione è invertibile oppure no:
$f \colon \mathbb{R} \rightarrow \mathbb{R}, f(x) = x^{2}+1$
?
Non è iniettiva ❌, di conseguenza non ha una funzione inversa.

Dimostra se la seguente funzione è invertibile oppure no:
$f \colon \mathbb{R} \setminus \{0\}\rightarrow \mathbb{R}, f(x) = \frac{1}{x}$
?
Non è suriettiva ❌, di conseguenza non ha una funzione inversa.

Risolvi almeno 3 esercizi sull'invertibilità delle funzioni cercando online:
?
Spero che lo hai fatto.

# References