## Opgave 1 
Den retningsafledte af en funktion $f(x,y)$ i retningen $\vec{u}=(u_1,u_2)$ er givet ved $D_{\vec{u}}f(x,y)=\nabla f(x,y)\cdot\vec{u} =f_x(x,y)u_1+f_y(x,y)u_2.$ 
### Tilfælde 1:
$\vec{u}=\begin{pmatrix}1\\0\end{pmatrix}$ $D_{\vec{u}}f =f_x\cdot 1+f_y\cdot 0 =f_x.$ Altså: $D_{(1,0)}f=f_x.$ 
**Fortolkning:** Dette er den partielle afledte med hensyn til $x$. Den angiver, hvor hurtigt funktionen ændrer sig, når man bevæger sig i $x$-retningen, mens $y$ holdes konstant. 
### Tilfælde 2:
$\vec{u}=\begin{pmatrix}0\\1\end{pmatrix}$ $D_{\vec{u}}f =f_x\cdot 0+f_y\cdot 1 =f_y.$ Altså: $D_{(0,1)}f=f_y.$
**Fortolkning:** Dette er den partielle afledte med hensyn til $y$. 
Den angiver, hvor hurtigt funktionen ændrer sig, når man bevæger sig i $y$-retningen, mens $x$ holdes konstant. 
### Konklusion 
De partielle afledte er særlige tilfælde af den retningsafledte: $f_x=D_{(1,0)}f \qquad \text{og} \qquad f_y=D_{(0,1)}f.$ Det betyder, at $f_x$ og $f_y$ beskriver funktionens ændringshastighed i henholdsvis $x$- og $y$-aksens retninger.


## Opgave 2
Da den retningsafledede defineres som gradienten prikket med en enhedsvektor
hvis enhedsvektoren peger samme vej som gradienten får man størst stigning
da vinklen er 0
hvis enhedsvektoren peger modsat så er vinklen 180 og man får størst fald

På et bjerg er enhedsvektoren vejen man vælger at gå, og gradienten fortæller hvilken vej går mest opad, modsat er den vej der går mest nedad

## Opgave 3
Gør rede for at funktion er konstant i retningen vinkelret på gradienten. 
Hvis enhedsvektoren er vinkelret på gradienten er der en vinkel på 90 imellem dem
theta = 90 grader Så er det prikproduktet af gradienten og enhedsvektoren ganget med cos(90 grader)  = gradienten gange enhedsvektoren * 0 = 0
Den retningsafledte er så 0


## Opgaver i bogen:

Opg 1: $f(x,y) = x^2 - y^2$
og punktet (2, -1)

a) Gradienten i punktet (2, -1) 
$\nabla f(x,y) = f_x, f_y)$

De partielle afledte er 
$f_x = 2x,$
$f_y = -2y.$
Dermed
$\nabla f(x,y) = (2x, -2y).$
Indsætter punktet (2, -1) 
$\nabla f(2, -1) = (2 * 2, -2* (-1)) = (4,2).$
svar: 
$\nabla f(2,-1) = (4,2)$

b) $z = f(x,y) = x^2 - y^2$

finder punktet på overfladen
$z = f(2,-1) = 2^2 - (-1)^2 = 4-1=3.$
Punktet er altså
$(2,-1,3)$


