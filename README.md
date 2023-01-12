# Minim2-EA
S'ha creat una nova classe anomenada Report que està associada a un usuari, té un string de tipus (user, parking, other), un string amb la queixa del usuari, 
un string de data (on es guarda la hora i el dia de quan es va realitzar la denúncia) i la categoria que en principi la idea és que fos del 1 al 3 (baix, mig i alt) 
però n'hi ha 4, del 0 al 3.

BACKEND:
  Classe Report amb el model, controller i la "api".
  S'ha implementat crear un report, esborrar-lo, agafar-los tots i agafar-ne un.
  Quan es crea un report també es guarda el id d'aquest en la classe usuari per si posteriorment es vol veure la llista de reports d'un usuari
 
 FRONTEND
  S'ha creat una view anomenada report amb una columna que conté:
    - Un text que indica el que es pot fer en aquella view
    - Un desplegable multiselector per indicar si la queixa és sobre un usuari, parking o altres.
    - Una casella on s'ha d'escriure la queixa
    - Un lliscador per seleccionar el grau de gravetat
  Un cop es fa click a submit s'agafa la hora del ordinador i els camps anteriors i s'envia cap a backend.
  S'ha creat un servei que pot crear un parking, esborrar-lo i agafar-los tots.
  
  A la view del report es volia fer una listview per veure altres denuncies, però no funcionava correctament i s'ha comentat. 
  
