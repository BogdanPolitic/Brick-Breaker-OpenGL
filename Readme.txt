


04.11.2018
POLITIC ANDREI-BOGDAN, 335CC
TEMA 1 EGC



	BREAK BREAKER
	=============
	Varianta de joc pe care am implementat-o incepe la un nivel scazut de dificultate, iar pe parcurs dificultatea creste, dar jocul este inca destul de usor de terminat. Player-ul are 4 vieti (cea curenta, plus inca 3 - bilele din partea stanga jos a ecranului). Baza albastra este decorativa.
	Dificultatea se bazeaza pe powerUp-uri. PowerUp-urile sunt de 3 tipuri:
		-> galbene 	(la fiecare acumulare de doua, platforma se largeste)
		-> verzi 	(la fiecare acumulare de doua, viteza bilei creste, si de asemenea creste si viteza de cadere a powerUp-urilor)
		-> albastre (la fiecare acumulare de doua, caramizile se maresc in latime si inaltime, cu acelasi raport de 1,1f)
	In concluzie, scopul powerUp-urilor este de a scadea timpul de terminare al jocului, iar dificultatea nu creste in mod deosebit, deoarece viteza mai mare a bilei se compenseaza cu platforma mai lunga.




	Cateva controale (DOAR PENTRU TEST. A NU SE FOLOSI IN CAZUL CHALLENGE-ULUI):
		-> tasta "3" -> creste spatiul dintre caramizi pe axa X
		-> tasta "4" -> scade spatiul dintre caramizi pe axa X
		-> tasta "5" -> creste spatiul dintre caramizi pe axa Y
		-> tasta "6" -> scade spatiul dintre caramizi pe axa Y
		-> tasta "7" -> creste dimensiunea X a caramizilor
		-> tasta "8" -> scade dimensiunea X a caramizilor
		-> tasta "9" -> creste dimensiunea Y a caramizilor
		-> tasta "0" -> scade dimensiunea Y a caramizilor
		-> tasta "=" -> creste dimensiunea (X) a platformei
		-> tasta "-" -> scade dimensiunea (X) a platformei
		-> tasta "]" -> creste viteza bilei
		-> tasta "[" -> scade viteza bilei
	Apasarea controalelor trebuie sa fie discreta, nu continua. Nu recomand folosirea lor in timpul jocului, deoarece pot cauza bug-uri.