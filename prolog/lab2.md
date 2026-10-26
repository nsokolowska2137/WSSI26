# Ćwiczenie 1

**L2.Cw1.1**
*true* , fakty para/2 nie są potrzebne

**L2.Cw1.2**
ground(para(X,X)). -> *false*
ground(para(tom,tom)). -> *true*
dzieje się tak dlatego, że X to zmienna wolna i nie jest ugruntowana, a 'tom' jest ugruntowane

**L2.Cw1.3**
dane zostają ugruntowane do *Dane = ksiazka(hobbit,tolkien)*

**L2.Cw1.4**
ground(posiada(anna,ksiazka(hobbit,tolkien))). -> *true*
ground(posiada(anna,ksiazka(hobbit,Autor))). -> *false* 
To drugie jest *false*, bo zawiera zmienną wolną 'Autor'

**L2.Cw1.5**
### Wyjaśnij, dlaczego ground(kot(reks)). zwraca true bez faktu kot(reks).
dzieje się tak, ponieważ wyrażenie ground(kot(reks)). nie zawiera zmiennych wolnych, więc jest ugruntowane. 

# Ćwiczenie 2

**L2.Cw2.1**


**L2.Cw2.2**


**L2.Cw2.3**


**L2.Cw2.4**


**L2.Cw2.5**
