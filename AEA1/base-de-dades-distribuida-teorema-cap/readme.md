# Base de dades distribuida - Teorema CAP

En informàtica teòrica, el teorema CAP, també conegut com a teorema de Brewer, formula que és impossible garantir simultàniament les tres característiques següents en una aplicació distribuïda: 

* Consistència: tots els nodes veuen la mateixa dada al mateix temps.
* Disponibilitat: la garantia que cada petició a un node rep una resposta de si ha tingut èxit o a fallat.
* Tolerància a la partició: el sistema continua operant malgrat un error a la xarxa divideixi el sistema ( aïlli certs nodes ).

Això afecta també a les bases de dades distribuides. 

**Exercici:**

1. Llegeix el blog: "[Visual Guide to NoSQL Systems](http://blog.nahurst.com/visual-guide-to-nosql-systems)" i familiaritzat amb els conceptes que allà apareixen.

![Visual Guide to NoSQL Systems](https://phaven-prod.s3.amazonaws.com/files/image_part/asset/607361/CausfGVcU2tskB-TR5b8CMm8Keg/medium_media_httpfarm5static_mevIk.png)

2. Per que l'autor de la pregunta d'stackoverflow "[Where does mongodb stand in the CAP theorem?](http://stackoverflow.com/questions/11292215/where-does-mongodb-stand-in-the-cap-theorem)" diu que Mongo és un sistema 'CA'? A que es refereix amb 'CA'?
