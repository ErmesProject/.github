# ERMES Project

## Descrizione

"Applicativi per funzioni di segnalamento ferroviario" - Dimostratori di ambiente di progettazione dei sistemi ACC/ACCM

## Architettura
> Questo diagramma si riferisce alla versione 1.0 del Sistema e deve essere aggiornata.

![System Architecture](https://github.com/ErmesProject/ermes-project/blob/master/documentation/SysPkgDiagram.png)


### Prerequisiti

I prerequisiti per poter installare e runnare l'applicazione sono:


>~~(Importante!) La versione di Java deve essere superiore o uguale alla 1.8.0_60 (consigliata una versione uguale o superiore a 1.8.0_201)~~
>(Importante!) La versione di Java deve essere superiore o uguale alla 11.0.9



>mvn, git

>(Per utilizzare i metodi della Configurazione) Installare il plugin per Eclipse di UML2 tramite update site: [Updatesite](http://download.eclipse.org/modeling/mdt/uml2/updates/releases/)


#### UI - SceneBuilder (Per JavaFX)
Per poter lavorare sulla grafica con **JavaFX** è necessario l'utilizzo del tool **SceneBuilder** versione 11 o successiva ([Download SceneBuilder](https://gluonhq.com/products/scene-builder)).

Bisogna inoltre importare all'interno di SceneBuilder la libreria JFoenix versione 9.0.8 o successiva ([Download JFoenix](https://github.com/jfoenixadmin/JFoenix)).

![Java FX Library](https://github.com/ErmesProject/ermes-project/blob/master/documentation/SceneBuilder-Import-JFoenix.png)

### Importazione Progetto in Eclipse

Come importare il progetto in Eclipse:
* Scaricare l’ultima versione di Eclipse la Java Enterprise Edition
* [Per utenti MAC](https://www.itemis.com/en/yakindu/state-machine/documentation/user-guide/inst_installing_to_an_existing_eclipse_instance#inst_installing_to_an_existing_eclipse_instance) - Installare Eclipse dentro la cartella /Applications (per  far funzionare YAKINDU come plugin all'interno di Eclipse e non dover utilizzare il bundle Eclipse di Yakindu dedicato): 
* (NOTA: On macOS, this only works if your .app file is located in your app folder.  (Bisogna cioè scaricare una versione di Eclipse e metterla dentro la cartella Application. Quindi installare il plugin come da specifica)).
* [Update site di YAKINDU](http://updates.yakindu.com/statecharts/releases/)
* git clone del progetto su github in locale
* Import del progetto come "Existing Maven Project"
* Sul progetto root fare Maven Update Project


## Tecnologie Utilizzate

* [Maven](https://maven.apache.org/) - Dependency Management
* [GIT](https://git-scm.com/) - Version Control System 
* [YAKINDU](https://www.itemis.com/en/yakindu/state-machine/) - An integrated modelling environment for the specification and development of reactive, event-driven systems based on the concept of state machines.
* [JavaFX](https://openjfx.io) - JavaFX is an open source, next generation client application platform for desktop, mobile and embedded systems built on Java
* [Scene Builder](https://gluonhq.com/products/scene-builder/) - Drag & Drop, Rapid Application Development for Java FX


## Sviluppatori

<b>Team Attuale:</b>
* Lombardi Tiziano,
* Cingolani Davide,
* Perelli Andrea,
* Ricci Matteo,
* Di Francesco Stefano,
* Rea Gianluca,
* Valdeburgo Mario
* Intrevado Michele
* Santone Domenico

<b>Hanno collaborato:</b>
* Basciani Francesco,
* Andreoli Lorenzo


## Acknowledgments

* RFI - Rete Ferroviaria Italiana

## Credits

&copy; 2019 - 2023, DISIM - University of L'Aquila, Model-Driven Engineering group
