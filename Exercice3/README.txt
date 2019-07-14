1 - On aura comme problème ici de faire envoyer chaque 10 secondes un signal
	qu serveur à partir du client. Ensuite le serveur devra declencher
	deux processus à chauqe fois qu'il recoit un signal du client.

2 - Pour resourdre ce problème, nous devons, dire au client d'envoyer un signal 
 toutes les dix secondes et faire déclencher auniveau du serveur des processus 
 à chaque fois qu'il reçpit un signal du client.

3 - Implémentation