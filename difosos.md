####**1. Desenvolupament de programari (’software’)**

#####**1.5 Característiques dels llenguatges més difosos.**

Existeixen molts llenguatges de programació diferents, fins al punt que moltes tecnologies tenen el seu llenguatge propi. Cada un d’aquests llenguatges té un seguit de particularitats que el fan diferent de la resta. 

Els llenguatges de programació més difosos són aquells que més es fan servir en cadascun dels diferents àmbits de la informàtica. 

Els llenguatges de programació més difosos corresponents a diferents àmbits, a diferents tecnologies o a diferents tipus de programació tenen una sèrie de característiques en comú que són les que marquen les similituds entre tots ells.

#####**1.5.1 Característiques de la programació estructurada**.

 La programació estructurada va ser desenvolupada pel neerlandès Edsger W. Dijkstra i es basa en el denominat teorema de l’estructura. Per això utilitza únicament tres estructures: **seqüència, selecció i iteració**.

D’aquesta forma les característiques de la programació estructurada són la **claredat, el teorema de l’estructura i el disseny descendent**. 

######Claredat 

Hi haurà d’haver prou informació al codi per tal que el programa pugui ser entès i verificat: comentaris, noms de variables comprensibles i procediments entenedors... Tot programa estructurat pot ser llegit des del principi a la fi sense interrupcions en la seqüència normal de lectura. 

######Teorema de l’estructura 

Demostra que tot programa es pot escriure utilitzant únicament les tres estructures bàsiques de control: 
- **Seqüència**: instruccions executades successivament, una darrere l’altra. Un exemple de l’estructura bàsica de seqüència, on primer s’executarà la sentència A i, posteriorment, la B. 

- **Selecció**: la instrucció condicional amb doble alternativa, de la forma “si condició, llavors SentènciaA, sinó SentènciaB”.

- **Iteració**: el bucle condicional “mentre condició, fes SentènciaA”, que executa les instruccions repetidament mentre la condició es compleixi.

######**Disseny descendent** 

El disseny descendent és una tècnica que es basa en el concepte de “divideix i venceràs” per tal de resoldre un problema en l’àmbit de la programació. Es tracta de la resolució del problema al llarg de diferents nivells d’abstracció partint d’un nivell més abstracte i finalitzant en un nivell de detall. 

Exemple del disseny descendent: A partir del problema1 s’obtenen diversos subproblemes (subproblema 1.1, subproblema 1.2 i subproblema 1.3). La resolució d’aquests subproblemes serà molt més senzilla que la del problema original per tal com se n’ha reduït considerablement l’abast i la mida. De forma iterativa es pot observar com aquests subproblemes es tornen a dividir, a la vegada, en altres subproblemes.

######**Programació modular**

Quan es parla de programació modular, ens referim a la divisió d’un programa en parts més manejables i independents. Una regla pràctica per aconseguir aquest propòsit és establir que cada segment del programa no excedeixi, en longitud, d’un pam de codificació.

En la majoria de llenguatges, els mòduls es tradueixen a: 
- Procediments: són subprogrames que duen a terme una tasca determinada i retornen 0 o més d’un valor. S’utilitzen per estructurar un programa i millorar la seva claredat. 
- Funcions: són subprogrames que duen a terme una determinada tasca i retornen un únic resultat o valor. S’utilitzen per crear operacions noves que no ofereix el llenguatge.

#####**1.5.1 Característiques de la programació orientada a objectes**.

Un dels conceptes importants introduïts per la programació estructurada és l’abstracció de funcionalitats a través de funcions i procediments. Aquesta abstracció permet a un programador utilitzar una funció o procediment coneixent només què fa, però desconeixent el detall de com ho fa. 

Aquest fet, però, té diversos inconvenients: 
- Les funcions i procediments comparteixen dades del programa, cosa que provoca que canvis en un d’ells afectin a la resta. 
- Al moment de dissenyar una aplicació és molt difícil preveure detalladament quines funcions i procediments necessitarem. 
- La reutilització del codi és difícil i acaba consistint a copiar i enganxar determinats trossos de codi, i retocar-los. Això és especialment habitual quan el codi no és modular.

>_L’**orientació a objectes** (en endavant, OO) és un paradigma de construcció de programes basat en una abstracció del món real_.

En un programa orientat a objectes, l’abstracció són els objectes. Aquests objectes són una representació directa d’alguna cosa del món real, com ara un llibre, una persona, una organització, una comanda, un empleat...

>_Un **objecte** és una combinació de dades (anomenades atributs) i mètodes (funcions i procediments) que ens permeten interactuar amb ell. En OO, doncs, els programes són conjunts d’objectes que interactuen entre ells a través de missatges (crides a mètodes)_.

Els llenguatges de POO (programació orientada a objectes) són aquells que implementen més o menys fidelment el paradigma OO. La programació orientada a objectes es basa en la integració de 5 conceptes: **abstracció**,**encapsulació**, **modularitat**, **jerarquía** i **polimorfisme**.

######Abstracció

Procés en el qual se separen les propietats més importants d’un objecte de les que no ho són, per mitjà de l’abstracció es defineixen les característiques essencials d’un bjecte del món real, els atributs i comportaments que el defineixen com a tal, per després modelar-lo en un objecte de programari. En el procés d’abstracció no ha de  ser preocupant la implementació de cada mètode o atribut, només cal definir-los.

En la tecnologia orientada a objectes l’eina principal per suportar l’abstracció és la classe. Es pot definir una classe com una descripció genèrica d’un grup d’objectes que comparteixen característiques comunes, les quals són especificades en els seus
atributs i comportaments.

######Encapsulació

Permet als objectes triar quina informació és publicada i quina és amagada a la resta dels objectes. Per això els objectes solen presentar els seus mètodes com a interfícies públiques i els seus atributs com a dades privades o protegides, essent inaccessibles des d’altres objectes. Les característiques que es poden atorgar són:

-	Públic: qualsevol classe pot accedir a qualsevol atribut o mètode declarat com a públic i utilitzar-lo.
-	Protegit: qualsevol classe heretada pot accedir a qualsevol atribut o mètode declarat com a protegit a la classe mare i utilitzar-lo.
-	Privat: cap classe no pot accedir a un atribut o mètode declarat com a privat i utilitzar-lo.

######Modularitat

Permet poder modificar les característiques de cada una de les classes que defineixen un objecte, de forma independent de la resta de classes en l’aplicació. Si una aplicació es pot dividir en mòduls separats, normalment classes, i aquests mòduls es poden compilar i modificar sense afectar els altres, aleshores aquesta aplicació ha estat implementada en un llenguatge de programació que suporta la modularitat.

######Jerarquia

Permet l’ordenació de les abstraccions. Les dues jerarquies més importants d’un sistema complex són l’**herencia** i l’**agregació**.

L’**herencia** també es pot veure com una forma de compartir codi, de manera que quan s’utilitza l’herència per definir una nova classe només s’ha d’afegir allò que sigui diferent, és a dir, reaprofita els mètodes i variables, i especialitza el comportament.

Es pot identificar una classe _pare_ anomenada _treballador_ i dues classes _filles_, és a dir dos subtipus de treballadors, _administratiu_ i _professor_.  

L’**agregació** és un objecte que està format de la combinació d’altres objectes o components. Així, un ordinador es compon d’una CPU, una pantalla, un teclat i un ratolí, i aquests components no tenen sentit sense l’ordinador.
 
######El polimorfisme

Característica que permet donar diferents formes a un mètode, ja sigui en la definició com en la implementació.          
     
La **sobrecàrrega** (_overload_) de mètodes consisteix a implementar diverses vegades un mateix mètode però amb paràmetres diferents, de manera que, en invocar-lo, el compilador decideix quin dels mètodes s’ha d’executar, en funció dels paràmetres de la crida.              

La **sobreescriptura** (_override_) de mètodes consisteix a reimplementar un mètode heretat d’una superclasse exactament amb la mateixa definició (incloent nom de mètode, paràmetres i valor de retorn).                                                                                                        

