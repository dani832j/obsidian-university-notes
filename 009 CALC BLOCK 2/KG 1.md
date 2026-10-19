#### Riemann Sum
![[Pasted image 20261019213600.png|330]]
1. ![[Pasted image 20261019193927.png]]

Trin 1: Vælger punkterne i øverste venstre hjørne af de 6 kvadrater:
$(0,2), (1,2), (3,2),$
$(0,1), (0,2), (0,3).$

Trin 2: Beregner Delta A
Hvert kvadrat har sidelængden 1, så Delta A = $1 * 1 = 1$

Trin 3: Indsæt punkterne i funktionen
Funktionen er f(x,y) = 5 - x - y.
f(0,2) = 3
f(1,2) = 2
f(2,2) = 1
f(0,1) = 4
f(1,1) = 3
f(2,1) = 2

Trin 4: Opskriv riemann-summen
$\sum f(x_{ij}^{*}, y_{ij}^{*}) \Delta{A}$
= (3+2+1+4+3+2) * 1

Trin 5: Regn summen ud
= 15



#### Itererede integraler
1. ![[Pasted image 20261019194055.png]]

Trin 1: Start med det inderste integral
integrerer mht. y

Trin 2: finder stamfunktion i den indre variabel
$\int (xy + y^2) dy$ 

da x er konstant trækkes den udenfor

$\int xy dy = x \int y dy$

$\int y^n dy = \frac{y^{n+1}}{n + 1}$
andet led
$y^2$
$\int y^2 dy = \frac{y^3}{3}$

trin 3: saml stamfunktionen
Kalder den F(y)
$\int^x_{0} (xy + y^2)dy = [F(y)]^x_{0}$

Trin 4: Indsæt indre grænser

F(b) - F(a)
øvre grænse er x og nedre er 0
så F(x) - F(0) 

Trin 5: Kig på det ydre integral
Efter indsættelse af de indre grænser står der nu et udtryk,
som kun indeholder x.

Det ydre integral har differentialet dx, så der integreres nu
med hensyn til x.

Find en stamfunktion af udtrykket i x ved hjælp af potensreglen

∫ x^n dx = (x^(n+1))/(n+1)

Anvend derefter de ydre grænser:

[F(x)]¹₀ = F(1) - F(0)

Resultatet er værdien af det itererede integral.

2. ![[Pasted image 20261019194107.png]]

#### Omskriv til itererede integraler
1. ![[Pasted image 20261019194141.png]]
2. ![[Pasted image 20261019194204.png]]
3. ![[Pasted image 20261019194212.png]]

#### Skitser integrationsområde og beregn integralet
1. ![[Pasted image 20261019194246.png]]

#### Beregn rumfang
1. ![[Pasted image 20261019194310.png]]
2. ![[Pasted image 20261019194317.png]]