# 13. Pourquoi ai-je du temps d'attente dans mon plan de tournée ?

L'algorithme d'optimisation peut introduire du temps d'attente pour ces raisons :

1. Le livreur arrive à l'emplacement du client **avant les heures d'ouverture**.
2. Le livreur rejoint le dépôt **avant qu'il ne devienne opérationnel**.

Les heures d'ouverture des clients et du dépôt sont des contraintes strictes à haute priorité, donc l'algorithme doit les respecter.

**Astuce :** Pour réduire le temps d'attente inutile, utilisez le **contrainte "Heure de départ automatique"** Cette fonctionnalité ajuste l'heure de départ afin que le livreur parte plus tard et arrive chez le client ou au dépôt au bon moment, minimisant les périodes d'inactivité à des emplacements inconnus.
