# SPEC – Site de recettes du monde

## Utilisateurs

Toute personne qui cherche une recette, du débutant au chef. Pas de compte, pas de connexion.
L'administratrice (la propriétaire du site) est la seule à ajouter, supprimer des recettes ou tout autre modification.

## Fonctionnalité principale

Trouver une recette sucrée ou salée, puis adapter les quantités au nombre de personnes.

Trois façons de chercher :
- **Recherche par nom** : une barre de recherche.
- **Filtres** : cuisine, sucré ou salé, difficulté, temps de préparation.
- **Par ingrédients** : l'utilisateur saisit ce qu'il a chez lui et le site propose des recettes qui les utilisent.

Cuisines (11) : française, italienne, indienne, japonaise, mexicaine, marocaine, algérienne, chinoise, libanaise, thaïlandaise, espagnole.

Fonctions complémentaires :
- **Adaptation des quantités** : l'utilisateur indique le nombre de personnes et les quantités sont recalculées.
- **Favoris** : enregistrés dans le navigateur de l'appareil, sans compte.
- **Partager** : copie du lien de la recette ou partage natif du téléphone.
- **Demander une recette** : formulaire pour suggérer une recette à ajouter.
- **Deux langues** : français et anglais, au choix de l'utilisateur.
- **Proposition de liste de courses** proposer une liste en fonction du nombre de personnes.

## Écrans

1. **Accueil / recherche** : barre de recherche, filtres, liste des recettes avec photo, nom, cuisine, difficulté et temps. Accès aux favoris et au formulaire de demande. 
Images défilantes sur différentes recettes et propisitions juste en bas de recettes.
2. **Mon frigo** : saisie des ingrédients disponibles et liste des recettes proposées.
3. **Fiche recette** : grande photo du plat, choix du nombre de personnes, ingrédients avec quantités adaptées, étapes, boutons Favori et Partager.

Le site s'adapte au téléphone, à la tablette et à l'ordinateur.

## Données stockées

**Recette** (ajoutée par l'administratrice)
- nom (FR et EN)
- photo du plat, de bonne qualité
- cuisine (une des 11)
- type : sucré ou salé
- difficulté : facile, moyen ou difficile
- temps de préparation (en minutes)
- nombre de personnes de référence
- ingrédients : nom (FR et EN), quantité, unité
- étapes (FR et EN)

**Demande de recette** (envoyée par un visiteur)
- nom de la recette souhaitée
- cuisine
- message facultatif
- date d'envoi

Aucune donnée personnelle n'est stockée. Les favoris restent dans le navigateur de l'utilisateur.

## Ce qu'on ne fera pas

- Comptes utilisateurs et connexion
- Ajout de recettes par les visiteurs (ils peuvent seulement en faire la demande)
- Commentaires et notes sur les recettes
- Informations nutritionnelles (calories, allergènes)
- Liste de courses
- Vidéos
- Application mobile à installer
- Langues autres que le français et l'anglais
