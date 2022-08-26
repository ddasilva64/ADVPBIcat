# Components entorn BI

**Contenidors de dades**

* **Dispersió de les dades**: Les dades acostumen a estar disperses i existir en _**diferents tipus de contenidors.**_
* **Contenidors de dades**: _**Magatzems de dades,**_ el contingut dels quals pot ser _**de diferent naturalesa**_, a causa de l'eina que genera aquestes dades.
* _**Continguts**_: _**Fitxers de text, bases dades, etc**_. Estan _**limitats per**_ l'accés corresponent als _**connectors de què disposin les eines d'extracció**_. Aplica a:
  * _**Data sources**_: Elements que emmagatzemen dades en origen.
  * _**Data targets**_: Magatzems de dades de destinació.
  * _**Data intermediate**_: Magatzems intermedis, que puguin ser necessaris utilitzar per a un tractament específic de les dades en un moment determinat, per al modelatge d'aquestes.

**Eines ETL (Extract-Transform-Load)**

* Eines per a l'_**extracció**_ del contingut des dels orígens, _**modelat**_ (transformació) d'aquesta informació i _**càrrega**_ als contenidors de destinació.
* Són _**imprescindibles**_, ja que _**els continguts poden estar dispersos i en diferents formats**_.
* Un cop _**extreta la informació i filtrada**_ (excloent-ne aquelles files que no siguin necessàries), es realitzaran els _**encreuaments, càlculs i altres operacions necessàries**_ amb l'objectiu _**relacionar tots els orígens implicats**_. **Taules intermèdies**: Poden existir i tenen per objecte _**inserir informació amb la dada en brut**_. _**En finalitzar el procés de modelatge poden ser eliminades**_, depenent de la temporalitat de la informació que emmagatzemen. Aquests magatzems de dades _**donen lloc als 'stages'**_, que són escenaris intermedis de càrrega.

**Quadres de Comandament (Dashboards)**

* Són eines de gestió empresarial creades per _**mesurar l'evolució de les activitats i els processos que es generen a l'interior de les organitzacions**_.
* S'utilitzen per _**construir recursos visuals**_, que facilitin la representació del contingut analitzat, per posteriorment _**agilitzar i facilitar la presa de decisions**_.
* Visualitzen les dades d'una manera _**amigable**_ i permeten la _**interacció**_ amb l'usuari, és a dir, resulta _**ràpid i senzill**_ la realització de _**segmentacions i filtrats**_, per tal de posar el focus en determinada dada.
* Dins del cicle de presentació de la dada, serà l'_**últim esglaó que es troba en el desenvolupament**_.
* És la _**capa de més interès per al client**_, és la que representa les dades requerides pel client d'una forma visual i amigable.

**KPIs (Key Performance Indicators)**

* Indicadors Clau d'Acompliment
* Fan referència a una sèrie de _**mètriques que s'utilitzen per sintetitzar la informació**_ (detallen quins són els objectius de mesura).
* Amb ells s'_**analitzaran**_ dades relacionades amb l'_**eficàcia i productivitat de les accions que es duguin a terme, de manera que faciliti la presa de decisions**_.
* Possibiliten _**determinar les accions estratègiques del negoci**_, que han estat més efectives a l'hora de complir els objectius marcats en un procés o projecte concret.
* _**No és**_ un recurs en forma d'_**eina**_, és un element imprescindible a l'hora de plantejar un projecte, que _**ens indicarà que és el que s'ha de mesurar**_.
* No només serveixen per _**detallar on es posa el focus de mesura**_, sinó que també serveixen perquè _**els desenvolupaments estiguin en constant evolució amb la finalitat de millorar**_ les dades representades i, per tant, de la seva _**anàlisi**_.

