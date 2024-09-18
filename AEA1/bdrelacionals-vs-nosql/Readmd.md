# Tipus de bases de dades

Les bases de dades són sistemes essencials per a l'emmagatzematge i la gestió d'informació en múltiples aplicacions. Existeixen diversos tipus de bases de dades, cadascuna amb característiques pròpies que les fan adequades per a diferents casos d'ús.

## Bases de dades relacionals
Les bases de dades relacionals (RDBMS) emmagatzemen la informació en taules estructurades amb files i columnes. Utilitzen el llenguatge SQL (Structured Query Language) per gestionar i consultar les dades. La relació entre les taules s'estableix mitjançant claus primàries i foranes. Exemples populars de bases de dades relacionals són MySQL, PostgreSQL i Oracle. Les RDBMS són molt eficients per gestionar dades estructurades amb relacions complexes.

## Bases de dades NoSQL
Les bases de dades NoSQL es dissenyen per gestionar grans volums de dades no estructurades o semi-estructurades. No segueixen l'esquema de taules de les bases de dades relacionals, sinó que poden utilitzar diferents models d'emmagatzematge, com documents, grafos, clau-valor o columnes.

* MongoDB és una base de dades basada en documents, on les dades s'emmagatzemen en format JSON (o BSON). És adequada per a dades no estructurades i aplicacions que requereixen gran flexibilitat i escalabilitat.

* Cassandra és una base de dades distribuïda basada en columnes àmplies, dissenyada per gestionar grans volums de dades de manera distribuïda i amb alta disponibilitat. És ideal per a sistemes que requereixen tolerància a fallades i replicació automàtica.

## Comparació
Les bases de dades relacionals són molt útils quan es necessiten transaccions complexes, integritat de dades i relacions entre diferents entitats. D'altra banda, les bases de dades NoSQL són més eficients en aplicacions que requereixen escalabilitat horitzontal, flexibilitat en l'estructura de les dades i un rendiment alt amb grans quantitats de dades.

Cadascun d'aquests models té avantatges segons el tipus d'aplicació, necessitats de rendiment i la quantitat de dades que cal gestionar.

# Exercicis

1. StackOverflow és una web de referència al món del desenvolupament de programari. Consulta quantes preguntes hi ha en total a la web stackoverflow.com. 
2. Consulta la defininció que trobem a StackOverflow per els següents Tags, comprova també quantes consultes hi ha per cadascun d'ells: Oracle, SQL-Server, MYSQL, postgresql, MongoDB, Cassandra, ms-access, sqlite. Per cadascun d'ells busca altres tags relacionats.
2. Stackoverflow emmagatzema les preguntes i respostes un una base de dades sql-server. Es poden realitzar consultes via web a aquesta base de dades. Observa la consulta: https://data.stackexchange.com/stackoverflow/query/483836/database-ranking . Amb el resultat fes una taula on es vegi quin % de les preguntes d'stackoverflow són relatives a cadascun d'aquests tags tant als darrers dos anys com des de l'inici del servei. Utilitza el resultat de la consulta i un full de càlcul.
4. Existeixen definicions molt més formals del que és un SGBD. Busca alguna d'aquestes definicions en anglès i tradueix-la al teu idioma. Busca per 'Database Management System'.
5. El sistema gestor de base de dades pot ser un procés que s'executa a la màquina ( ex: Oracle, SQL Server, MYSQL ) o bé poden ser unes llibreries, unes dll en el cas Windows ( ex: Access, sqlite ). Observa aquestes captures del gestor de tasques i digues a quin SGBD creus que es corresponen.

![Oracle](http://i.imgur.com/CbtJX2J.png)

![SQL Server](http://i.imgur.com/xGf5SUi.png)
