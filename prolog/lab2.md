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
\+ pies(tom). -> *true* , ponieważ tom nie jest określone jako pies, więc negacja jest zgodna z bazą danych

**L2.Cw2.2**
kot(tom). -> *true*
\+ kot(tom). -> *false*

**L2.Cw2.3**


**L2.Cw2.4**


**L2.Cw2.5**

# Ćwiczenie 3

**L2.Cw3.1**
lubi(filip,ania).-> *true*
lubi(ania,filip). -> *false*
oznacza to, że Filip lubi Anię, ale Ania nie lubi Filipa; relacja jest asymetryczna
**L2.Cw3.2**
lubi(Kto, dawid). -> *Kto = bartek*

**L2.Cw3.3**


**L2.Cw3.4**


**L2.Cw3.5**

# Ćwiczenie 4

**L2.Cw4.1**
**L2.Cw4.2**
**L2.Cw4.3**
**L2.Cw4.4**
**L2.Cw4.5**
