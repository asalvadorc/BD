Bases de Dades

- [Tema 2: MODEL ENTITAT-RELACIÓ](index.md)
- [Objectius i coneixements previs](objectius_i_coneixements_previs.md)
- [1. Introducció](1_introducci.md)
- [2. Exemple](2_exemple.md)
- [3. Les Entitats del Model E/R](3_les_entitats_del_model_er.md) 
  - [3.1 Entitats](31_entitats.md) 
    - [Aplicació a l'exemple](aplicaci_a_lexemple.md)
  - [3.2 Atributs](32_atributs.md) 
    - [Aplicació a l'exemple](aplicaci_a_lexemple0.md)
  - [3.3 Dominis](33_dominis.md)
- [Exercicis](exercicis.md)
- [4. Les Relacions del Model E/R](4_les_relacions_del_model_er.md) 
  - [4.1 Relació](41_relaci.md) 
    - [Aplicació a l'exemple](aplicaci_a_lexemple1.md)
  - [4.2 Atributs de Relació](42_atributs_de_relaci.md) 
    - [Aplicació a l'exemple](aplicaci_a_lexemple2.md)
  - [4.3 Tipus de Relació o Cardinalitat](43_tipus_de_relaci_o_cardinalitat.md) 
    - [Aplicació a l'exemple](aplicaci_a_lexemple3.md)
- [Exercicis](exercicis0.md)
- [5. Relacions de grau major que dos](5_relacions_de_grau_major_que_dos.md)
- [6. Model E/R Estès](6_model_er_ests.md) 
  - [6.1 Cardinalitat màxima i mínima. Participació total.](61_cardinalitat_mxima_i_mnima_participaci_total.md) 
    - [Aplicació a l'exemple](aplicaci_a_lexemple4.md)
  - [6.2 Entitats dèbils](62_entitats_dbils.md)
  - [6.3 Generalització i herència](63_generalitzaci_i_herncia.md) 
    - [Aplicació a l'exemple](aplicaci_a_lexemple5.md)
- [7. Restriccions externes](7_restriccions_externes.md)
- [Exercicis](exercicis1.md)
- [Informació addicional](informaci_addicional.md)
- [Auto-avaluació](autoavaluaci.md)

[« Anterior](6_model_er_ests.md) | [Següent »](aplicaci_a_lexemple4.md)
# <a name="main"></a>**6.1 Cardinalitat màxima i mínima. Participació total.**




CARDINALITAT MÀXIMA I MÍNIMA 
### **CARDINALITAT MÀXIMA i MÍNIMA** d’una entitat que participa en una relació, són respectivament el número màxim i mínim d’ocurrències d’aquesta entitat que estan relacionades amb una ocurrència de l’altra entitat
![ref1]

Per exemple 

Un empleat pot dirigir 0 o 1 departament, i un departament és dirigit (com a mínim i com a màxim) per 1 empleat. Ho posarem entre parèntesis **(card. mínima, card. màxima)** al costat de l’entitat<a name="_ftnref1"></a>[<sup>\[1\]</sup>](#_ftn1 "_ftnref1"). En realitat el nou concepte és la cardinalitat mínima, ja que la màxima és la cardinalitat d'abans. Els valors habituals de cardinalitat mínima són 0 i 1. 



PARTICIPACIÓ TOTAL O PARCIAL 

Una entitat participa de forma **TOTAL** en una relació, si totes les seues ocurrències participen en alguna ocurrència de la relació. Així DEPARTAMENT participa de forma total, ja que tot departament té un cap. En canvi EMPLEAT no participa de forma total, ja que no tot empleat dirigeix un departament. Les entitats que participen de forma total tenen de cardinalitat mínima 1. Les que no 0. **Per tant amb la participació total o parcial aconseguim el mateix que amb la cardinalitat mínima.**

Representarem que una entitat participa de forma total en una relació amb una doble ratlla 

![ref2]





Com que de les dues maneres anteriors, la cardinalitat mínima i la participació total o parcial, aconseguim exactament el mateix, en aquestos apunts **només representarem la participació total o parcial**, ja que té una representació gràfica molt senzilla. 


\-----

<a name="_ftn1"></a>[<sup>\[1\]</sup>](#_ftnref1 "_ftn1") Hi ha autors que les posen a l’inrevés, en les altres entitats. 

[« Anterior](6_model_er_ests.md) | [Següent »](aplicaci_a_lexemple4.md)

Llicenciat sota la [Llicència Creative Commons Reconeixement NoComercial CompartirIgual 3.0](http://creativecommons.org/licenses/by-nc-sa/3.0/)
**Created with an evaluation copy of Aspose.Words. To discover the full versions of our APIs please visit: https://products.aspose.com/words/**

[ref1]: 61_cardinalitat_mxima_i_mnima_participaci_total.002.png
[ref2]: 61_cardinalitat_mxima_i_mnima_participaci_total.003.png
