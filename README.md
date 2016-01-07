# rail3dtools
Utilities for Rail3D Transport Network Emulator

This tutorial comes from my desire to build a route layout that represents one of the places I love: the valley
of the river Marecchia (near Rimini, Italy).

Along the banks of this river there were two railway lines: on the left bank the never born "subappennina"
from Santarcangelo di Romagna to Urbino. On the opposite side the Rimini - Mercatino Marecchia (now
Novafeltria) entered service in 1916 and abandoned in 1960.

You can still see all the stations (though not always easy to recognize) and numerous other manufactures
such as tunnels and bridges.


Nel progettare lo scenario mi sono imbattuto nella necessità di gestire una moltitudine di dati relativi ale
stazioni, i ponti, le linee ferroviarie (solo a Rimini se ne intersecavano tre), i fiumi (oltre al Marecchia c'è l'Ausa
e il Mazzocco).

Avevo iniziato a preparare tali dati per il Train Simulator di Microsoft con l'ausilio di Google Earth e volevo
riutilizzarli; avevo anche trovato il modo di scaricare dal Portale Cartografico Nazionale dati DEM ad altisima
risoluzione e non avevo alcuna intenzione di modellare a mano tutte le alture che circondano la valle.

Così mi sono messo all'opera ed ho scritto alcune utility per utilizzare questi dati anche con Rail3D.

Con la versione 107.0.1.6 è inoltre stata resa disponibile una funzione che permette di emulare l'opzione “Lay
At Terrain Level” anche nella posa dei binari tramite script e questo ha permesso di generare automaticamente linee ferroviarie, strade e fiumi direttamente dai path di Google Earth.
