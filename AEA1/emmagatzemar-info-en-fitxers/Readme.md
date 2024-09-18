## Fitxers

Els fitxers són un mitjà d'emmagatzematge de dades utilitzat en informàtica per guardar i gestionar informació. Hi ha diversos tipus de fitxers, cadascun amb característiques específiques que determinen com s'emmagatzemen i accedeixen les dades.

### 1. Fitxers plans
Els **fitxers plans** són els més senzills. Emmagatzemen la informació com a text sense cap estructura interna, separant els camps amb delimitadors com espais o comes. Són fàcils de llegir i escriure, però el seu accés pot ser lent per a volums de dades grans.


### 2. Fitxers d'accés directe
Els **fitxers d'accés directe** permeten accedir a qualsevol registre del fitxer sense necessitat de llegir tot el contingut prèviament. Això es fa utilitzant una adreça o una clau única que identifica la ubicació del registre. Són ideals per a situacions en què es requereix un accés ràpid i eficient a les dades. Son fitxers binaris, si els obrim amb un editor de text només veurem caràcters especials.

```
+----------------------------+
|   FITXER D'ACCÉS DIRECTE    |
+----------------------------+
|  Registre 1  |  Adreça 001  |
+----------------------------+
|  Registre 2  |  Adreça 002  |
+----------------------------+
|  Registre 3  |  Adreça 003  |
+----------------------------+
|  Registre 4  |  Adreça 004  |
+----------------------------+
```

### 3. Fitxers indexats
Els **fitxers indexats** fan ús d'un índex per accelerar l'accés a la informació. Aquests índexs permeten accedir a determinats registres de manera més ràpida que en un fitxer pla, ja que l'índex actua com una guia que apunta a la ubicació exacta de les dades dins del fitxer. Son fitxers binaris, si els obrim amb un editor de text només veurem caràcters especials.

```
+----------------------------+          +----------------------+
|   FITXER INDEXAT            |          |       ÍNDEX          |
+----------------------------+          +----------------------+
|  Registre 1  |  Dada 1      |  <------ |  Clau 1 -> Adreça 1  |
+----------------------------+          +----------------------+
|  Registre 2  |  Dada 2      |  <------ |  Clau 2 -> Adreça 2  |
+----------------------------+          +----------------------+
|  Registre 3  |  Dada 3      |  <------ |  Clau 3 -> Adreça 3  |
+----------------------------+          +----------------------+
|  Registre 4  |  Dada 4      |  <------ |  Clau 4 -> Adreça 4  |
+----------------------------+          +----------------------+
```



### 4. Altres tipus de fitxers
Existeixen altres tipus de fitxers que combinen característiques d'aquests tipus bàsics, com els **fitxers seqüencials indexats**, que permeten accedir tant de manera seqüencial com per índex. La selecció del tipus de fitxer depèn de les necessitats específiques de rendiment i gestió de les dades.


