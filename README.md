BA Cheikh </br>
LAARIF Rayen </br>
RATOANDROMANANA Iavosoa </br>
# Projet GNN - Prédiction de lien
Dans ce projet, nous avons caché des liens dans le graphe afin de voir si notre modèle serait capable de les retrouver. Nous l'avons fait pour 2 cas: prédire les noeuds des pays et prédire ceux des villes.

Le lien du projet: [Projet GNN](https://github.com/Sheik-info/gnn_project)

## Comment exécuter le code?
Ouvrir le projet dans un Google Collab. </br>
Pour exécuter le code pour prédire les noeuds des pays ou des villes, commenter la cellule non-concernée.

## Ablation study
Pour faire la prédction de liens, nous avons utilisé un VGAE car il s'agit d'un modèle souvent utilisé pour la prédiction de liens manquants. Dans notre modèle, nous utilisons deux couches GCN. Si on retire une couche, les performances sont moins bonnes: on retrouve moins de lien et le score de précision baisse fortement. Si on rajoute une couche en plus, les calculs sont plus long pour un résultat quasi-identique avec 2 couches.

## Utilisation de l'IA générative
Utilisation de Claude de le part de Rayen LAARIF pour resumer le TP et rattraper les lacunes après rejoindre le groupe 2 semaines en retard.
Exemple de Prompt: Expliquer cellule par cellule l'avancement sur le TP.
