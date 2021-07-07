---
title: Curació de dades de recerca en repositoris. Organització de dades
teaching: 30
exercises: 0
questions:
- "Què és la curació de dades?"
- "Quines activitats formen part de la curació de dades de recerca?"
- "Quines qualitats ha de tenir un conjunt de dades per ser publicat? Què vol dir que un conjunt de dades és ´tidy´ o ordenat?"
objectives:
- "Saber definir ´Curació de dades de recerca´."
- "Saber enumerar activitats necessaries per la curació de dades de recerca."
- "Saber reconèixer els elements que s'han d'avaluar en curar un conjunt de dades."
- "sabran descriure l'estructura d'un conjunt de dades en un full de càlcul per considerar-lo ´tidy´"
- "sabran identificar errors en l'estructura de dades en un full de càlcul, i sabran identificar els problemes que poden causar. Inclou el format de les dades."
- "coneixeran l'existència de Software i Data Carpentry com a recurs per a la instrucció en gestió de dades de recerca."
key points:
- "En curar dades de recerca avaluarem el registre, la documentació i el conjunt de dades"
- "La curació dels fitxers de dades consistirà en seleccionar les dades, assegurar-se que es poden compartir, guardar les dades en el format adequat, i assegurar-se que les dades i els fitxers estan organitzats."
- "En organitzar dades en un full de càlcul hem de guardar les dades amb estructura de variables en les columnes, mostres en les files."
-  "En organitzar dades en un full de càlcul hem de guardar les dates fent servir un estàndard o separant Dia, Mes i Any en columnes diferents"
-  "En organitzar dades en un full de càlcul hem de generar documentació per assegurar la reproductibilitat del projecte"
---
# La curació de dades de recerca

> ## Definició de curació de dades
> 
> Quan parlem de curació de dades d'investigació parlem d'"una sèrie d'accions i feines realitzades per part dels curadors en un repositori de dades perquè l'accés a les dades perduri amb el temps i sigui significatiu" (la meva traducció, de [Johnston et al 2016](https://hdl.handle.net/11299/188638)).
> 
{: .callout}

Quan curem dades per a un repositori millorem, revisem i de vegades creem contingut en 3 elements:
* **El registre**: aquestes són les metadades estructurades que formen part del repositori. Aquest tipus d'informació es captura en general per a tots els tipus de contingut en un repositori, incloses dades. Alguns exemples de les metadades incloses en el registre són autor, data, identificador, cita, abstract, llicència, llengua, drets, paraules clau o subject, títol, etc
* **La documentació**: aquests són fitxers que expliquen amb detall la informació continguda en les dades. Aquests també són metadades, però per distingir-los de les metadades de l'registre em referiré a aquests arxius amb la paraula documentació. La majoria de la informació continguda en el registre també està inclosa en la documentació, però la documentació inclou més informació. Per exemple, la documentació pot incloure una llista de les variables presents en les dades, i la seva definició. En alguns repositoris, especialment repositoris dedicats a disciplina específica, que requereixen dipositar documentació amb formats estàndards molt concrets, la documentació i el registre són el mateix.
* **Les dades**: els fitxers amb dades.

Podeu trobar una llista de les diferents activitats que es realitzen quan es curen dades a la pàgina web de el Data Curation Network [https://datacurationnetwork.org/data-curation-activities/](https://datacurationnetwork.org/data-curation-activities/). El Data Curation Network és un projecte que té la missió de facilitar el suport als investigadors per part de repositoris de dades. Els esmentarem en diverses ocasions durant aquestes lliçons perquè han fet molta feina per definir el procés de curació de dades d'investigació en un repositori.

# Curar els fitxers de dades

En aquesta lliçó ens centrarem en la curació dels fitxers de dades, el tercer element de la llista anterior. En la propera lliçó parlarem del registre i la documentació. Curar els fitxers de dades inclou una sèrie d'activitats.

### Selecció de dades

Malauradament, no ho podem guardar i preservar tot. És important treballar amb l'investigador per assegurar-se que les dades escollides per compartir en el repositori són les adequades. Haurem d'avaluar els següents criteris ([Whyte, 2010](https://www.dcc.ac.uk/guidance/how-guides/appraise-select-data)):
* **rellevància per a la missió i objectius del repositori**
* **valor científic o històric de les dades**
* **si les dades són úniques**. Si no ho són, perquè han estat obtingudes d'altres fonts, haurem d'avaluar si les altres fonts ofereixen garanties de preservació. Si aquestes garanties són raonables, podem simplement citar les fonts en comptes de preservar les dades de nou. Si la investigació va posar molta feina en reorganitzar les dades, incorporar-les amb dades de diverses fonts, canviar-les i tractar-les, pot ser convenient preservar-les. En general és aconsellable que no hi hagi diferents versions de les mateixes dades (a no ser que hi hagi un motiu, i en aquest cas les versions han d'estar ben documentades).
* **potencial de redistribució**. Avaluarem la integritat i usabilitat de les dades. Per exemple, si els formats són adequats perquè altres facin servir les dades.
* **replicabilitat**. Si no és possible replicar l'estudi, o fer-ho significaria tenir costos alts, és convenient preservar les dades.
* **reproductibilitat**. Les dades fan possible la reproductibilitat de l'estudi.
* **costos**. els costos estimats per mantenir i preservar el recurs s'han avaluat, i són adequats tenint en compte els possibles beneficis de preservar. Hi ha finançament disponible.
* **documentació**: hi ha documentació que permet que les dades siguin localitzats, es puguin accedir, i siguin reutilitzats.

### Assegurar-se que les dades es poden compartir en un repositori

Si són dades d'un projecte que inclou **dades personals**, ens hem d'assegurar que el comitè d'ètica corresponent ha autoritzat que es comparteixin les dades, i en quina forma. Ens hem d'assegurar que es poden compartir tenint en compte la GDPR.

Si hi ha restriccions (e.g. les dades només poden compartir si no hi ha identificadors), hem de comprovar que s'hagin aplicat. Cal recordar, en aquest punt, que tot i que és un procés important, i el curador pot ser de gran ajuda per identificar aquests problemes, la responsabilitat final és de l'investigador, que és el que ha de conèixer a fons què pot o no fer amb les dades recol·lectades.
 
Si hi ha algun problema de **propietat intel·lectual** que s'hagi de resoldre. Per exemple, si hi ha dades reutilitzades d'altres fonts, hem d'assegurar-nos que l'investigador té permís per redistribuir-les. O si hi ha dades que estan protegides per drets d'autor, i els drets pertanyen a una altra persona, hem de tenir permís per redistribuir-les.

### Format

El potencial de preservació a llarg termini dependrà en gran mesura de el format del fitxer. Un exemple personal: en el nostre repositori ens hem trobats amb fitxers Excel que van ser guardats com a material suplementari de tesis doctorals fa 10-15 anys, i que és impossible obrir, l'ordinador es penja quan ho intentem. No té cap sentit guardar aquests fitxers.
 
Ja hem parlat a la secció dels plans de gestió de dades sobre els formats ideals : formats oberts, que funcionen independentment del sistema operatiu, que no són propietaris, formats que no perdin informació i que no estiguin encriptats o protegits amb paraules clau. 

> ## Recursos
>
> Podeu consultar una llista de formats comuns de fitxers en aquesta pàgina de la Cornell University Library, en la que separen els fitxers segons la probabilitat de preservació [https://guides.library.cornell.edu/ecommons/formats](https://guides.library.cornell.edu/ecommons/formats) Si voleu més informació sobre formats, la Library of Congress té una pàgina web amb informació sobre formats per alguns tipus de fitxers a [https://www.loc.gov/preservation/digital/formats/fdd/descriptions.shtml](https://www.loc.gov/preservation/digital/formats/fdd/descriptions.shtml).
{: .challenge}

Els fitxers de Microsoft Office es mereixen un esment especial, perquè són molt usats. Word, Excel, Access, Power point, etc. no són formats oberts, i són formats propietat d'una empresa, no són formats apropiats per a maximitzar la preservació digital. Sempre que es pugui s'haurien d'evitar. En la majoria d'ocasions es poden convertir a altres formats fàcilment.
* Un fitxer **Word** es pot convertir en un fitxer de text ASCII (en què es perdrà la majoria de el format) o en un pdf (en el qual es preservarà el format).
* Un fitxer **Excel** es pot convertir en un fitxer csv (comma separated values). Haurem de generar un fitxer per full de càlcul. En transformar un Excel en csv podem perdre el format (colors, negreta, etc.), perdrem macros, figures, equacions, etc. No obstant això, els elements que perdem poden ser, precisament, els que fan que la informació en Excel no sigui reproduïble. Són els elements que haurien d'estar documentats en la documentació (el cas de les equacions), o en forma d'altres arxius (el cas de les figures). Parlarem més d'Excel en aquest tema. 
* Una base de dades en **Access**. Les bases de dades relacionals són un tipus de dades que no és trivial preservar. En el millor dels casos, si la base de dades és relativament simple, les dades es poden separar en taules, guardades en csv, i posar la documentació sobre les relacions entre les taules en els fitxers de documentació. Si la base de dades conté moltes taules i relacions complexes separar-les en taules no serà una opció pràctica. Hi ha estàndards de preservació de bases de dades relacionals, SIARD i CHRONOS, que guarden la informació en format XML. Per més informació sobre la preservació de bases de dades relacionals podeu consultar l'informe de [Day Thomson (2016)](http://dx.doi.org/10.7207/twr16-02).

A vegades és molt difícil canviar el format de les dades, i no és raonable demanar a l'investigador que ho canviï. Per exemple, si hi ha codi en un programa que no és obert, com Matlab, traduir-lo a un altre llenguatge és una quantitat de treball enorme. Depèn de l'criteri de l'curador i de les polítiques del repositori decidir si és obligatori canviar el format en aquests casos. Personalment, en el cas del nostre repositori institucional, jo prefereixo que les dades i metadades es preservin al repositori, però els explico el problema perquè puguin canviar els formats des del principi en el seu pròxim projecte.

### Organització i consistència de les dades

És important que les dades estiguin ben organitzades. Persones alienes al projecte (que entenguin la disciplina), han de poder entendre les dades només veient els fitxers i consultant la documentació. Contactar l'autor no ha de ser necessari. Encara que és difícil definir exactament què vol dir que les dades estiguin ben organitzades per a qualsevol tipus de dades, aquesta és una llista dels elements a considerar.

* **Noms de fitxers**: els noms dels fitxers i carpetes han de ser informatius. És preferible que no tinguin caràcters especials (incloent accents i espais en blanc).
* En la documentació ha d'haver una **descripció del contingut de cada un dels fitxers**.
* L'organització de la informació en cada un dels fitxers ha de ser ordenada, o el que anomenem **"tidy data"**. Parlem de ´tidy data´i l'organització de dades en la següent secció.


# Dades ordenades, ´tidy data´ i fulls de càlcul

L'objectiu aquí és parlar de tidy data en general. Però parlar en general és abstracte, i ja hem parlat molt en general en les seccions anterior. Aquí farem servir els fulls de càlcul com a exemple d'un tipus de dades en particular, però els conceptes apresos es poden aplicar a altres tipus de dades. Els fulls de càlcul són un exemple útil per parlar de tidy data, perquè són una eina molt habitual, usada per molts investigadors. 
 
A més de ser un exemple per parlar de tidy data, vull parlar de fulls de càlcul per introduir-vos a les Carpentries. Les Carpentries (The Carpentries [https://carpentries.org/](https://carpentries.org/)) és una organització sense ànim de lucre que té com a objectiu ensenyar eines computacionals relacionades amb dades a investigadors al voltant de el món. Dues de les coses que crec que són útils per al recolzament a la recerca:

* Tenen una sèrie de lliçons obertes per a tothom, amb llicències CC-BY. Les podeu trobar a la seva pàgina web al menú "Teach", dividides en Data Carpentry lessons, Software Carpentry lessons, i Library Carpentry lessons. Algunes d'elles estan traduïdes al castellà. Són lliçons que la comunitat de voluntaris de les Carpentries ha desenvolupat, i s'encarrega de mantenir. Són lliçons que es fan servir sovint, i per això estan a el dia, i molt polides. Molts i moltes bibliotecaris fan servir aquestes lliçons per organitzar tallers que són part dels data services de la biblioteca. Desenvolupar una lliçó porta temps, i moltes vegades no sóm experts en aquests temes, però en sabem prou per donar lliçons introductòries. Per això val molt la pena saber de l'existència d'aquestes lliçons. El contingut d'aquesta secció és una adaptació de la lliçó [Data Organization in Spreadsheets for Ecologists](https://datacarpentry.org/spreadsheet-ecology-lesson/). I si fullegeu les lliçons veureu que el format és el mateix que el d'aquesta lliçó, hem fet servir les seves plantilles per crear aquesta pàgina web. 

* Les Carpentries tenen un programa per formar instructors. Es pot fer en línia, i és gratuït . Entre altres coses, el programa ensenya com aprenen els adults, i estratègies docents que són molt útils per a persones que poden no haver tingut mai formació de docent. 

> ## Incís
> 
> Si voleu, en comptes de llegir aquesta lliçó (reorganitzada, resumida i traduïda), podeu seguir directament la lliçó de les Carpentries: [Data Organization in Spreadsheets for Ecologists](https://datacarpentry.org/spreadsheet-ecology-lesson/). Tingueu en compte que la lliçó original de les Carpentries està pensada per fer-la amb un instructor, no per seguir-la des de la pàgina web. Dit això, jo crec que són molt útils si es segueixen per la pàgina web. 
> 
{: .callout}


### Organitzar dades en un full de càlcul

En aquesta part de la lliçó parlarem de la creació de les dades des del punt de vista de l'investigador creant les dades. Una bona organització de les dades és el fonament de qualsevol projecte d'investigació. Molts investigadors tenen les seves dades en fulls de càlcul, així que és el lloc en el qual comencen moltes investigacions. El que discutirem val per Excel, Open Office, Google Sheets i la majoria de programes d'edició de fulls de dades.

EL primer concepte a tenir en compte és que els ordinadors i les persones entenen la informació de forma molt diferent. Els humans entenem informació desestructurada molt fàcilment, però som lents. Els ordinadors són ràpids, però molt literals. Per poder aprofitar les eines que existeixen per analitzar dades de forma robusta, ràpida i reproductible (per exemple, llenguatges de progamació com R o Python) hem d'assegurar-nos que les dades estan organitzades de la manera adequada per tal que, no només les persones les entenguin, sinó també les màquines. 

Parlarem de
* El format de les taules
* Evitar errors comuns
* Com tractar dades en fulls de càlcul
* Control de qualitat i manipulació
* Exportar dades des d'un programa de full de càlcul

El segon concepte a tenir en compte és que els programes d'edició de fulls de càlcul tenen moltes funcionalitats. Podem entrar dades, organitzar-les, classificar-es, calcular-ne estadístiques, representar dades, etc. No obstant això, aquests programes són molt bons per a algunes d'aquestes tasques, però no tan bones per a altres. En particular, hem d'anar amb molt de compte quan usem fulls de càlcul per generar estadístiques i figures perquè aquests programes funcionen a força de clics i d'arrossegar el cursor, i això fa que sigui molt difícil replicar els passos que s'han seguit per generar, per exemple, una determinada figura. I també és molt fàcil aplicar per error una fórmula a les cel·les adjacents. Hi ha altres programes, com R o SAS, que són més adequats per calcular estadístiques i fer figures: més robustos, menys propensos a errors, i més reproduïbles.

Per què són bons els programes de gestió de fulls de càlcul? Per ordenar i "netejar" dades que després seran usades en altres programes. Quan preparem dades per compartir, precisament volem que les dades estiguin en aquest format net i ordenat.

### Errors habituals i bones pràctiques

Parlem de bones pràctiques i d'errors habituals en fulls de càlcul. 

* Un dels problemes més comuns amb els fulls de càlcul és quan els investigadors els tracten com si fossin llibretes de laboratori. Anotant coses als marges, usant colors i altres tipus de format per guardar el contingut, i confiant que l'usuari de les dades sap el context per entendre les dades. Colors de fons, negretes, marges gruixuts per marcar les separacions de la taula, etc són una bona manera d'ajudar a les persones a visualitzar els continguts d'un full de dades, i es poden usar tranquil·lament per això. Però és molt important **no fer servir formats per guardar informació**. Per exemple, si marquem en vermell els valors que no s'haurien de fer servir en un anàlisi perquè la bàscula no estava calibrada, estem guardant la informació en forma de format. La informació en forma de format es perdrà en guardar les dades en altres fitxers (com per exemple csv), també es perdrà en llegir les dades amb altres programes, i, en general, és difícil utilitzar la informació fins i tot en els fulls de càlcul mateixos. El millor és guardar aquesta informació en forma de columnes amb valors. Per exemple, en el cas de la balança no calibrada afegiríem una columna (e.g. Calibratge) i guardaríem els valors en forma de 0 i 1 o com un "sí" o "no".
* **No anotar els zeros**: de vegades  mesurem alguna cosa i el resultat és zero. Per exemple, hem mirat el número de rodents atrapats en un experiment, i no n'hi havia cap. És important anotar el zero, i no deixar-lo en blanc, perquè un zero i un blanc són valors diferents. Un blanc és quan no hem pogut fer la mesura, o quan la mesura per algun motiu no està disponible. Els programes d'anàlisi de dades normalment interpreten blancs com a valor nul, i no com a zero. 
* **Utilitzar valors nuls problemàtics**. Hi ha diferents raons per les quals podem tenir valors nuls. De vegades val la pena anotar aquestes raons (per exemple, la bàscula utilitzada no estava calibrada). Ja hem dit que no hem de fer servir el zero, perquè 0 és un valor. Quin valor nul hem de fer servir? Alguns valors nuls típics són deixar la cel·la en blanc (és a dir, no posar res), posar un valor en concret, com -999 o 999, posar un abreujament com NA o NULL o NAN, o utilitzar un símbol com + o -. Depenent de el programa amb què volem tractar les dades uns d'aquest valors nuls seran millors que altres. Per exemple, R entén "NA" com a valor nul, Python entén "None", i SQL entén "NULL". La majoria de programes entén un blanc com a valor nul, així que en general un blanc és un bon valor nul. Valors que es poden confondre amb valors reals (com el 999 o el -999) són, en general, una mala idea. El que és essencial és que hi hagi documentació en algun lloc que defineixi el valor blanc que s'ha utilitzat.
* **usar noms de variables que són problemàtics**. Els noms de variables han de ser descriptius, i és aconsellable que no incloguin espais, números, o caràcters especials. El caràcter "_" es pot usar enlloc d'espais. També es poden usar majúscules per fer els noms més fàcils de llegir. alguns exemples
    * Mal exemple: Màxim Temp (° C); Bon exemple: Max_Temp_C
    * Mal exemple: M / F; Bon exemple: sexe
    * Mal exemple: 1a obs; Bon exemple: Primera_Obs


### Estructura de les dades

L'organització que normalment és més efectiva per tenir dades ordenades, o "tidy data", és
* Totes les variables han d'estar en columnes. Les variables són el que estem mesurant. Com a "temperatura" o "pes"
* Cada observació ha d'estar en una fila.
* Només hi ha d'haver una informació en cada parcel·la. No s'han de posar dos tipus d'informació en una cela (e.g. el valor i la unitat)

Vegem un exemple. En la següent figura veiem dues taules. Les dues taules tenen la mateixa informació, però està estructurada de forma diferent. Quina organització és millor?

![La imatge mostra dues taules. La Taula 1 té tres columnes per tres anys consecutius: 2010, 2011, 2012. Té dues fileres, per dos llocs de mostreig, Washington i Oregon. A les cel·les es mostren valors entre 5 i 22. La taula 2 té tres columnes amb els títols "Site" (lloc de mostreig), "Year" (any) i "Abundance" (abundància). Té sis fileres, cada una de les quals amb diferents valors per cada una de les variables. Washington o Oregon per Site, un número entre 2010 i 2012 per Year i un número entre 5 i 22 per Abundance.](../fig/tema3_exemple_estructura-_taules.png)
 
La resposta correcta és que depèn. Si això fossin dades que estem publicant en un article o una presentació, volem que les persones les entenguin el més ràpidament i clarament possible. La Taula 1 serà millor, perquè és més clar que les dades es van prendre en dos llocs, i durant 3 anys diferents. És més fàcil visualitzar, per exemple, que els valors a Washington són més alts que els valors a Oregon. Però la taula 2 és millor per organitzar les dades en un full de càlcul. A la taula 2 veiem clarament que estem prenent dades de tres variables: lloc, any i abundància. Si en un moment determinat volem afegir variables (per exemple prendre notes de la presència de sequera durant aquest any) ens serà molt fàcil fer-ho en la taula 2, i serà complicat a la taula 1. També serà més fàcil fer servir la taula 2 si la recol·lecció de dades es fa a intervals irregulars (per exemple, dues dades en alguns anys, una dada en altres). La taula 2 serà més fàcil d'usar per un programa com R, python, o SAS.

Quan les dades es comparteixen en un repositori haurien de tenir l'estructura de la taula 2, no la de la taula 1.

Un cop ja tenim l'estructura de taula, què és millor? Tenir moltes taules amb poca informació o tenir una gran taula amb molta informació? En general fer servir moltes taules o moltes pestanyes no és recomanable, perquè és més fàcil cometre errors (no col·locar la mateixa informació de la mateixa manera en cada taula) i perquè és molt més difícil llegir les dades amb aquesta estructura amb altres programes. Una gran taula és millor que moltes taules petites. I la majoria de vegades volem combinar la informació de les diferents taules quan analitzem les dades. 

### Estratègies per generar dades reproductibles

Per garantir la reproductibilitat del projecte, i assegurar-nos que no perdem res per accident, és molt important **guardar sempre una còpia de les dades brutes sense modificar**.
 
Ja hem explicat que un problema dels fulls de càlcul és que és difícil reproduir els passos que s'han seguit per obtenir un determinat resultat. Per això és important **prendre notes dels passos que seguim**. Per exemple, podríem obrir una pestanya nova, anomenar-la "readme" o "notes". O podríem crear un fitxer amb Notepad o qualsevol altre programa d'edició de textos, i guardar-lo al costat del nostre full de càlcul. A la figura següent en teniu un exemple.

![La figura mostra un processador de text pla amb el següent text: Notes del processament de les dades a dades_projecte_DM.xlsx  # Passos seguits el 2021-06-14   * Fer una copia del full 2013-bruts, anomenada 2013-nets; còpia del full 2014-bruts a 2014-nets.  * A 2013-nets: crear una columna "Especies". Copiar la informació dels títols dels gràfics en aquesta columna * A 2013-nets: ajuntar les dades de totes les taules separades en una gran taula amb columnes "Data", "Parcella", "Especies", "Sexe", "Pes". * A 2013-nets: separar la columna de data en tres columnes "dia" "mes" "any" fent servir les fórmules =YEAR() =MONTH() =DAY()](../fig/tema3_readme_per_figura.png)

Aquest fitxer de notes segurament no serà el que es acabi sent compartit quan les dades es facin públics en un repositori, però parts d'aquest podrien acabar en la documentació final. I un fitxer d'aquest tipus ens serà molt útil si mesos després no recordem com vam tractar les dades, o si hem de repetir els mateixos passos amb una nova versió de les dades. 

Aquest fitxer de documentació també és un bon lloc on apuntar totes les **metadades de les dades**. Incloure metadades a la taula és un error comú en fulls de càlcul. Notes a les cel·les del costat de la taula, o notes barrejades amb els valors. És important documentar les metadades, però s'ha de fer en un fitxer de documentació, no amb les dades. Totes les taules hauríen de tenir un fitxer de documentació amb un "data dictionary", una llista de totes les variables, amb les seves definicions respectives (encara que sembli obvi, sovint no ho és), i tota la informació que ens cal per ententre-les bé: unitats, rang de valors acceptats, abreviacions, etc. 

Finalment, per garantir que el fitxer de dades perduri amb el temps hauríem de **guardar-lo en un format de text pla**, com ara csv o fitxers delimitats per tabulacions. En general guardar fulls de càlculs en aquest fitxer és fàcil triant l'opció de "Anomena i desa". Aquests formats de text pla normalment es poden obrir fàcilment amb els editors de fulls de càlcul.

### Dates

És molt comú guardar les dates en una columna en un full de dades. Aquests editors tenen un munt de formats pre-determinats per dates, i encara que pugui semblar útil, moltes vegades aquest format pre-determinat causa molts errors. Per exemple:

* Quan fem servir abreviacions en les dades que el programa entén com a dates, i que canvia automàticament.
* Quan entrem dates i no entrem l'any, normalment el programa assumeix que l'any correcte és l'any en què ens trobem, i l'entra automàticament, sense dir-nos-ho. 
* Quan guardem les dades en altres formats, com csv, es guarden les dades tal com les veiem. Si la nostra visualització inclou només dia i mes, i no l'any, la informació d'any la perdrem.
* La manera com estan guardades les dates en els programes de full de càlcul és utilitzant un dia de referència i comptant quants dies han passat des d'aquell dia. Durant molts anys els dies de referència d'Excel a Windows i a Mac era diferent, i els fulls de càlcul que s'havien creat amb un sistema operatiu tenien dates incorrectes (4 anys de diferència) si s'obrien amb un altre sistema operatiu. Aquest problema pot persistir ara si obrim fitxers Excel antics. 

La forma més clara de guardar les dates és tenir una columna per a cada element: any, mes, dia, i hora, minut, segon si són necessaris. D'aquesta manera no hi haurà confusions amb diferents formes habituals de guardar les dates ( fem servir dd/mm/yyyy o mm/dd/yyyy?), o errors deguts a diferents programes i sistemes operatius.

En general, quan es tenen dades que inclouen dates (una situació molt comú) val la pena recordar que hi ha un estàndard per dates, l'ISO 8601 segons el qual el format adequat és yyyy-mm-dd. Les pàgines de la Wikipedia en [castellà](https://es.wikipedia.org/wiki/ISO_8601) o [anglès](https://en.wikipedia.org/wiki/ISO_8601) tenen molta informació sobre com utilitzar l'estàndard.

[![Acudit que explica que hi ha un estàndard ISO, i que segons aquest estàndard les dates s'han de formatejar yyyy-mm-dd, i qualsevol altra opció no és correcta](../fig/tema3_xkcd_iso_8601.png)](https://imgs.xkcd.com/comics/iso_8601.png)
 

# Referències

Day Thomson, S.. (2016). Preserving Transactional Data [DPC Technology Watch Report]. Digital Preservation Coalition. [http://dx.doi.org/10.7207/twr16-02](http://dx.doi.org/10.7207/twr16-02)

Johnston, L.R., Carlson, J, Hudson-Vitale, C., Imker, H., Kozlowski, W., Olendorf, R., Steward, C. (2016) Definitions of data curation activities used by the Data Curation Network. Retrieved from the University of Minnesota Digital Conservancy, [https://hdl.handle.net/11299/188638](https://hdl.handle.net/11299/188638). 

Whyte, A. & Wilson, A. (2010). "How to Appraise and Select Research Data for Curation". DCC How-to Guides. Edinburgh: Digital Curation Centre. Available online: https://www.dcc.ac.uk/guidance/how-guides/appraise-select-data

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
