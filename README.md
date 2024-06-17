# Booki
## contexte
Booki est un site de comparaison d'hébergements et d'activités à Marseille.
## choix
### responsive
Le site est responsive conçu en desktop-first.
#### min-width 320
Je vois comme inutile de forcer l'affichage en largeur d'éléments en ligne sur un écran très étroit.
#### Flexbox
Flexbox est choisi en premier partout où c'est possible car il y aurait moins de modifications responsive pour passer en colonne.
#### unités
##### utilisation de pixels 
Les pixels sont visuellement conformes pour les élements d'en-tête
##### utilisation de %
L'utilisation est réalisable pour la largeur 
### balises sémantiques
#### aside 
La section populaires serait aside au contenu indépendant selon la documentation https://developer.mozilla.org/en-US/docs/Web/HTML/Element/aside, "The paragraph is only indirectly related to the main article content". Je pense que le lien entre Populaires et Hébergements est direct. Aside est seulement visuellement de côté sur grands écrans.