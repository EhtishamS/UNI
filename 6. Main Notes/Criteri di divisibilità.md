 2025-07-16 22:14:00

Status: Adult

Tags: [[Mathematics]]
 
# Criteri di divisibilità

Indicheremo con $\mathbb{N}$ l'insime dei **numeri naturali** (compreso lo zero)

$\mathbb{N} = \{0, 1, 2, 3, 4, 5, 6, 7, 8, \dots\}$

Diremo che un numero naturale $d$ è divisibile per un numero naturale $n$, indicheremo con $d \mid n$ (d divide n), se esiste un numero naturale $c$ tale che $c*d = n$.
In poche parole se $d$ divide $n$ -> $n/d \in \mathbb{N}$ è senza resto.

Ogni numero è **sempre** divisibile per se stesso è per l'unita: $n \mid n$ e $1 \mid n$ 

Dato un numero esistono delle regole che permettono di verificare i numeri per quali esso è divisibile, questi vengono detti **criteri di divisibilità**.

Elenchiamo alcuni criteri di divisibilità. Un numero $n$ è divisibile per :
1. 2 se l'ultima cifra è pari -> 2002
2. 3 se la somma delle cifre è divisible per 3 -> 102
3. 4 se le ultime due cifre formano un numero divisibile per 4 -> 1432
4. 5 se l'ultima cifra è 0 o 5 -> 1995
5. 6 se è divisibile per 2 e per 3 -> 162
6. 7 se il numero ottenuto tralasciando l'ultima cifra sommato a cinque volte l'ultima cifra è divisible per 7 -> 518 (iterabile)
7. 8 se il numero formato dalle sue ultime tre cifre è divisibile per 8.
8. 9 se la somma delle sue cifre è divisibile per 9.
9. 10 se la sua ultima cifra è 0
10. 11 se il numero ottenuto tralasciando l'ultima cifra meno l'ultima cifra è divisible per 11 (questo processo è iterabile)

Consideriamo il numero 27720. Esso è divisibile per

2 : l’ultima cifra è 0 quindi pari;

3 : la somma delle cifre è 18 quindi divisibile per 3;

4 : le ultime due cifre formano 20, un numero divisibile per 4;

5 : l’ultima cifra è 0;

6 : è divisibile sia per 2 che per 3 per quanto visto prima;

7 : il numero ottenuto tralasciando l’ultima cifra sommato a cinque volte l’ultima cifra è 2772. Per verificare che è divisibile per 7 iteriamo il processo: esso è divisibile per 7 se 287 lo è; quest’ultimo è divisibile per 7 se lo è 63, cosa chiaramente vera;

8 : il numero formato dalle ultime tre cifre è 720 chiaramente divisibile per 8 (90⋅8=720);

9 : la somma delle sue cifre è 18, quindi divisibile per 9;

10 : la sua ultima cifra è 0;

11 : 27720 è divisibile per 11 se e solo se 2772−0 lo è, se e solo se 277−2=275 lo è, se e solo se 27−5=22 lo è: chiaramente 22 è divisibile per 11.

In effetti 27720=5⋅7⋅8⋅9⋅11=23⋅32⋅5⋅7⋅11.

# Flash Cards
#nozioni-di-base 

Come si legge questo simbolo "$\mid$" quando si parla della divisione?
?
Si legge "divide"
<!--SR:!2025-07-23,4,272-->

Quali sono i criteri di divisibilità che valgono sempre per un numero $n \in \mathbb{N}$ ?
?
Ogni numero nell'insieme $\mathbb{N}$ è divisibile per se stesso ($n \mid n$) e per uno ($1 \mid n$)
<!--SR:!2025-07-23,4,270-->

Cosa sono i criteri di divisibilità?
?
I criteri di divisibilità sono regole che mi permettono di verificare per quali numeri sia divisibile un numero $n$.
<!--SR:!2025-07-23,4,272-->

Quali sono i divisori di questo numero 27720?
?
2, 3, 4, 5, 6, 7, 8, 9, 10, 11
# References
<!--SR:!2025-07-20,1,232-->