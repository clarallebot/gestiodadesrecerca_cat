---
title: Bones pràctiques en gestió de dades
teaching: 5
exercises: 0
questions:
- "Què són els principis FAIR?"
- "Què vol dir reproductibilitat?"
- "En què consisteix la gestió de dades de recerca?"
objectives:
- "Saber definir ´Dades de recerca´."
- "Saber definir ´Gestió de dades de recerca´."
- "Entendre el concepte de reproductibilitat."
- "Tenir una visió general de dades obertes en la gestió de dades de recerca"
keypoints:
- "Les dades de recerca poden tenir moltes formes diferents."
- "Un dels objectius de la gestió de dades de recerca és que la ciència sigui més reproductible."
---
### Bones pràctiques en gestió de dades


### Tidy data i fulls de càlcul


### Organitzar dades en un full de càlcul

L'objectiu aquí és parlar de tidy data en general. Però parlar en general és abstracte, i ja hem parlat molt en general en el tema anterior. Aquí farem servir els fulls de càlcul com a exemple d'un tipus de dades en particular, però els conceptes apresos es poden aplicar a altres tipus de dades. Els fulls de càlcul són un exemple útil per parlar de tidy data, perquè són una eina molt habitual, usada per molts investigadors. La majoria dels professionals de biblioteques també estan familiarizats amb dades en forma de taula.
 
A més de ser un exemple per parlar de tidy data, vull parlar de fulls de càlcul per introduir-vos a les Carpentries. Les Carpentries (The Carpentries [https://carpentries.org/](https://carpentries.org/)) és una organització sense ànim de lucre que té com a objectiu ensenyar eines computacionals relacionades amb dades a investigadors al voltant de el món. Dues de les coses que crec que són útils per al recolzament a la recerca:

* Tenen una sèrie de lliçons obertes per a tothom, amb llicències CC-BY. Les podeu trobar a la seva pàgina web al menú "Teach", dividides en Data Carpentry lessons, Software Carpentry lessons, i Library Carpentry lessons. Algunes d'elles estan traduïdes al castellà. Són lliçons que la comunitat de voluntaris de les Carpentries ha desenvolupat, i s'encarrega de mantenir. Són lliçons que es fan servir sovint, i per això estan a el dia, i molt polides. Molts i moltes bibliotecaris fan servir aquestes lliçons per organitzar tallers que són part dels data services de la biblioteca. Desenvolupar una lliçó porta temps, i moltes vegades no sóm experts en aquests temes, però en sabem prou per donar lliçons introductòries. Per això val molt la pena saber de l'existència d'aquestes lliçons. El contingut d'aquesta lliçó és una adaptació de la lliçó [Data Organization in Spreadsheets for Ecologists](https://datacarpentry.org/spreadsheet-ecology-lesson/).

* Les Carpentries tenen un programa per formar instructors. Es pot fer en línia, i és gratuït . Entre altres coses, el programa ensenya com aprenen els adults, i estratègies docents que són molt útils per a persones que poden no haver tingut mai formació de docent. En el meu cas, va ser una experiència transformadora.
* 
Si voleu, en comptes de llegir aquesta lliçó (reorganitzada, resumida i traduïda), podeu seguir directament la lliçó de les Carpentries: [Data Organization in Spreadsheets for Ecologists](https://datacarpentry.org/spreadsheet-ecology-lesson/). Tingueu en compte que la lliçó original de les Carpentries està pensada per fer-la amb un instructor, no per seguir-la des de la pàgina web. Dit això, jo crec que són molt útils si es segueixen per la pàgina web. 

### Organitzar dades en un full de càlcul

En aquesta part de la lliçó parlarem de la creació de les dades des del punt de vista de l'investigador creant les dades. Una bona organització de les dades és el fonament de qualsevol projecte d'investigació. Molts investigadors tenen les seves dades en fulls de càlcul, així que és el lloc en el qual comencen moltes investigacions.

EL primer concepte a tenir en compte és que els ordinadors i les persones entenen la informació de forma molt diferent. Els humans entenem informació desestructurada molt fàcilment, però sóm lents. Els ordinadors són ràpids, però molt literals. Per poder aprofitar les eines que existeixen per analitzar dades de forma robusta, ràpida i reproductible (per exemple, llenguatges de progamació com R o Python) hem d'assegurar-nos que les dades estan organitzades de la manera adequada per tal que, no només les persones les entenguin, sinó també les màquines. 

Parlarem de
* El format de les taules
* Evitar errors comuns
* Com tractar dades en fulls de càlcul
* Control de qualitat i manipulació
* Exportar dades des d'un programa de full de càlcul


No parlarem de com anàlitzar dades en fulls de càlcul, de generar gràfics, o d'introduir codi i equacions en fulls de càlcul. Les tècniques de què parlarem són sobre organització de dades. Idealment, són tècniques que els investigadors fan servir des del principi de treballar amb les seves dades. Si es cometen errors, aquests errors moltes vegades romanen en els fitxers de dades, i els veiem quan curem dades a la fi de l'procés. El que discutirem val per Excel, Open Office, Google Sheets i la majoria de programes d'edició de fulls de dades.

El segon concepte a tenir en compte és que els programes d'edició de fulls de càlcul tenen moltes funcionalitats. Podem entrar dades, organitzar-les, classificar-es, calcular-ne estadístiques, representar dades, etc. No obstant això, aquests programes són molt bons per a algunes d'aquestes tasques, però no tan bones per a altres. En particular, hem d'anar amb molt de compte quan usem fulls de càlcul per generar estadístiques i figures perquè aquests programes funcionen a força de clics i d'arrossegar el cursor, i això fa que sigui molt difícil replicar els passos que s'han seguit per generar, per exemple, una determinada figura. I també és molt fàcil aplicar per error una fórmula a les cel·les adjacents. Hi ha altres programes, com R o SAS, que són més adequats per calcular estadístiques i fer figures: més robustos, menys propensos a errors, i més reproduïbles.

Per què són bons els programes de gestió de fulls de càlcul? Per ordenar i "netejar" dades que després seran usades en altres programes. Quan preparem dades per compartir, precisament volem que les dades estiguin en aquest format net i ordenat.

### Exercici

### Errors habituals i bones pràctiques

Ara que ja heu reflexionat sobre l'exemple, parlem de bones pràctiques i d'errors habituals en fulls de càlcul. En les següents pàgines parlarem de 
* Estructura de les dades
* Reproductibilitat
* Dates

Al final, parlaré de com aplicar tots aquests conceptes a l'exemple que acabeu de veure. 

Aquí teniu una llista d'errors habituals: 
* Un dels problemes més comuns amb els fulls de càlcul és quan els investigadors els tracten com si fossin llibretes de laboratori. Anotant coses en els marges, usant colors i altres tipus de format per guardar el contingut, i confiant que l'usuari de les dades sap el context per entendre les dades. Colors de fons, negretes, marges gruixuts per marcar les separacions de la taula, etc són una bona manera d'ajudar a les persones a visualitzar els continguts d'un full de dades, i es poden usar tranquil·lament per això. Però és molt important no fer servir formats per guardar informació. Per exemple, si marquem en vermell els valors que no s'haurien de fer servir en un anàlisi perquè la bàscula no estava calibrada, estem guardant la informació en forma de format. La informació en forma de format es perdrà en guardar les dades en altres fitxers (com per exemple csv), també es perdrà en llegir les dades amb altres programes, i, en general, és difícil utilitzar la informació fins i tot en els fulls de càlcul mateixos. El millor és guardar aquesta informació en forma de columnes amb valors. Per exemple, en el cas de la balança no calibrada afegiríem una columna (e.g. Calibratge) i guardaríem els valors en forma de 0 i 1 o com un "sí" o "no".
* **No anotar els zeros**: de vegades  mesurem alguna cosa i el resultat és zero. Per exemple, hem mirat el número de rodents atrapats, i no n'hi havia cap. És important anotar el zero, i no deixar-lo en blanc, perquè un zero i un blanc són valors diferents. Un blanc és quan no hem pogut fer la mesura, o quan la mesura per algun motiu no està disponible. Els programes d'anàlisi de dades normalment interpreten blancs com a valor nul, i no com a zero. 
Utilitzar valors nuls problemàtics. Hi ha diferents raons per les que podem tenir valors nuls. De vegades val la pena registrar aquestes raons (e.g. la bàscula utilitzada no estava calibrada). Ja hem dit que no hem de fer servir el zero, perquè 0 és un valor. Quin valor nul hem de fer servir? Alguns valors nuls típics són deixar la cel·la en blanc (és a dir, no posar res), posar un valor en concret, com -999 o 999, posar un abreujament com NA o NULL o NAN, o utilitzar un símbol com + o -. Depenent de el programa amb què volem tractar les dades uns d'aquest valors nuls seran millors que altres. Per exemple, R entén "NA" com a valor nul, Python entén "None", i SQL entén "NULL". La majoria de programes entén un blanc com a valor nul, així que en general un blanc és un bon valor blanc. Valors que es poden confondre amb valors reals (com el 999 o el -999) són, en general, una mala idea. El que és essencial és que hi hagi documentació en algun lloc que defineixi el valor blanc que s'ha utilitzat.
* **Posar comentaris o unitats dins de les cel·les**. Només hi ha d'haver un tipus d'informació en cada cel·la. Un comentari o una unitat és un tipus d'informació que ha d'anar en la seva pròpia cel·la o a la documentació, no juntament amb els valors.
* **usar noms de variables que són problemàtics**. Els noms de variables han de ser descriptius, i és aconsellable que no incloguin espais, números, o caràcters especials. El caràcter "_" es pot usar enlloc d'espais. També es poden usar majúscules per fer els noms més fàcils de llegir. alguns exemples
    * Mal exemple: Màxim Temp (° C); Bon exemple: Max_Temp_C
    * Mal exemple: M / F; Bon exemple: sexe
    * Mal exemple: 1a obs; Bon exemple: Primera_Obs


### Estructura de les dades

L'organització que normalment és més efectiva per tenir dades ordenades, o "tidy data", és
* Totes les variables han d'estar en columnes. Les variables són el que estem mesurant. Com a "temperatura" o "pes"
* Cada observació ha d'estar en una fila.
* Només ha d'haver una informació en cada parcel·la. No s'han de posar dos tipus d'informació en una cela (e.g. el valor i la unitat)

Vegem un exemple. En la següent figura veiem dues taules. Les dues taules tenen la mateixa informació, però està estructurada de forma diferent. Quina organització és millor?

 
La resposta correcta és que depèn. Si això fossin dades que estem publicant en un article o una presentació, volem que les persones les entenguin el més ràpidament i clarament possible. La Taula 1 serà millor, perquè és més clar que les dades es van prendre en dos llocs, i durant 3 anys diferents. És més fàcil visualitzar, per exemple, que els valors a Washington són més alts que els valors a Oregon. Però la taula 2 és millor per organitzar les dades en un full de càlcul. A la taula 2 veiem clarament que estem prenent dades de tres variables: lloc, any i abundància. Si en un moment determinat volem afegir variables (per exemple prendre notes de la presència de sequera durant aquest any) ens serà molt fàcil fer-ho en la taula 2, i serà complicat a la taula 1. També serà més fàcil fer servir la taula 2 si la recol·lecció de dades es fa a intervals irregulars (per exemple, dues dades en alguns anys, una dada en altres). La taula 2 serà més fàcil d'usar per un programa com R, python, o SAS.

Quan les dades es comparteixen en un repositori haurien de tenir l'estructura de la taula 2, no la de la taula 1.

Un cop ja tenim l'estructura de taula, què és millor? Tenir moltes taules amb poca informació o tenir una gran taula amb molta informació? En general fer servir moltes taules o moltes pestanyes no és recomanable, perquè és més fàcil cometre errors (no col·locar la mateixa informació de la mateixa manera en cada taula) i perquè és molt més difícil llegir les dades amb aquesta estructura amb altres programes. Una gran taula és millor que moltes taules petites. I la majoria de vegades volem combinar la informació de les diferents taules. 

### Estratègies per generar dades reproductibles

Per garantir la reproductibilitat del projecte, i assegurar-nos que no perdem res per accident, és molt important **guardar sempre una còpia de les dades brutes sense modificar**.
 
Ja hem explicat que un problema dels fulls de càlcul és que és difícil reproduir els passos que s'han seguit per obtenir un determinat resultat. Per això és important **prendre notes dels passos que seguim**. Per exemple, podríem obrir una pestanya nova, anomenar-la "readme" o "notes". O podríem crear un fitxer amb Notepad o qualsevol altre programa d'edició de textos, i guardar-lo al costat del nostre full de càlcul. A la figura 1 en teniu un exemple.

Aquest fitxer de notes segurament no serà el que es acabi sent compartit quan les dades es facin públics en un repositori, però parts d'aquest podrien acabar en la documentació final. I un fitxer d'aquest tipus ens serà molt útil si mesos després no recordem com vam tractar les dades, o si hem de repetir els mateixos passos amb una nova versió de les dades. 

Aquest fitxer de documentació també és un bon lloc on apuntar totes les **metadades de les dades**. Incloure metadades a la taula és un error comú en fulls de càlcul. Notes a les cel·les del costat de la taula, o notes barrejades amb els valors. És important documentar les metadades, però s'ha de fer en un fitxer de documentació, no amb les dades. Totes les taules hauríen de tenir un fitxer de documentació amb un "data dictionary", una llista de totes les variables, amb les seves definicions respectives (encara que sembli obvi, sovint no ho és), i tota la informació que ens cal per ententre-les bé: unitats, rang de valors acceptats, abreviacions, etc. 

Finalment, per garantir que el fitxer de dades perduri amb el temps hauríem de **guardar-lo en un format de text pla**, com ara csv o fitxers delimitats per tabulacions. En general guardar fulls de càlculs en aquest fitxer és fàcil triant l'opció de "Anomena i desa". Aquests formats de text pla normalment es poden obrir fàcilment amb els editors de fulls de càlcul.

### Dates

És molt comú guardar les dates en una columna en un full de dades. Aquests editors tenen un munt de formats pre-determinats per dates, i encara que pugui semblar útil, moltes vegades aquest format pre-determinat causa molts errors. Per exemple:

* Quan fem servir abreviacions en les dades que el programa entén com a dates, i que canvia automàticament.
* Quan entrem dates i no entrem l'any, normalment el programa assumeix que l'any correcte és l'any en què ens trobem, i l'entra automàticament, sense dir-nos-ho. 
* Quan guardem les dades en altres formats, com csv, es guarden les dades tal com les veiem. Si la nostra visualització inclou només dia i mes, i no l'any, la informació d'any la perdrem.
* La manera com estan guardades les dates en els programes de full de càlcul és utilitzant un dia de referència i comptant quants dies han passat des d'aquell dia. Durant molts anys els dies de referència d'Excel a Windows i a Mac era diferent, i els fulls de càlcul que s'havien creat amb un sistema operatiu tenien dates incorrectes (4 anys de diferència) si s'obrien amb un altre sistema operatiu. Aquest problema pot persistir ara si obrim fitxers Excel antics. 

La forma més clara de guardar les dates és tenir una columna per a cada element: any, mes, dia, i hora, minut, segon si són necessaris. D'aquesta manera no hi haurà confusions amb diferents estàndards ( fem servir dd / mm / yyyy o mm / dd / yyyy?), o errors deguts a diferents programes i sistemes operatius.

En general, quan es tenen dades que inclouen dates (una situació molt comú) val la pena recordar que hi ha un estàndard per dates, l'ISO 8601 segons el qual el format adequat és yyyy-mm-dd. Les pàgines de la Wikipedia en [castellà](https://es.wikipedia.org/wiki/ISO_8601) o [anglès](https://en.wikipedia.org/wiki/ISO_8601) tenen molta informació sobre com utilitzar l'estàndard.

> ## Incís
> 
> Aquí explicarem un incís.
> 
{: .callout}

> ## Exercici
>
> Us proposo aquest exercici
>
> > ## Solució
> >
> > Aquesta és la solució de l'exercici
> >
> {: .solution}
{: .challenge}



> ## Lectures recomanades
>
> *   Article 1
>
> *   Article 2
{: .challenge}
