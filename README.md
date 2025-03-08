# README - Projet INFO903

## Description du Projet
Ce projet concerne l'utilisation et l'adaptation des architectures YOLO pour la détection de maladie de feuille basé sur une implémentation FromScratch depuis PascalVoc.

## Contenu du Projet
- **YOLOv1** :
  - Commentaires sur l'architecture présents uniquement dans le fichier _PascalVOC_.
  - Indications sur les modifications nécessaires pour l'adaptation LeafDiseases dans le fichier _leafdisease_ cependant aucunes modifications n'est appliqué car nous n'avons jamais réussis à passer toutes les erreurs. Entre autres, actuellement le modèle leafdisease utilise le jeu de données plantdoc comme si il y avais 20 classes mais n'utilise réellement que la 1ere.
  
- **YOLOv2** :
  - Tous les éléments sont inclus dans un unique fichier.
  - Détails de l'architecture expliqués.
  - Instructions pour l'adaptation à _PlantDoc_.