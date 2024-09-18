# Android Saving Data
## Exercici de Introducció a les bases de dades
La major part d'aplicacions Android necessiten desar dades, això ens ho explica aquesta documentació extreta dels manual d'Android [Saving Data](https://developer.android.com/training/data-storage)  per a desenvolupadors Android: 

### Data and File Storage Overview

Android uses a file system that's similar to disk-based file systems on other platforms. The system provides several options for saving app data:

#### 1. App-specific storage
Store files that are meant for your app's use only, either in dedicated directories within an internal storage volume or different dedicated directories within external storage. Use the directories within internal storage to save sensitive information that **other apps shouldn't access**.

#### 2. Shared storage
Store files that your app intends to share with other apps, including:
- Media
- Documents
- Other files

#### 3. Preferences
Store private, primitive data in **key-value pairs**.

#### 4. Databases
Store structured data in a private database using the **Room persistence library**.


* Quins tres tipus de mecanismes podem fer servir per a desar dades?
* Per a què estan pensats cadasqun d'aquests mecanismes?
* Quin Sistema Gestor de Base de Dades fa servir Android?
