# MCC_Data_acquisition
DC Motor data acquisition files recorded from a data acquisition board conneted to the system  
****************************************************************************************
 BACHA Abdelkabir - OSIL Team- Laboratoire LRI - ENSEM - University of Hassan II - Casablanca 
 ****************************************************************************************

This work was used in my phd thesis. Please refer to link below to consult a journal that was published in the International Journal of 
Computer Applications - FCS® (Foundation of Computer Science). If you want to use this work in your research please cite this article.  
The link : https://www.ijcaonline.org/archives/volume124/number5/22104-22104-2015905484 
DOI : 	10.5120/ijca2015905484


On cite parmi les variables qu’on a pu mesurer : 
•	Le courant de la MCC étudiée
•	La tension de la MCC
•	La température interne : près des balais et du collecteur.
•	La température externe.
•	La température du pont de commande (H-bridge)
•	Le rapport cyclique : commande de la vitesse
•	La vitesse de rotation.
•	L’état de mise marche de la machine : start = 1 : la machine et en marche, start = 0 : le contraire. 

A la sortie de la carte d’acquisition, les enregistrements des états instantanés de variables citées sont disponibles via les deux modes de transmission : port série (UART) et Bus I2C.
On a collecté ces données pendant des périodes données (fonctionnement normale, à vide, avec surcharge, avec axe bloqué, etc) et on les a enregistré dans des fichiers d’extension  (.txt et .csv).
