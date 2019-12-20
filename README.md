# CSI AtlanteWI - Accesso organizzato a dati e geoservizi

CSI AtlanteWI è un plugin del software GIS 
[QGIS](https://qgis.org "QGIS - A Free and Open Source Geographic Information System") 
ed è l'evoluzione del plugin CSI Atlante ( https://github.com/SITA-RegionePiemonte/CSIAtlante ) sviluppato per la versione di QGIS 3.x

Pensato per un'organizzazione (enti pubblici, singoli dipartimenti/direzioni,...) 
dove gli amministratori del Sistema Informativo Territoriale (SIT)
guidano, attraverso un catalogo strutturato, gli utilizzatori finali di QGIS all'accesso 
ai dati vettoriali (PostGIS) e ai geoservizi (WMS) di riferimento.

Il sistema è composto da tre componenti principali :

- Plugin Qgis 3.4 : componente client per la gestione delle alberature di dati e servizi
- Modulo Drupal8 : componente per la gestione dell'autenticazione, profilazione utente ed erogazione dati
- Backoffice : componente per l'alimentazione della base dati utile alla pubblicazione

In questa fase viene pubblicata esclusivamente la prima componente (https://github.com/SITA-RegionePiemonte/CSIAtlanteWI-PluginQgis). 
Nell'arco del 2020 saranno pubblicati anche il Modulo Drupal e, a seguire, il backoffice.

Le differenze principali rispetto alla versione precedente sono le seguenti :

- interfaccia gestita in una Webview
- accesso tramite login personale
- integrazione con Drupal8 (Modulo Drupal)
- registrazione e cambio password autonoma
- gestione profilazione e privilegi
- gestione di progetti personali e di gruppo
- editing dati postgis


## Features:
* Presentazione di dati geografici
* Ricerca di dati geografici
* Tematizzazione dati geografici
* Profilazione per utenti e gruppi di utenti

# Prerequisites
Installing [QGIS 3.4](https://docs.qgis.org/3.4/en/docs/)

# Installing
[QGIS Lesson: Installing and Managing Plugins](docs.qgis.org/3.4/en/docs/training_manual/qgis_plugins/index.html#"QGIS Lesson: Installing and Managing Plugins")

# Contributing
Please read CONTRIBUTING.md for details on our code of conduct, and the process for submitting pull requests to us.

# Versioning
We use Semantic Versioning for versioning. (http://semver.org)

# Copyrights
© Copyright: Regione Piemonte 2019

# License
See the LICENSE.md file for details



