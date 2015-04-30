# MCC_Data_acquisition
DC Motor data acquisition files recorded from a data acquisition board conneted to the system  
// ****************************************************************************************
// BACHA Abdelkabir - Equipe EAP- Laboratoire LISER - ENSEM - UH2C 
// ****************************************************************************************



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
