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
• **Seqüència**: instruccions executades successivament, una darrere l’altra. Un exemple de l’estructura bàsica de seqüència, on primer s’executarà la sentència A i, posteriorment, la B. 

• **Selecció**: la instrucció condicional amb doble alternativa, de la forma “si condició, llavors SentènciaA, sinó SentènciaB”.

• **Iteració**: el bucle condicional “mentre condició, fes SentènciaA”, que executa les instruccions repetidament mentre la condició es compleixi.

######**Disseny descendent** 

El disseny descendent és una tècnica que es basa en el concepte de “divideix i venceràs” per tal de resoldre un problema en l’àmbit de la programació. Es tracta de la resolució del problema al llarg de diferents nivells d’abstracció partint d’un nivell més abstracte i finalitzant en un nivell de detall. 

Exemple del disseny descendent: A partir del problema1 s’obtenen diversos subproblemes (subproblema 1.1, subproblema 1.2 i subproblema 1.3). La resolució d’aquests subproblemes serà molt més senzilla que la del problema original per tal com se n’ha reduït considerablement l’abast i la mida. De forma iterativa es pot observar com aquests subproblemes es tornen a dividir, a la vegada, en altres subproblemes.

######**Programació modular**

Quan es parla de programació modular, ens referim a la divisió d’un programa en parts més manejables i independents. Una regla pràctica per aconseguir aquest propòsit és establir que cada segment del programa no excedeixi, en longitud, d’un pam de codificació.

En la majoria de llenguatges, els mòduls es tradueixen a: 
• Procediments: són subprogrames que duen a terme una tasca determinada i retornen 0 o més d’un valor. S’utilitzen per estructurar un programa i millorar la seva claredat. 
• Funcions: són subprogrames que duen a terme una determinada tasca i retornen un únic resultat o valor. S’utilitzen per crear operacions noves que no ofereix el llenguatge.

#####**1.5.1 Característiques de la programació orientada a objectes**.

Un dels conceptes importants introduïts per la programació estructurada és l’abstracció de funcionalitats a través de funcions i procediments. Aquesta abstracció permet a un programador utilitzar una funció o procediment coneixent només què fa, però desconeixent el detall de com ho fa. 

Aquest fet, però, té diversos inconvenients: 
• Les funcions i procediments comparteixen dades del programa, cosa que provoca que canvis en un d’ells afectin a la resta. 
• Al moment de dissenyar una aplicació és molt difícil preveure detalladament quines funcions i procediments necessitarem. 
• La reutilització del codi és difícil i acaba consistint a copiar i enganxar determinats trossos de codi, i retocar-los. Això és especialment habitual quan el codi no és modular.
