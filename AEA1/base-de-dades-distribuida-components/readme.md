# Base de dades distribuida - Components

# Components d’un SGBD distribuït

1. **Node d'emmagatzematge (Data Nodes)**  
   - Emmagatzemen físicament les dades i gestionen les operacions de lectura i escriptura.
   - En bases de dades distribuïdes, les dades solen estar particionades o replicades entre múltiples nodes.

2. **Node de consulta (Query Nodes)**  
   - Gestionen les sol·licituds de consultes enviades pels usuaris o aplicacions.
   - Poden descompondre les consultes i distribuir-les entre els nodes d'emmagatzematge.
   
3. **Coordinador o gestor de transaccions (Transaction Coordinator)**  
   - Garanteix que les transaccions distribuïdes es gestionin correctament, complint amb les propietats ACID.
   - Implementa protocols com el **two-phase commit (2PC)** per coordinar les transaccions distribuïdes.

4. **Catàleg o metadades (Catalog/Metadata Store)**  
   - Conté la informació sobre l'estructura de la base de dades (esquema), el mapa de dades distribuïdes entre nodes i altres metadades importants.
   - Ajuda en l'optimització de les consultes i en la localització de dades distribuïdes.

5. **Mecanisme de replicació (Replication Manager)**  
   - Gestiona la duplicació de dades en múltiples nodes per garantir la disponibilitat i la tolerància a fallades.
   - Pot ser replicació síncrona o asíncrona, depenent de la consistència requerida.

6. **Mecanisme de particionament (Partitioning Manager)**  
   - Defineix com es divideixen les dades entre els nodes del sistema (particionament horitzontal, vertical o híbrid).
   - Garanteix un equilibri de càrrega adequat i una optimització en l'accés a les dades.

7. **Monitoratge i recuperació d'errors (Monitoring and Fault Tolerance)**  
   - Supervisa el rendiment i l'estat dels nodes i el sistema global.
   - Inclou mecanismes de recuperació automàtica davant fallades dels nodes per garantir la continuïtat del servei.


**Exercicis**

1. Familiaritza't amb els nous conceptes esmentats.
2. Fes un diagrama que representi diferents màquines connectades via xarxa, en diferents edificis o llocs del planeta, i que totes juntes formin un DDBMS.


