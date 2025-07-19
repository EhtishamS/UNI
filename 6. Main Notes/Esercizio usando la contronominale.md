Sia $n \in \mathbb{N}$. Dimostrare che $2^n -1$ $primo$ $\Rightarrow$ $n$ $primo$

La dimostrazione di questa potrebbe essere molto difficile da fare allora dimostriamo che la sua contronominale per la quale dovrebbe essere più facile.

$n$ Non $primo$ $\Rightarrow$ $2^n -1$ Non $primo$

Facciamo verifica per casi semplici prima:

$n=0 \Rightarrow 2^n -1 = 1-1=0$ ✅ (non è primo)
$n = 1 \Rightarrow 2^n-1 = 2-1=1$ ✅ (non è primo)

Verifichiamo adesso per tutti i casi maggiori di 1:

$n \geq 2$ 

Possiamo immaginare che $n$ sia un numero composto

$n = l * m,$   $1<l,m<n$

L'espressione iniziale si può riscrivere in questo modo:
$2^{l*m} -1 = (2^l)^m -1$

Per la generalizzazione del prodotto notevole che dice
$x^m-1=(x-1)(x^{m-1}+x^{m-2}+\dots+x^1+1),$ $m>1$

Quindi se riscriviamo il l'espressione questa verra scritta così:
$(2^l)^m -1 = (2^l-1)((2^l)^{m-1}+(2^l)^{m-2}+\dots+2^1+1)$

Siccome $l$ è strettamente maggiore di 1, allora il risultato dell'espressione $2^l -1$ è strettamente maggiore di 1. 

Stesso vale per la seconda espressione dove $m$ risulta strettamente maggiore di 1, allora il risultato dell'espressione $((2^l)^{m-1}+(2^l)^{m-2}+\dots+2^1+1)$ è strettamente maggiore di 1

> [!Important] Conclusione 
> Possiamo concludere con certezza che il prodotto di 2 numeri strettamente maggiore di 1 non sarà mai primo, quindi $n$ Non $primo$ $\Rightarrow$ $2^n -1$ Non $primo$ è vero, e di conseguenza anche $2^n -1$ $primo$ $\Rightarrow$ $n$ $primo$ è vero.
