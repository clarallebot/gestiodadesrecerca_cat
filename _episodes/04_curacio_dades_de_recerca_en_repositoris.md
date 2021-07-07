---
title: Curació de dades de recerca en repositoris
teaching: 30
exercises: 0
questions:
- "Quins són els elements necessaris d'un pla de gestió de dades?"
- "Quina informació hem d'incloure en cada element?"
- "Quins són els errors més comuns en escriure un pla de gestió de dades?"
objectives:
- "Saber definir ´Dades de recerca´."
- "Saber definir ´Gestió de dades de recerca´."
- "Entendre el concepte de reproductibilitat."
- "Tenir una visió general de dades obertes en la gestió de dades de recerca"
key points:
- "Les dades de recerca poden tenir moltes formes diferents."
- "Un dels objectius de la gestió de dades de recerca és que la ciència sigui més reproductible."
---
# Curar dades en un repositori

Aquest tema està enfocat a la curació de dades per a un repositori institucional que accepta documents rellevants per a la institució (per exemple tesis, informes, materials docents, etc.) i que també accepta dades de recerca dels investigadors de la universitat. Els conceptes dels que parlarem es poden aplicar fàcilment a altres repositoris, però la rigidesa / flexibilitat amb què s'apliquen és una cosa que s'ha de decidir segons els objectius del repositori.
 
Des del meu punt de vista una de les funcions més útil del repositori institucional és donar el servei de repositori per aquelles situacions en què altres repositoris existents no són adequades. Per exemple, per investigadors que treballen en un camp d'investigació per al qual no hi ha un repositori de referència; i també per donar suport a aquells investigadors que no es troben còmodes compartint dades, i prefereixen fer-ho amb algú de confiança, de la seva pròpia universitat, que els pugui guiar. Els repositoris institucionals també poden donar un servei en concret, com ara acceptar conjunts de dades que són especialment grans, i que normalment no s'accepten en repositoris de disciplines concretes (tot i que en aquest cas, és clar, la biblioteca necessitarà tenir els recursos necessaris per poder oferir alguna cosa així). El procés de revisió també pot tenir un objectiu docent: informar els investigadors de com dipositar dades d'investigació.

Els dipòsits institucionals tendeixen a acceptar dades de disciplines molt diverses, encara que per descomptat hi ha excepcions (e.g. el cas d'institucions de recerca d'un àmbit concret que acceptaran dades només d'aquest àmbit). Al meu entendre un repositori generalista haurà de ser més flexible que altres repositoris centrats en una disciplina. Per exemple, és molt difícil escollir un tipus d'estàndard de metadades o format de dades, i obligar a tots a usar-los. Aquests estàndards i formats són normalment específics per a una disciplina, i si esperem dades de moltes disciplines diferents no té sentit que sigui obligatori fer servir un format en concret.

És recomanable que el repositori tingui uns objectius clars, i que desenvolupi una política de com es tractaran les dades. Algunes de les preguntes a treballar per desenvolupar aquestes polítiques poden ser ([Green et al, 2009](https://www.coar-repositories.org/files/guide.pdf))
* Els objectius i missió de l'repositori
* El tipus de dades que el repositori accepta
* L'estat de les dades que el repositori accepta. Les dades passen per un cicle que va de dades brutes a dades llestes per compartir amb el públic.
* Versions. Si hi ha diferents versions d'un mateix conjunt de dades, com es tractaran en el repositori.
* Formats. Quins formats s'acceptaran?
* Limitacions de nombre de fitxers o volum de dades que es vulguin imposar.
* Quin tipus de metadades es generaran i preservaran

En les lliçons anteriors d'aquest mateix tema hem parlat de com curar i organitzar les dades. Aquí parlarem de com curar les metadades, i distingirem entre dos tipus de metadades.
* **El registre**: les metadades que formen part de l'repositori, que poden ser descriptives, administratives o estructurals. Algunes d'aquestes metadades seran accessibles només per a aquells que mantenen el repositori, altres seran visibles per al públic. Per a aquesta explicació ens centrarem en les metadades que normalment gestionen els bibliotecaris que curen dades, i que són visibles per als usuaris (títol, autors, abstract, etc.).
* **La documentació**: fitxers que expliquen detalladament el contingut de les dades, i en donen el context necessari per poder entendre-les.

# El registre del repositori

La major part de les metadades de l'repositori es gestionen de la mateixa manera en un registre de dades que en un registre d'altres tipus de contingut. Quan tractem amb dades hem de posar especial atenció en els següents elements.

### Llicències

### Camps descriptius que descriguin el conjunt de dades

Un error comú que els investigadors cometen és descriure el conjunt de dades amb el mateix títol, autors, abstract, etc. que l'article a què es refereixen. Això és un error. Les metadades han de descriure les dades, no l'article.
* L'abstract ha de ser una descripció dels materials en el registre, no de la interpretació de les dades.
* El títol també ha de descriure les dades. De vegades els investigadors posen la cita de l'article en el títol de les dades. Un títol és un títol, no una cita. 
* Els autors per descomptat poden ser els mateixos en l'article que en el conjunt de dades, però no tenen per què ser-ho. Publicar les dades per separat és una oportunitat excel·lent per donar crèdit a les persones que han treballat en la recollida de dades, però que no van com a coautors en l'article.

### DOI

El DOI és el Digital Object Identifier, una sèrie de caràcters alfanumèrics que identifiquen de forma única a el conjunt de dades. Un DOI és persistent i conté metadades de l'objecte. La majoria d'agències finançadores, revistes científiques etc requereixen que els conjunts de dades en repositoris tinguin un DOI. És important que el repositori tingui la capacitat de generar un DOI (o un altre identificador únic i persistent) per a cada conjunt de dades, i aquest DOI ha d'estar documentat en el registre. 

### La cita recomanada

No tots els investigadors estan familiaritzats amb dades d'investigació publicade s en obert, i alguns mai han citat dades en els seus articles, i no estan segurs de com fer-ho.

Per facilitar a altres investigadors el citar les dades correctament és útil incloure la cita en un dels camps del registre.

### Altra informació

És important que les dades continguin totes les metadades necessàries per ser útils. Tot i això, està clar que els investigadors estan acostumats a fer servir articles científics com a unitat estàndard d'informació científica. Si hi ha articles, llibres, o altres materials relacionats amb les dades, és important afegir aquesta informació al registre.

# La documentació del conjunt de dades

El més important a destacar pel que fa a la documentació és que és imprescindible que estigui present. Cap conjunt de dades s'ha de publicar sense algun tipus de documentació, la documentació hauria de ser **obligatòria**.
 
Una part de la documentació inclou **aspectes generals**, que són elements que ja havíem inclòs en el registre, i que poden estar augmentats. Per exemple, el registre inclou els autors. En la documentació podem llistar els autors i afegir altra informació extra que pot no aparèixer en el registre, com ara l'identificador ORCID de l'investigador (en el cas que no hi hagi registre d'autoritats al repositori), l'afiliació, informació de contacte com l'adreça de correu electrònic, el paper que l'autor va exercir en la creació del conjunt de dades, etc.
 
És important repetir aquesta informació perquè l'investigador que decideixi descarregar les dades la tingui, fins i tot si no ha tingut la previsió de guardar la informació present al registre.
 
A continuació, alguns dels elements que hem de tenir en compte en crear (o revisar) la documentació del conjunt de dades.

### Consistència de les metadades del registre i la documentació del conjunt de dades

Sembla que no calgui dir-ho, però la informació que hi ha repetida entre el registre i el conjunt de dades ha de ser consistent. El títol ha de ser el mateix. Els autors han de ser els mateixos. La llicència ha de ser la mateixa. Etcètera. A la pràctica, si demanem la informació dues vegades, moltes vegades (moltes!) aquesta informació no és consistent, i s'ha de corregir.

### Format de la documentació

El format de la documentació ha de seguir les mateixes normes que el format de les dades, han de complir els principis FAIR. Si hi ha un estàndard que sigui adequat, s'ha d'utilitzar. Podeu trobar una llista d'estàndards de metadades de recerca en directori de metadades de la Research Data Alliance [http://rd-alliance.github.io/metadata-directory/standards/](http://rd-alliance.github.io/metadata-directory/standards/)

A la pràctica moltes vegades és difícil utilitzar un estàndard de metadades, sobretot si treballem amb un repositori agnòstic. Si no hi ha un estàndard que sigui adequat es pot crear un simple fitxer de text amb la informació necessària. És obert, i fàcil de generar. Moltes vegades aquests fitxers es diuen "readme". Podeu trobar un exemple de plantilla de readme en [aquest enllaç](https://raw.githubusercontent.com/osulp/Data-Management-Templates-Project/master/Documentation_Template/Documentation_Template.txt). És una versió adaptada a la Oregon State University d'una plantilla que fan servir molts repositoris institucionals.

### Informació de contacte

Idealment les persones que reutilitzin les dades no necessitaran contactar a l'autor, perquè tota la informació estarà clarament explicada en la documentació. Però per si de cas, és important especificar en la documentació qui és la persona de contacte a qui enviar preguntes, si n'hi ha. La informació de contacte ha de ser tan persistent com sigui possible. Per exemple, si les dades kes està dipositant un estudiant de doctorat a punt d'acabar la seva tesi, l'adreça de correu electrònic de la universitat pot no ser el contacte més durador. Algunes solucions possibles són proporcionar una altra adreça de correu electrònic, o afegir una segona persona de contacte que tingui una posició permanent a la universitat, o tenir un perfil obert de ORCID mitjançant el qual es pugui contactar.

### Enllaços robustos

Els enllaços en un fitxer de documentació han de ser el més robustos possible. Això vol dir:
* En curar les dades ens assegurarem que tots els enllaços funcionen.
* També ens assegurarem que, quan sigui possible, portin a continguts oberts. Per exemple, si hi ha un article que analitza i explica les dades, l'article hauria d'estar citat en la documentació. Si hi ha una versió de l'article en obert, i una versió que no està en obert, en la documentació hauríem d'incloure com accedir a la versió en obert.
* També valorarem si els enllaços van a materials que esperem que perdurin en el temps.

### Llista de fitxers

Si el conjunt de dades té més d'un fitxer de dades s'ha d'incloure una descripció del contingut de cada un dels fitxers o carpetes.

### Diccionari de dades

Com hem vist en la lliçó anterior, en el cas de dades en forma tabular és important incloure en la documentació la descripció de cadascuna de les variables. Tot i que els títols de les columnes semblin clars, han de definir-se. També inclourem unitats, i tota la informació necessària per interpretar les dades, com una llista de valors possibles per a una determinada variable (per exemple, si hi ha una variable que sigui "color", quins són els valors acceptables?), definicions d'acrònims, o valors nuls.

### Mètodes

La documentació ha d'incloure informació sobre com es van recol·lectar les dades, quins protocols es van fer servir, quin control de qualitat es va aplicar, com es van analitzar les dades, etc. És molt comú que els investigadors vulguin citar un article publicat en comptes de reescriure tots els mètodes. Això és acceptable, però en aquest cas és especialment important comptar amb una versió en obert de l'article, perquè sense aquesta informació la utilitat de les dades queda notablement reduïda. Crec que és important explicar als investigadors que un conjunt de dades és l'oportunitat perfecta per afegir tota aquella informació que no hem pogut incloure en la secció de mètodes de l'article. 

# Curar dades quan no s'és expert en el tema

Les guies d'aquest tema parteixen de el supòsit que el curador de dades no és un expert en la disciplina de les dades que està curant. Ser expert en la matèria ajudarà molt el curador. Per als que no som normalment experts en la matèria de les dades que curem, els recursos desenvolupats pel Data Curation Network són molt útils.
 
El Data Curation Network és un projecte que ha desenvolupat (i continua desenvolupant) una sèrie de guies, anomenades "primers" que contenen informació que ajuda a un curador a avaluar un conjunt de dades del qual no és expert. Conté informació sobre el tipus de fitxers, com obrir-los, i els requisits que recomanen que es compleixin per ser acceptats en un repositori.

Passeu uns minuts explorant el contingut d'aquests primers, per utilitzar-los com a referència quan ho necessiteu [https://datacurationnetwork.org/outputs/data-curation-primers/](https://datacurationnetwork.org/outputs/data-curation-primers/).

Un altre element molt útil del Data Curation Network és que han desenvolupat una llista d'accions que un curador realitza en revisar un conjunt de dades. Podeu accedir a aquesta llista amb aquest enllaç: [https://datacurationnetwork.org/outputs/workflows/](https://datacurationnetwork.org/outputs/workflows/) És una llista molt més detallada del que hem revisat en aquests tema, si us plau reviseu-la també com a part d'aquesta lliçó. No tots els elements d'aquesta llista son adequats per a un determinat repositori (per exemple, en el meu cas, no tenim recursos suficients per assegurar-nos que el codi que els investigadors dipositen en el nostre repositori es pot compilar i executar correctament), però crec que és interessant tenir-la en compte quan creeu vostra pròpia llista d'elements a considerar en els vostres repositoris.


# Referències

Green, A., MacDonald, S., & Rice, R. (2009). Policy-making for Research Data in Repositories: A Guide. Data Information Specialists Committee. [https://www.coar-repositories.org/files/guide.pdf](https://www.coar-repositories.org/files/guide.pdf)


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
