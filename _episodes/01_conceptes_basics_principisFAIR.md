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


## Referències

Pérez Aliende, M. L., Rasero Merino, V., Ortiz Uceta, E., Lopez Medina, A., de las Moras Hervella, M., González Ballesteros, F., Corrales Correyero, J. (2015) Portal PAGODA: Plan de Gestión de Datos. Fesabid'15, XIV Jornadas Españolas de Documentación. Gijón, 28, 29 y 30 Mayo 2015. [http://www.fesabid.org/gijon2015/www.fesabid.org/sites/default/files/repositorio/actas_fesabid_2015.pdf](http://www.fesabid.org/gijon2015/www.fesabid.org/sites/default/files/repositorio/actas_fesabid_2015.pdf)

# Què és la gestió de dades de recerca?

> ## Definició de gestió de dades de recerca
> 
> Gestionar dades de recerca és un conjunt d'activitats destinades a emmagatzemar, preservar i reutilitzar dades de forma eficient, ètica i segura, durant tot el cicle de vida de les dades.
> 
{: .callout}

Aprofundim en aquesta definició.

## Exemples

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

## El cicle de vida de les dades

Les dades passen per diferents estadis al llarg d'un projecte. És normal i adequat que les dades estiguin gestionades de diferent manera en diferents estadis. Per exemple, durant un projecte normalment l'accés a les dades el tenen només els membres del projecte. En el moment de publicar articles, tesis doctorals, llibres i altres materials es comparteixen les dades referents a la publicació amb el públic. Al final del projecte es comparteixen totes les dades, publicades o no.

Si busqueu per internet trobareu un munt de versions de cicles de vida de les dades. Aquí en teniu una, elaborada pel grup de treball d'Accés Obert de la Red de Bibliotecas Universitarias (REBIUN).

[![El cicle de les dades científiques, elaborat pel grup de treball d'Accés Obert de la Red de Bibliotecas Universitarias (REBIUN). inclou els següents passos en cercle: Dissenyar, planificar, crear recollir i recol·lectar, descriure, processar, arxivar, seleccionar, preservar, accedir i usar, compartir, reutilitzar.](../fig/tema1_contingut1_REBIUN_Infografies_cicdatcie_a2016iCAT.jpg)](https://ddd.uab.cat/record/165475)

Figura: cicle de les dades científiques, elaborat pel grup de treball d'Accés Obert de la Red de Bibliotecas Universitarias (REBIUN)

## Què no és la gestió de dades?

A vegades hi ha certa confusió amb el tema gestió de dades. Aquí teniu una llista de coses que no són sinònims de gestió de dades (tot i que poden ser part de la gestió de dades en alguns casos concrets).
* big data. No només s'han de gestionar grans quantitats de dades. Conjunts de dades petits també s'han de gestionar bé.
* administració de bases de dades
* data science, o ciències informàtiques
* el disseny d'un experiment: com recollir dades, o quines dades s'han de mesurar, o com dissenyar un experiment.

> ## Pregunta amb resposta múltiple
>
> Quins dels següents exemples es poden considerar gestió de dades de recerca? (resposta múltiple)
> A. Un investigador dóna accés a les dades a una col·laboradora
> B. Un investigador decideix posar nom a les seves dades de la següent manera: NomProjecte_Variable_Instrument_LlocMostreig_YYYYMMDD.dat
> C. Una investigadora decideix publicar un article a una revista de prestigi en el seu camp.
> D. Una investigadora decideix depositar els protocols que ha seguit durant el seu experiment en obert en un repositori.
>
> > ## Solució
> >
> > A. CERT Gestionar l'accés a les dades és una part important de la gestió de dades, ja sigui amb membres de l'equip, col·laboradors externs, o el públic.
> > B. CERT Mantenir les dades ordenades és part de la gestió de dades. 
> > C. FALS Publicar un article és publicar la interpretació de les dades, no les dades. Això no és, en principi, gestionar les dades.
> > D. CERT Això es pot considerar gestionar dades perquè està depositant metadades, informació sobre com s'han generat les dades.
> >
> {: .solution}
{: .challenge}

## Referències

REBIUN (2016) Datos de investigación y acceso abierto. https://ddd.uab.cat/record/165475.  [Consulta: 2 juliol 2021].

# Reproductibilitat

## Context

Per parlar de reproductibilitat començarem introduint breument la feina de Brian Nosek, perquè és un investigador que ha parlat molt de temes de reproductibilitat. Però n'hi ha molts d'altres, evidentment. 

En Brian Nosek va coordinar un estudi en el qual ell, més 269 col·laboradors, van intentar reproduir les troballes de 98 articles en el camp de la psicologia ([Open Science Collaboration, 2015](https://doi.org/10.1126/science.aac4716)). Van escollir articles publicats en revistes de prestigi, i van comptar amb la col·laboració de molts dels autors dels estudis originals. El resultat va ser que tan sols van poder replicar 39 dels 98 estudis. Altres estudis similars han estat publicats en altres disciplines, amb resultats similars ([Begley, 2013](https://doi.org/10.14694/EdBook_AM.2013.33.466), [Camerer 2016](https://doi.org/10.1126/science.aaf0918)). Aquest tipus d'estudis van portar a la comunitat científica a parlar de l'existència d'una crisi de reproductibilitat. La idea és que de la manera com es fa ciència avui en dia, és molt difícil reproduir els resultats d'un estudi.

Encara que no tota la comunitat científica està d'acord amb l'existència d'aquesta crisi, el concepte de reproductibilitat és important per a la comunitat científica ([Fanelli, 2018](https://doi.org/10.1371/journal.pone.0005738)). La següent figura, provinent de l'article de [Fanelli (2018)](https://doi.org/10.1371/journal.pone.0005738) il·lustra el nombre d'articles publicats des de 1975 que parlen d'una crisi de reproductibilitat. En vermell, si estan d'acord amb l'existència d'una crisi, en blau si qüestionen l'existència d'una crisi.



## Referències

Begley, C. G. (2013). An Unappreciated Challenge to Oncology Drug Discovery: Pitfalls in Preclinical Research. American Society of Clinical Oncology Educational Book, 33, 466–468. [https://doi.org/10.14694/EdBook_AM.2013.33.466](https://doi.org/10.14694/EdBook_AM.2013.33.466)

Camerer, C. F., Dreber, A., Forsell, E., Ho, T.-H., Huber, J., Johannesson, M., Kirchler, M., Almenberg, J., Altmejd, A., Chan, T., Heikensten, E., Holzmeister, F., Imai, T., Isaksson, S., Nave, G., Pfeiffer, T., Razen, M., & Wu, H. (2016). Evaluating replicability of laboratory experiments in economics. Science, 351(6280), 1433–1436. [https://doi.org/10.1126/science.aaf0918](https://doi.org/10.1126/science.aaf0918)

Fanelli, D. (2009). How Many Scientists Fabricate and Falsify Research? A Systematic Review and Meta-Analysis of Survey Data. PLoS ONE, 4(5), e5738. [https://doi.org/10.1371/journal.pone.0005738](https://doi.org/10.1371/journal.pone.0005738)

Open Science Collaboration. (2015). Estimating the reproducibility of psychological science. Science, 349(6251), aac4716–aac4716. [https://doi.org/10.1126/science.aac4716](https://doi.org/10.1126/science.aac4716)


# La gestió de dades i dades obertes

# Els principis FAIR

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
