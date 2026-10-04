# Kursusgang 5 - Forberedelse  

#summer #sigma #fakultet  
## Formål  

Målet er at kunne læse og forstå sigma-notation (summationer).  
Vi fokuserer på notation, ikke på hvordan summer beregnes.
  
---  
## Sigma-notation  

Sigma-tegnet  
$$  

\sum  

$$
bruges til at skrive summer med mange led kompakt.  
Eksempel:  
$$  

\sum_{i=1}^{100} a_i  

=  

a_1+a_2+a_3+\cdots+a_{100}  

$$
---  
## Summationsindeks  

Bogstavet under sigma kaldes summationsindekset.  

Eksempel:  
$$  

\sum_{i=1}^{100} a_i  

$$
og  
$$  

\sum_{k=1}^{100} a_k  

$$
betyder præcis det samme.  

Valget af bogstav er ligegyldigt. 

---  
## Start- og slutværdi  

Summen behøver ikke starte ved 1.  

Eksempel:  
$$  

\sum_{n=-17}^{89} a_n  

=  

a_{-17}+a_{-16}+\cdots+a_{89}  

$$
Man kan starte og slutte ved vilkårlige hele tal. 

---  
## Når indekset optræder flere steder  

Hvis summationsindekset forekommer flere gange, indsættes værdien alle steder.  

Eksempel:  
$$  

\sum_{j=3}^{24} b_j j^2  

=  

b_3 3^2+b_4 4^2+\cdots+b_{24}24^2  

$$
---  
## Når indekset ikke optræder  

Eksempel:  
$$  

\sum_{n=1}^{15} a_i  

$$
Indekset $n$ optræder ikke i udtrykket.  

Derfor får man  
$$  

a_i+a_i+\cdots+a_i  

=  

15a_i  

$$
---  
## Uendelige summer  
Eksempel:  
$$  

\sum_{n=0}^{\infty} a_n  

=  

a_0+a_1+a_2+\cdots  

$$
En uendelig sum stopper aldrig. 

---  
## Produktnotation  

På samme måde som summer skrives produkter med  
$$  

\prod  

$$
Eksempel:  
$$  

\prod_{i=1}^{n} a_i  

=  

a_1a_2a_3\cdots a_n  

$$
---  
## Fakultet  

Definition:  
$$  

n!  

=  

\prod_{i=1}^{n} i  

=  

1\cdot2\cdot3\cdots n  

$$
Eksempler:  
$$  

4!=24  

$$
$$  

5!=120  

$$
---  
## Vigtig sum  

En sum som optræder flere gange i materialet er  
$$  

\sum_{n=0}^{\infty}\frac{x^n}{n!}  

=  

1+x+\frac{x^2}{2!}+\frac{x^3}{3!}+\cdots  

$$
Denne er vigtig fordi den senere forbindes med eksponentialfunktionen. 

---  
## Sammenhæng med tallet e  

Ved forelæsningen vises at  
$$  

e  

=  

\sum_{n=0}^{\infty}\frac{1}{n!}  

$$
---  
## Ting jeg skal kunne  

- [x] Ekspandere en sum skrevet med sigma-notation  

- [x] Skrive en ekspanderet sum med sigma-notation  

- [x] Identificere summationsindekset  

- [x] Forstå hvad et produkttegn betyder  

- [x] Beregne små fakulteter  

- [x] Forstå notation som  

$$  

\sum_{n=0}^{\infty}\frac{x^n}{n!}  

$$
--- 
## Intuition  

Sigma:  

$$  

\sum  

$$
betyder "læg sammen".  

Produkt:  
$$  

\prod  

$$
betyder "gang sammen".  

Summationsindekset er blot en tællevariabel, som løber gennem alle værdier mellem start- og slutindekset.