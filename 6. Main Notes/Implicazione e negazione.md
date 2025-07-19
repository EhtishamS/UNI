2025-07-15 15:27:15

Status: Baby

Tags: [[Mathematics]]

# Implicazione e negazione

Date due proposizioni $P$ e $Q$, consideriamo che
$P \Rightarrow Q$ e $\neg Q \Rightarrow \neg P$ 

Vogliamo dimostrare che queste due proposizioni sono **equivalenti**.

Supponiamo che $P$ è vera e $Q$ è falsa. 

Sappiamo che se la premessa è vera e la conclusione è falsa allora l'implicazione è falsa, quindi $P \Rightarrow Q$ è falsa.

$\neg P$ è falso e $\neg Q$ è vero, anche in questo caso l'implicazione è falsa.

Quindi entrambe le proposizioni sono false.

Eccolo tutte le casistiche possibili: 

| $P$ | $Q$ | $\neg P$ | $\neg Q$ | $P \Rightarrow Q$ | $\neg Q \Rightarrow \neg P$ |
| --- | --- | -------- | -------- | ----------------- | --------------------------- |
| V   | V   | F        | F        | V                 | V                           |
| V   | F   | F        | V        | F                 | F                           |
| F   | V   | V        | F        | V                 | V                           |
| F   | F   | V        | V        | V                 | V                           |

Nota bene -> La negazione di un implicazione si dice **contronominale**
# Flash Cards
#nozioni-di-base 

La negazione di un implicazione è equivalente all'implicazione originale?
?
Sì
<!--SR:!2025-07-21,4,270-->

Dimostra che la negazione dell'implicazione è equivalente all'implicazione originale
?
Se $P$ è vero e $Q$ è falso allora $P \Rightarrow Q$  è falso,  allora $\neg P$ è falso e $\neg Q$ è vero allora $\neg Q \Rightarrow \neg P$ è falso.
Quindi $P \Rightarrow Q$ e $\neg Q \Rightarrow \neg P$ entrambe sono false e quindi equivalenti.
<!--SR:!2025-07-21,4,270-->

Come si dice se la negazione di una implicazione?
?
Contronominale
# References
<!--SR:!2025-07-21,4,270-->

[[Esercizio usando la contronominale]]