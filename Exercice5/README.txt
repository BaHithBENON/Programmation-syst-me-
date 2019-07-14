
1. Problèmes à résoudre:

- Création de deux processus qui manipulerons une mémoire partager simultanément
- Envoie a intervalle de temps régulier le message qui déclenche les processus

2. Pour résourdre ces problèmes, 
- crée la mémoire partagée dans le père, puis on céer les fils dans d'autres fichiers
- on attache chaque fils à la mémoire partagée
- on effectue des opérations dans chaque fils sans attendre

3. Implémentation
