---
title: Conceptes bàsics i principis FAIR
teaching: 30
exercises: 0
questions:
- "Què són les dades de recerca?"
- "Què vol dir reproductibilitat?"
- "En què consisteix la gestió de dades de recerca?"
- "Què són els principis FAIR?"
objectives:
- "Saber definir ´Dades de recerca´."
- "Saber definir ´Gestió de dades de recerca´ i nombrar accions que es puguin considerar gestió de dades de recerca."
- "Definir el concepte de reproductibilitat i argumentar per què és important."
- "Llistar motius perls quals publicar dades en obert és positiu"
- "Nombrar els quatre elements dels principis FAIR"
keypoints:
- "Les dades de recerca poden tenir moltes formes diferents."
- "Un dels objectius de la gestió de dades de recerca és que la ciència sigui més reproductible."
- "Posar dades en obert és més que simplement fer que siguin gratuïtes. Han de ser accessibles, i tenir llicències"
- "Els principis FAIR estan fets amb la idea de maximitzar la reusabilitat de les dades, per persones i per màquines"
---

Aquesta lliçó conté cinc parts:
* Què són les dades de recerca?
* Què és la gestió de les dades de recerca?
* Reproductibilitat
* La gestió de dades i dades obertes
* Els principis FAIR

# Què són les dades de recerca?

 Durant aquest curs parlarem de dades d'investigació. Podeu trobar moltes definicions de dades de recerca, i alguns organismes fan servir definicions més àmplies que altres. Una possible definició:

> ## Definició de dades de recerca
> 
> Les dades d'investigació constitueixen aquells materials generats o recol·lectats durant el transcurs d'una investigació. En general, les dades d'una investigació són les que un investigador necessitaria per validar els resultats publicats de la seva recerca. ([Pérez Aliende et al 2015](http://www.fesabid.org/gijon2015/www.fesabid.org/sites/default/files/repositorio/actas_fesabid_2015.pdf))
> 
{: .callout}


Alguns elements de la definició que hem de destacar:

* Les dades són "fets objectius" en els quals es basen els resultats de la investigació. Les dades no són el mateix que la interpretació de les dades. Els articles científics poden incloure visualitzacions de les dades, i interpretacions del que les dades volen dir, però no són les dades.
* Segons la disciplina, les dades de recerca poden tenir moltes formes diferents. Les dades d'investigació no són necessàriament xifres. Exemples de materials que es poden considerar dades de recerca
  - un full de càlcul amb mesures obtingudes de sensors en el camp
  - un seguit d'entrevistes, gravades en vídeo
  - mapes i dades geoespacials
  - objectes que s'analitzen. Per exemple, una mostra de gel per a un estudi sobre canvi climàtic.
  - models, incloent el codi del model, els arxius d'entrada, i els resultats.
  - una sèrie de textos històrics.

Les dades per si soles normalment no són útils. Necessitem informació per interpretar-les. Quan parlem de gestió de dades de recerca parlem de gestionar les dades i també les metadades que ens permeten entendre i interpretar les dades adequadament. La documentació de les dades també es pot considerar dades d'investigació. Exemples de metadades de dades d'investigació:
* protocols experimentals
* codi que s'ha utilitzat per analitzar i tractar les dades
* context de la informació (on, quan, com, qui ha generat les dades)
* notes de laboratori, físiques o digitals
* arxiu de configuració d'un instrument
* fitxers anotant la procedència de les dades (en el cas de dades reutilitzades)
* diccionaris de dades amb les definicions, unitats etc. de les variables mesurades
* questionaris 

Per exemple: una dada seria, la temperatura és 28. És útil aquesta dada? Em podeu interpretar aquesta dada? És fred? O és calent? Tot això no ho podeu fer si no teniu les metadades. Les unitats, on s'ha mesurat, en quin moment s'ha mesurat. Segons el tipus de recerca necessitarem saber també amb quin instrument s'ha mesurat, quin és el marge d'error, etc. 


> ## Vertader o fals?
>
> Les dades de recerca són sempre xifres, normalment estructurades en forma de taula. Cert o fals?
>
> > ## Solució
> >
> > Fals! Les dades de recerca poden ser de molts tipus, no només xifres. Depenent del camp d'estudi dades de recerca poden ser textos, entrevistes, fotografies, imatges, audio, mapes, qüestionaris, etc. Si considerem les metadades part de les dades, aleshores els tipus de dades s'amplien encara més.
> >
> {: .solution}
{: .challenge}



# Què és la gestió de dades de recerca?

> ## Definició de gestió de dades de recerca
> 
> Gestionar dades de recerca és un conjunt d'activitats destinades a emmagatzemar, preservar i reutilitzar dades de forma eficient, ètica i segura, durant tot el cicle de vida de les dades.
> 
{: .callout}

Aprofundim en aquesta definició.

### Exemples

Les accions implicades en la gestió de dades poden ser molt diverses. Aquí en teniu uns exemples:
* escriure un pla de gestió de dades
* desar les dades amb noms de fitxers estructurats de tal manera que ens permetin saber què hi ha a cada fitxer fàcilment.
* fer servir un programa de control de versions per gestiona les diferents versions de les dades o del programari creat per tractar les dades.
* dissenyar un sistema que ens permeti mantenir tres còpies de seguretat de totes les dades del projecte
* documentar els mètodes de col·lecció i anàlisi de les dades
* tenir un sistema que ens permeti donar accés a les dades només a aquelles persones que n'hagin de tenir accés.
* dissenyar un projecte de recerca de manera que es protegeixi els participants i se'n garanteixi un tractament just, digne i respectuós.
* organitzar les dades de manera que es puguin entendre clarament, i reutilitzar
* compartir dades
* posar les dades en un repositori al final del projecte per garantir-ne la conservació i per compartir-les fàcilment

### El cicle de vida de les dades

Les dades passen per diferents estadis al llarg d'un projecte. És normal i adequat que les dades estiguin gestionades de diferent manera en diferents estadis. Per exemple, durant un projecte normalment l'accés a les dades el tenen només els membres del projecte. En el moment de publicar articles, tesis doctorals, llibres i altres materials es comparteixen les dades referents a la publicació amb el públic. Al final del projecte es comparteixen totes les dades, publicades o no.

Si busqueu per internet trobareu un munt de versions de cicles de vida de les dades. Aquí en teniu una, elaborada pel grup de treball d'Accés Obert de la Red de Bibliotecas Universitarias (REBIUN).

[![El cicle de les dades científiques, elaborat pel grup de treball d'Accés Obert de la Red de Bibliotecas Universitarias (REBIUN). inclou els següents passos en cercle: Dissenyar, planificar, crear recollir i recol·lectar, descriure, processar, arxivar, seleccionar, preservar, accedir i usar, compartir, reutilitzar.](../fig/tema1_contingut1_REBIUN_Infografies_cicdatcie_a2016iCAT.jpg)](https://ddd.uab.cat/record/165475)

Figura: cicle de les dades científiques, elaborat pel grup de treball d'Accés Obert de la Red de Bibliotecas Universitarias (REBIUN)



### Què no és la gestió de dades?

A vegades hi ha certa confusió amb el tema gestió de dades. Aquí teniu una llista de coses que no són sinònims de gestió de dades (tot i que poden ser part de la gestió de dades en alguns casos concrets).
* big data. No només s'han de gestionar grans quantitats de dades. Conjunts de dades petits també s'han de gestionar bé.
* administració de bases de dades
* data science, o ciències informàtiques
* el disseny d'un experiment: com recollir dades, o quines dades s'han de mesurar, o com dissenyar un experiment.

> ## Pregunta amb resposta múltiple
>
> Quins dels següents exemples es poden considerar gestió de dades de recerca? (resposta múltiple)
> - A. Un investigador dóna accés a les dades a una col·laboradora
> - B. Un investigador decideix posar nom a les seves dades de la següent manera: NomProjecte_Variable_Instrument_LlocMostreig_YYYYMMDD.dat
> - C. Una investigadora decideix publicar un article a una revista de prestigi en el seu camp.
> - D. Una investigadora decideix depositar els protocols que ha seguit durant el seu experiment en obert en un repositori.
>
> > ## Solució
> >
> > - A. CERT Gestionar l'accés a les dades és una part important de la gestió de dades, ja sigui amb membres de l'equip, col·laboradors externs, o el públic.
> > - B. CERT Mantenir les dades ordenades és part de la gestió de dades. 
> > - C. FALS Publicar un article és publicar la interpretació de les dades, no les dades. Això no és, en principi, gestionar les dades.
> > - D. CERT Això es pot considerar gestionar dades perquè està depositant metadades, informació sobre com s'han generat les dades.
> >
> {: .solution}
{: .challenge}


# Reproductibilitat

### Context

Per parlar de reproductibilitat començarem introduint breument la feina de Brian Nosek, perquè és un investigador que ha parlat molt de temes de reproductibilitat. Però n'hi ha molts d'altres, evidentment. 

En Brian Nosek va coordinar un estudi en el qual ell, més 269 col·laboradors, van intentar reproduir les troballes de 98 articles en el camp de la psicologia ([Open Science Collaboration, 2015](https://doi.org/10.1126/science.aac4716)). Van escollir articles publicats en revistes de prestigi, i van comptar amb la col·laboració de molts dels autors dels estudis originals. El resultat va ser que tan sols van poder replicar 39 dels 98 estudis. Altres estudis similars han estat publicats en altres disciplines, amb resultats similars ([Begley, 2013](https://doi.org/10.14694/EdBook_AM.2013.33.466), [Camerer 2016](https://doi.org/10.1126/science.aaf0918)). Aquest tipus d'estudis van portar a la comunitat científica a parlar de l'existència d'una crisi de reproductibilitat. La idea és que de la manera com es fa ciència avui en dia, és molt difícil reproduir els resultats d'un estudi.

Encara que no tota la comunitat científica està d'acord amb l'existència d'aquesta crisi, el concepte de reproductibilitat és important per a la comunitat científica ([Fanelli, 2018](https://doi.org/10.1371/journal.pone.0005738)). La següent figura, provinent de l'article de [Fanelli (2018)](https://doi.org/10.1371/journal.pone.0005738) il·lustra el nombre d'articles publicats des de 1975 que parlen d'una crisi de reproductibilitat. En vermell, si estan d'acord amb l'existència d'una crisi, en blau si qüestionen l'existència d'una crisi.

![Gràfic de Fanelli (2018) que mostra el número d'articles publicats des de 1975 fins al 2017 amb les paraules "reproducibility crisis", "scientific crisis", "science in crisis", "crisis in science", "replication crisis", "replicability crisis". Entre el 1975 i el 2011 n'hi ha 5 o menys cada any, i només quatre en parlen recolzant la idea de la crisi. Del 2012 al 2016 el número d'articles creix de 5 a més de 35 per any, i la gran majoria recolzen la idea que hi ha una crisi. ELs últims tres anys inclouen articles que qüestionen que hi hagi una crisi.](../fig/tema1_contingut1_figure1_reproducibility_fanelli2018.png)
Figura: Gràfic de [Fanelli (2018)](https://doi.org/10.1371/journal.pone.0005738) mostrant l'evolució del concepte de reproductibilitat.

> ## Definició de reproductibilitat i replicabilitat
> 
> Si feu una mica de recerca, veureu que hi ha moltes definicions de reproductibilitat, i que sovint s'entrellacen amb el concepte de replicabilitat. Aquestes són les definicions del [National Academies of Sciences, Engineering, and Medicine, (2019)](https://doi.org/10.17226/25303). (La traducció és meva).
> 
> **Reproductibilitat** és l'obtenció de resultats consistents usant les mateixes dades d'origen, els mateixos passos computacionals, mètodes i codi, les mateixes condicions d'anàlisi.
> 
> **Replicabilitat** és l'obtenció de resultats consistents a través d'estudis que tenen com a objectiu el resoldre les mateixes preguntes científiques, on cada estudi ha obtingut les seves pròpies dades. 
> 
{: .callout}

### Per què hi ha una crisi de reproductibilitat?

Hi ha moltes raons per les quals és difícil reproduir estudis científics. A vegades és perquè els científics són humans, i cometen errors. Vegeu, per exemple, el cas de l'estudiant que va descobrir un error en un article de gran prestigi, descrit en aquest article d'[Alexander R. (2013)](https://www.bbc.com/news/magazine-22223190). Altres vegades és perquè s'ha comès frau i les dades s'han fabricat, com en el cas del psicòleg Diederik Stapel, que va inventar les dades de més de 50 articles, vegeu un dels articles sobre el tema a [Callaway, 2011](https://doi.org/10.1038/479015a). En general, però, la preocupació ve del fet que la manca de reproducibilitat és deguda a un biaix estructural del sistema. Aquí en teniu uns quants elements:

* Hi ha molta pressió per publicar molt, i en determinades revistes. Això fa que no es publiquin estudis vàlids però "avorrits", o estudis que tenen resultats negatius. Els resultats es prioritzen, enlloc de prioritzar la metodologia.
* Aquesta pressió per publicar també provoca que els investigadors caiguin en la temptació (conscient o no) de fer més i més anàlisis fins a trobar el resultat desitjat.
* La unitat bàsica de transmetre resultats és l'article, que sovint és un format rígid que no dóna lloc a compartir informació imprescindible per reproduir els estudis. A vegades pensem que una bona secció de mètodes en un article ja és suficient per garantir la reproductibilitat d'un projecte d'investigació, però no és cert. Per realment reproduir un estudi es necessita molt més: informació sobre els instruments i la seva configuració, els protocols seguits, el codi usat per a tractar les dades, els tests estadístics usat, els valors llindar, el programari i maquinari usat, ... i per descomptat, les dades.

La comunitat científica ha començat moltes estratègies per millorar la reproductibilitat i replicabilitat dels estudis científics. En el capítol 6 de [National Academies of Sciences, Engineering, and Medicine (2019)](https://doi.org/10.17226/25303) podeu trobar una explicació sobre moltes d'elles. La bona gestió de les dades durant la investigació i després de la investigació és una part fonamental per a generar investigacions reproduïbles. Un element molt important per assegurar la reproductibilitat de la ciència són les dades obertes. En parlem a la secció següent.



# La gestió de dades i dades obertes

### Dades obertes

Posar les dades en obert és una manera d'assegurar-se que altres investigadors podran (1) comprovar que no s'han comès errors en el tractament de les dades en una publicació (2) reproduir els resultats de la investigació i (3) re-utilitzar les dades per a altres investigacions. Compartir dades amb el públic té també altres avantatges

* Publicar dades en obert és positiu per als investigadors. Per exemple, hi ha estudis que demostren que els articles que tenen dades en oberts se citen més que els que no ([Piwowar i Vision, 2013](https://doi.org/10.7287/peerj.preprints.1v1))
* Perquè és més just. Sobretot si tenim en compte que gran part dels fons per a investigació provenen de diners públics.
* Quan les dades es fan públics en un repositori de qualitat també assegurem la seva preservació a llarg termini.
* Compartir les dades de recerca en general fa que la ciència avanci més ràpid. En algunes ocasions compartir les dades fa possible investigació que seria impossible d'altres formes. Per exemple, vegeu aquest [article de Nature (2016)](https://doi.org/10.1038/534435b) sobre com compartir dades pot ajudar en la investigació de malalties rares.


### Com han de ser les dades obertes?

> ## Definició de dades obertes
> Dades d'investigació obertes són (segons la [Comissió Europea](https://ec.europa.eu/info/research-and-innovation/strategy/strategy-2020-2024/our-digital-future/open-science/open-science-monitor/facts-and-figures-open-research-data_en), la meva traducció), "dades que sustenten els resultats de la investigació científica sense restriccions d'accés, de manera que qualsevol pot accedir-hi".
> 
> 
{: .callout}

És important el concepte que posar les dades en obert no és només fer que les dades siguin gratuïtes. Les dades obertes han de tenir els permisos i llicències necessàries per assegurar-se que les dades es puguin reutilitzar. Aquestes cinc R de les dades obertes, resumeixen el concepte ([les cinc R de Wiley](https://opencontent.org/blog/archives/3221), la meva traducció):

* **retenir**: que puguis descarregar les dades i guardar-ne una còpia
* **revisar**: editar, adaptar i modificar la teva còpia
* **modificar**: barrejar, transformar o crear a partir de la còpia original.
* **reutilitzar**: fer servir l'original o derivats de forma pública
* **redistribuir**: compartir còpies de l'original o els derivats.

I a més de tenir les llicències necessàries, les dades obertes han de ser dades de qualitat. Tenir un conjunt de dades en obert que no es pot entendre no serveix per a res. En un moment parlarem dels principis FAIR, uns principis creats per maximitzar la reutilització de les dades que incideixen molt en quines qualitats han de tenir les dades. Dades FAIR i dades obertes no són el mateix, tot i que no són exclusivament per dades obertes, són una bona guia per saber com publicar dades obertes de qualitat, de manera que en maximitzem la reutilització. 

### Tot ha de ser obert?

Evidentment, no totes les dades es poden publicar en obert. Hi ha molt bones raons per mantenir segons quines dades protegides. La consigna  que les dades han de ser "tan obertes com sigui possible, tan tancades com sigui necessari" s'utilitza sovint, la veureu per exemple en les guies de la Comissió Europea per redactar plans de gestió de dades.

El cas més comú en què les dades no s'haurien de publicar en obert és quan hem de protegir la privacitat dels subjectes de recerca, perquè els nostres subjectes són persones de qui estem recol·lectant dades personals. A vegades, tot i que no treballem amb persones, és necessari també tenir les dades tancades. Per exemple, un estudi d'espècies en extinció en què hi ha informació de la localització d'aquestes espècies no s'hauria de publicar en obert per evitar que caçadors furtius utilitzin aquesta informació. O les dades d'un estudi sobre la prevalença d'una determinada malaltia en bestiar no s'hauria de publicar en obert per protegir els pagesos que estan gestionant la malaltia correctament a les seves granges.

> ## Vertader o fals?
>
> Per tal de fer que la recerca sigui reproduible totes les dades utilitzades en un projecte de recerca s’haurien de posar en obert, sense excepció. Cert o fals?
>
> > ## Solució
> >
> > Fals! Hi ha moltes excepcions que poden ser necessàries. Per exemple, quan la recerca és sobre subjectes humans per protegir la seva privacitat. 
> >
> {: .solution}
{: .challenge}

# Els principis FAIR

Com ja hem comentat a l'apartat anterior, dades accessibles amb llicències clares són dades obertes, però dades obertes no són necessàriament útils. Per assegurar-nos que siguin útils necessitem que les dades siguin de qualitat, que tinguin documentació, que siguin permanents i tinguin identificadors, que en sapiguem la procedència, que estiguin generades de forma ètica ... Tot això us resultarà familiar, és el que les biblioteques fan regularment amb altres tipus de continguts, i també s'ha de fer amb les dades de recerca.

Els principis FAIR ([Wilkinson et al al 2016](https://doi.org/10.1038/sdata.2016.18)) es van desenvolupar amb l'objectiu d'aclarir aquestes qüestions. Com hem de compartir les dades de recerca perquè siguin útils i reutilitzables? Els principis FAIR indiquen que les dades han de ser localitzables, accessibles, interoperables, i reutilitzables.

A continuació teniu els principis FAIR (traducció de [Melero et al, 2018(http://hdl.handle.net/10609/98347))

**Localitzable** (findable):
* F1. Assignar un identificador únic i persistent a les dades i metadades.
* F2. Descriure les dades amb metadades enriquides (és a dir, afegint-hi declaracions semàntiques, anotacions, etc., sobre les dades que descriuen, que milloren la qualitat de les metadades). 
* F3. Registrar i indexar dades i metadades en un sistema (repositori, servei, etc.) que disposi de motor de cerca. 
* F4. Incloure un element de metadades específic per a l’identificador persistent de les dades.


**Accessible** (accessible):
* A1. Utilitzar protocols estandarditzats per poder recuperar dades i metadades mitjançant l’identificador.
* A1.1 Els protocols han de ser oberts, gratuïts i universalment aplicables.
* A1.2 Els protocols han de permetre, a més, un procediment d’autenticació i autorització, si cal.
* A2. Garantir la disponibilitat d’accessibilitat de les metadades, encara que les dades ja no estiguin disponibles. Recomanacions de MareData 11


**Interoperable** (interoperable):
* I1. Utilitzar llenguatges formals (accessibles, compartits i normalitzats) per representar dades i metadades.
* I2. Descriure les dades i metadades amb vocabularis (esquemes, ontologies, etc.) que també segueixin els principis FAIR.
* I3. Incloure referències encreuades i enllaços entre dades i metadades.


**Reutilitzable** (reusable):
* R1. Assegurar-se que les dades i metadades utilitzades tenen una varietat d’elements o atributs precisos i rellevants.
* R1.1. Publicar dades i metadades amb una llicència de reutilització clara i accessible.
* R1.2. Utilitzar criteris de provenance (creació, atribució i historial de versions) per associar metadades a les dades durant el seu cicle de vida.
* R1.3. Assegurar-se que els estàndards de dades i metadades utilitzats compleixen els estàndards comuns de l’àrea de coneixement a què es refereixen les dades.

### Elements importants dels principis FAIR

Hi ha unes quantes característiques dels principis FAIR que crec que és important destacar.

Dades FAIR i dades obertes no són el mateix. Hi ha dades obertes que no compleixen els principis FAIR, i hi ha dades que compleixen aquests principis que no es poden posar en obert. Si voleu llegir més sobre el tema de dades que no es poden posar en obert i com gestionar-les a la bibliografia teniu uns quants articles que en parlen:

* sobre què vol dir accessibilitat en els principis FAIR quan tenim subjectes humans ([Landi et al 2020](https://doi.org/10.1162/dint_a_00027))
* sobre com compartir dades d'individus èticament ([Bull et al 2015](https://doi.org/10.1177/1556264615594767)). Aquest article és d'abans dels principis FAIR, així que no parla dels principis FAIR.

**Els principis FAIR són una guia, són principis aspiracionals**. Aquests principis no es van fer amb la idea de crear un sistema mètric que ens digui si un conjunt de dades és bo (FAIR) o no (no FAIR). Al contrari, els principis pretenen ser una manera de millorar, i de guiar el desenvolupament de pràctiques, polítiques, recursos, etc. per maximitzar la reutilització de les dades de recerca ([Jacobsen et al, 2020](https://doi.org/10.1162/dint_r_00024)).

Com que els principis FAIR són aspiracionals i generals, també són **imprecisos i vagues**. Això vol dir que s'han d'interpretar, i que **cada comunitat d'investigadors ha de fer la feina de decidir què vol dir FAIR per les seves dades**. Si busqueu a la literatura trobareu un munt d'articles publicats sobre aquest tema en diferents disciplines.

> ## Vertader o fals?
>
> En general és recomanable aplicar els principis FAIR també a les metadades i al pla de gestió de dades. Cert o fals?
>
> > ## Solució
> >
> > Cert! Els principis FAIR són rellevants per a molt més que tan sols les dades mateixes. Es poden aplicar a la documentació de les dades i metadades, als plans de gestió de dades, i en general als objectes de recerca. És una de les recomanacions del document de Maredata. "Les metadades que descriuen les dades, així com el propi pla de gestió de les dades, en què es documenta tot el procés de gestió que seguirà el projecte per a les dades, també han de ser localitzables, accessibles, interoperables i reutilitzables en si mateixes."
> >
> {: .solution}
{: .challenge}

> ## Lectura recomanada
>
> El desembre del 2018 el projecte Maredata va publicar un document amb recomanacions per a la gestió de dades de recerca. El document va dirigit a investigadores i investigadors, però crec que és un document útil per entendre l'aplicabilitat dels principis FAIR, i el que comporta la gestió de dades de recerca per a una persona fent recerca. Si voleu aprendre més sobre els principis FAIR llegiu el document que podeu trobar a [http://hdl.handle.net/10609/98347](http://hdl.handle.net/10609/98347)
{: .challenge}

# Referències


Begley, C. G. (2013). An Unappreciated Challenge to Oncology Drug Discovery: Pitfalls in Preclinical Research. American Society of Clinical Oncology Educational Book, 33, 466–468. [https://doi.org/10.14694/EdBook_AM.2013.33.466](https://doi.org/10.14694/EdBook_AM.2013.33.466)

Bull, S., Roberts, N., & Parker, M. (2015). Views of Ethical Best Practices in Sharing Individual-Level Data From Medical and Public Health Research: A Systematic Scoping Review. Journal of Empirical Research on Human Research Ethics, 10(3), 225–238. [https://doi.org/10.1177/1556264615594767](https://doi.org/10.1177/1556264615594767)

Callaway, E. (2011). Report finds massive fraud at Dutch universities. Nature, 479(7371), 15–15. [https://doi.org/10.1038/479015a](https://doi.org/10.1038/479015a)

Camerer, C. F., Dreber, A., Forsell, E., Ho, T.-H., Huber, J., Johannesson, M., Kirchler, M., Almenberg, J., Altmejd, A., Chan, T., Heikensten, E., Holzmeister, F., Imai, T., Isaksson, S., Nave, G., Pfeiffer, T., Razen, M., & Wu, H. (2016). Evaluating replicability of laboratory experiments in economics. Science, 351(6280), 1433–1436. [https://doi.org/10.1126/science.aaf0918](https://doi.org/10.1126/science.aaf0918)

Facts and Figures for open research data. (n.d.). [Text]. European Commission - European Commission. Retrieved July 2, 2021, from [https://ec.europa.eu/info/research-and-innovation/strategy/strategy-2020-2024/our-digital-future/open-science/open-science-monitor/facts-and-figures-open-research-data_en](https://ec.europa.eu/info/research-and-innovation/strategy/strategy-2020-2024/our-digital-future/open-science/open-science-monitor/facts-and-figures-open-research-data_en)


Fanelli, D. (2009). How Many Scientists Fabricate and Falsify Research? A Systematic Review and Meta-Analysis of Survey Data. PLoS ONE, 4(5), e5738. [https://doi.org/10.1371/journal.pone.0005738](https://doi.org/10.1371/journal.pone.0005738)

Jacobsen, A., de Miranda Azevedo, R., Juty, N., Batista, D., Coles, S., Cornet, R., Courtot, M., Crosas, M., Dumontier, M., Evelo, C. T., Goble, C., Guizzardi, G., Hansen, K. K., Hasnain, A., Hettne, K., Heringa, J., Hooft, R. W. W., Imming, M., Jeffery, K. G., … Schultes, E. (2020). FAIR Principles: Interpretations and Implementation Considerations. Data Intelligence, 2(1–2), 10–29. [https://doi.org/10.1162/dint_r_00024](https://doi.org/10.1162/dint_r_00024)

Landi, A., Thompson, M., Giannuzzi, V., Bonifazi, F., Labastida, I., da Silva Santos, L. O. B., & Roos, M. (2020). The “A” of FAIR – As Open as Possible, as Closed as Necessary. Data Intelligence, 2(1–2), 47–55. [https://doi.org/10.1162/dint_a_00027](https://doi.org/10.1162/dint_a_00027)

Melero Melero, R., Abadal Falgueras, E., Aleixandre Garrido, R., Canals Parera, A., Ferrer, A., Hernández, A., López Borrull, A., Mazón López, J. N., Méndez Rodríguez, E., Ollé Castellà, C., & Peset, F. (2018). Recomanacions per a la gestió de dades de recerca dirigides a investigadors. 	[http://hdl.handle.net/10609/98347](http://hdl.handle.net/10609/98347)

National Academies of Sciences, Engineering, and Medicine (2019). Reproducibility and Replicability in Science. Washington, DC: The National Academies Press. [https://doi.org/10.17226/25303](https://doi.org/10.17226/25303).

Open Science Collaboration. (2015). Estimating the reproducibility of psychological science. Science, 349(6251), aac4716–aac4716. [https://doi.org/10.1126/science.aac4716](https://doi.org/10.1126/science.aac4716)

Pérez Aliende, M. L., Rasero Merino, V., Ortiz Uceta, E., Lopez Medina, A., de las Moras Hervella, M., González Ballesteros, F., Corrales Correyero, J. (2015) Portal PAGODA: Plan de Gestión de Datos. Fesabid'15, XIV Jornadas Españolas de Documentación. Gijón, 28, 29 y 30 Mayo 2015. [http://www.fesabid.org/gijon2015/www.fesabid.org/sites/default/files/repositorio/actas_fesabid_2015.pdf](http://www.fesabid.org/gijon2015/www.fesabid.org/sites/default/files/repositorio/actas_fesabid_2015.pdf)

Piwowar, H., & Vision, T. J. (2013). Data reuse and the open data citation advantage [Preprint]. PeerJ PrePrints. https://doi.org/10.7287/peerj.preprints.1v1

REBIUN (2016) Datos de investigación y acceso abierto. [https://ddd.uab.cat/record/165475](https://ddd.uab.cat/record/165475).  [Consulta: 2 juliol 2021].

Reinhart, Rogoff... and Herndon: The student who caught out the profs. (2013, April 19). BBC News. [https://www.bbc.com/news/magazine-22223190](https://www.bbc.com/news/magazine-22223190)

The ups and downs of data sharing in science. (2016). Nature, 534(7608), 435–436. [https://doi.org/10.1038/534435b](https://doi.org/10.1038/534435b)

Wiley (2014) The Access Compromise and the 5th R. Improving learning. [Blog post] [https://opencontent.org/blog/archives/3221](https://opencontent.org/blog/archives/3221)

Wilkinson, M. D., Dumontier, M., Aalbersberg, Ij. J., Appleton, G., Axton, M., Baak, A., Blomberg, N., Boiten, J.-W., da Silva Santos, L. B., Bourne, P. E., Bouwman, J., Brookes, A. J., Clark, T., Crosas, M., Dillo, I., Dumon, O., Edmunds, S., Evelo, C. T., Finkers, R., … Mons, B. (2016). The FAIR Guiding Principles for scientific data management and stewardship. Scientific Data, 3(1), 160018. [https://doi.org/10.1038/sdata.2016.18](https://doi.org/10.1038/sdata.2016.18)
