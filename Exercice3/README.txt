1 - On aura comme probl�me ici de faire envoyer chaque 10 secondes un signal
	qu serveur � partir du client. Ensuite le serveur devra declencher
	deux processus � chauqe fois qu'il recoit un signal du client.

2 - Pour resourdre ce probl�me, nous devons, dire au client d'envoyer un signal 
 toutes les dix secondes et faire d�clencher auniveau du serveur des processus 
 � chaque fois qu'il re�pit un signal du client.

3 - Impl�mentation