# Base de dades distribuida - Components

Quan parlem de base de dades distribuida apareixen nous conceptes i acrònims que cal saber:

* **DDBMS**: Distributed Database Management System.
* **DTM**: Distributed Transactionb Manager. Encarregat de gestionar i coordinar transaccions entre les diferents màquines on està distribuit el nostre sistema gestor de base de dades. Cal recordar que les transaccions comencen i finalizen, que durant la seva vida es fan canvis sobre les dades i que en finalitzar els canvis es confirmen o es desestimen.
* **DBM**: DataBase Manager.
* **Node**: Cadascuna de les màquines independents sobre les que s'està executant el DDBMS. De vegades es parla de `cluster` al conjunt de nodes que conformen el sistema.
* **Maquinari**: Per ser un sistema distribuit s'ha d'executar sobre màquines que no comparteixen components, és a dir, vàries màquines interconnectades per xarxa però sense compartir CPU ni memòria.
* **Programari**: cadascuna de les màquines sobre les que s'executa el sistema distribuit disposa del seu propi programari, com a mínim un sistema operatiu i el programari del DDBMS.

**Exercicis**

1. Familiaritza't amb els nous conceptes esmentats.
2. Fes un diagrama que representi diferents màquines connectades via xarxa, en diferents edificis o llocs del planeta, i que totes juntes formin un DDBMS.


