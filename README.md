# Applications documentaires

Catalogue public d'applications documentaires, réalisé en HTML, CSS et JavaScript, avec une présentation **DSFR-like** (sans prétention de conformité DSFR ou RGAA officielle).

## Accès

Adresse prévue après activation de GitHub Pages : https://didierthebault-web.github.io/applications-documentaires/

## Fonctionnalités

- 9 projets publics présentés sous forme de cartes
- Fiches détaillées (objectifs, fonctionnalités, publics, limites)
- Recherche textuelle et filtres par domaine et type d'accès
- Liens directs vers les applications lorsque la publication est documentée
- Accès aux dépôts GitHub de chaque projet
- Interface adaptable aux petits écrans, navigation au clavier

## Mise en ligne

Le site se trouve à la racine du dépôt, dans `index.html`.

Pour activer GitHub Pages :

1. Ouvrir **Settings > Pages** dans le dépôt.
2. Dans **Build and deployment**, choisir **Deploy from a branch**.
3. Sélectionner **main** et **/(root)**.
4. Cliquer sur **Save**.
5. Consulter la rubrique Pages pour vérifier le lien et l'état du déploiement.

GitHub Pages peut prendre quelques instants pour rendre le site accessible. L'adresse ci-dessus n'est pas garantie avant vérification.

## Modifier le catalogue

Éditer le tableau `apps` à la fin du fichier `index.html`. Les liens `live` sont réservés aux applications dont l'URL publique a été identifiée ; une valeur `null` dirige uniquement vers le dépôt source.

Les dépôts privés sont volontairement exclus.

## Limites

Cette plateforme est indépendante : il ne s'agit pas d'un site officiel du ministère de la Culture. Les liens externes et la disponibilité des outils ne sont pas vérifiés automatiquement. Un audit d'accessibilité RGAA complet reste nécessaire.
