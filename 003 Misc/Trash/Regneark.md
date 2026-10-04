## Opgave 13. 
I den her opgave skal i finde ligningen der skal bevises selv. 
1. Lad $f(x)=xe^x$ så betegner $f^{(n)}$ den n-te afledte af f, e.g. $f = f^{(0)}$ og $f' = f^{(1)}.$ 
   a) Bestem de første 3 afledte af f og find en mønster. 
	Bruger produktreglen: $(f*g)' = f'*g + f*g'$
	$f'(x) = xe^x = (x)' \cdot e^x + x \cdot (e^x)'$
	= $e^x+xe^x$
	Formodning: $P(n) :$   $f^{(n)}(x)=e^x(x+n)$
	b) Brug induktion for at bevise at mønsteren i har fundet tidliger holder for enhver afledte. 
	
	Opskrift: 
	1. Find et mønster  
	2. Formuler påstanden P(n)  
	3. Basis: vis P(0)  
	4. Antag P(k) (induktionshypotesen)  
	5. Vis P(k+1)  
	6. Konkludér at P(n) gælder for alle n
	b) Brug induktion for at bevise at mønsteren i har fundet tidliger holder for enhver afledte. 

1. Lad $h$ være en uendlig mange gange differentiabel funktion og definere $H(x) := h(x)e^x.$ 
* a) bestem de første 3 afledte af H og find et mønster.
	Først differentierer jeg og bruger produktreglen:
	$(h(x)e^x)' = (h(x))' * e^x + h(x) * e^x$
	$h'(x)*e^x + h(x)*e^x$
	$e^x(h'(x)+h(x))$
	$H'(x)=e^x(h'(x)+h(x))$
	$H''(x) = e^x(h'(x)+h(x))+e^x(h''(x)+h'(x)).$
	$H''(x)=e^x(h''(x)+2h'(x)+h(x))$
	$H'''(x)$
	
	$H(x)=ex(h) H′(x)=ex(h′+h)$
	
	$H'(x)=e^x(h'+h)H′(x)=ex(h′+h) H′′(x)=ex(h′′+2h′+h)$
	$H''(x)=e^x(h''+2h'+h)H''(x)=ex(h''+2h′+h) H'''(x)=ex(h'''+3h''+3h'+h)$
	$H'''(x)=e^x(h'''+3h''+3h'+h)H'''(x)=e^x(h'''+3h''+3h'+h)$
	
	mønstret er binomialkoefficienter hvor vi har 
	1
	11
	121
	1331
	Disse svarer til rækkerne i Pascals trekant.
	Desuden forekommer alle afledte af h fra orden $n$ ned til orden $0$:
	$h^{(n)}(x),h^{(n-1)}(x),…,h′(x),h(x).$
	
	
* b) Brug induktion for at bevise at mønstret i har fundet tidligere holder for enhver afledte. 
	# Påstand:
	Formoder at
	$P(n): H^{n}(x)=e^x\sum_{k=0}^{n}\binom{N}{k}h^{{(n-k)}}(x)$
	Basistrin:
	$P(0) : H^0 (x) = e^x \sum_{k=0}^0 (\binom{0}{k} h^{(0-k)}(x)$
	Evaluerer:
	$e^x(h^{(0)}(x))$
	Induktionshypotese
	Vi antager P(k) at det gælder for et vilkårligt tal k 
	$H^{(k)}(x)=e^x\sum_{i=o}^{k}\binom{k}{i}h^{(k-i)}(x))$
	Vi skal vise at P(k+1) også gælder, dvs. 
	$H^{(k+1)}(x) = e^x \sum_{i=0}^{k+1} \binom{k+1}{i} h^{(k+1-i)}(x)$
	$H^{(k+1)}(x) = (H^{(k)}(x))'$ 
	Ved induktionshypotesen fås
	 = $( e^x \sum_{i=0}^{k} \binom{k}{i} h^{(k-i)}(x)'$
	Differentieret:
	$e^x \sum \binom{k}{i}h^{(k-i)}(x)+e^x (\sum \binom{k}{i}h{{(k-i)}}(x))'$
	$\sum \binom{k}{i}h{{(k-i)}}(x) '= \sum(h^{{(k-i)}}(x))'$ 
	$\sum h^{(k+1-i)}(x)$
	Så har vi 
	$e^x \sum \binom{k}{i}h^{(k-i)}(x)+e^x\sum h^{(k+1-i)}(x)$
	$= e^x(\sum \binom{k}{i}h^{(k-i)}(x)+\sum h^{(k+1-i)}(x))$
	Ved Pascals identitet 
	$\binom{k}{i-1}+\binom{k}{i} = \binom{k+1}{i}$  
	kan de to summer samles til  
	*$e^x\sum_{i=0}^{k+1} \binom{k+1}{i} h^{(k+1-i)}(x).$
	Dette er netop P(k+1), og induktionstrinnet er dermed vist.



