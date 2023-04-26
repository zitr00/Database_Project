# Database_Project

### Se considera o aplicatie pentru evidenta studentilor.
Pentru orice student trebuie sa se salveze intr-o baza de date Oracle urmatoarele informatii:
-	nume
-	prenume
-	nr. Legitimatie
-	medie generala
-	media pe anul1
-	media pe anul2
-	media pe anul3
-	informatii despre notele obtinute: Disciplina, Anul de studiu (in care se studiaza disciplina), Nr. Prezentare, Data prezentarii, Nota obtinuta


#### Stiind ca ‘numele’ nu depaseste 15 caractere, ‘prenumele’ nu depaseste 20 caractere, ‘numarul de Legitimatie’ are exact 6 caractere, toate mediile sunt numere cuprinse intre 0 si 10, un student se poate prezenta de oricate ori la un examen si ca in calculul mediilor intra nota maxima obtinuta pentru fiecare disciplina, implementam:
1.	Să se realizeze proiectarea bazei de date aferente (structura de tabele, structura de coloane a fiecărei tabele, constrângeri).
2.	Sa se scrie comenzile SQL pentru tabelele proiectate la punctul anterior.
3.	Să se scrie comenzile SQL pentru popularea bazei de date cu urmatoarele informatii:
-AICI POZA-
4.	Să se scrie o interogare care sa afiseze studentii care au discipline nepromovate.
5.	Sa se genereze un raport care sa cuprinda numele,prenumele, anul de studiu si numarul legitimatiei fiecarui student. (anul de studiu va fi maximul dintre anii la care are trecute note).
6.	Sa se genereze un raport detaliat care sa cuprinda numele,prenumele, nr. legitimatiei, si toate notele finale la disciplinele promovate (denumirea diciplinei +nota), ordonat dupa nume, prenume, an de studiu, disciplina.
7.	Sa se scrie un trigger care la adaugarea unei note sa calculeze automat media pe anul respectiv si media generala. (media se va face indiferent de nota obtinuta, considerand nota maxima pe disciplina)
8.	Sa se scrie o functie care sa primeasca ca si parametru disciplina si sa returneze promovabilitatea la aceasta disciplina exprimata in procente.
9.	Sa se afiseze studentii care au toate disciplinele promovate la anul de studiu in care sunt, precizand numarul de Legitimatie, numele, prenumele, media pe anul de studiu in care sunt, ordonat dupa nume.
10.	Sa se afiseze studentul care are cele mai multe prezentari la examene, precizand numele, prenumele, numarul de prezentari si rata lui de promovabilitate.
