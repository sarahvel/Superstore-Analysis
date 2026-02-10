## Projet d’analyse – Superstore 🛒

### Contexte

Ce projet porte sur l’analyse des ventes d’un magasin fictif situé aux États-Unis et vise à évaluer l’impact des remises, du mix produit et des catégories de produits sur la rentabilité, à partir de données commerciales fictives.

### Problématique

Comment l'enseigne Superstore peut-elle améliorer durablement sa rentabilité sans dépendre d’une croissance des volumes, en agissant sur les remises, les clients et le mix produit ?

### Fichiers de données

**Rapport d'analyse** : [Consulter le rapport (PDF)](Analyse_Superstore_Ventes.pdf)  
**Jeu de données** : [SuperStore_Orders.csv](SuperStore_Orders.csv) (données brutes utilisées pour l'analyse)

### Méthodologie

Visualisation réalisée sur Tableau.

- **Nettoyage** : standardisation des dates, catégories, segments et régions
- **Analyse des ventes** : évolution temporelle, volumes et chiffre d’affaires
- **Rentabilité** : analyse profit / perte par clients et sous-catégorie de produits
- **Remises** : impact des discounts sur les ventes et la marge
- **Segmentation** : performance par segment client


### Résultats clés

- La politique de remise détruit la rentabilité : remises > 20% engendre des pertes systématiques
- 15,7% des ventes sont réalisées avec des remises supérieures à 20% (volume significatif de transactions déficitaires)
- Les ventes non rentables détruisent près de 35 % du profit potentiel :
    - Profit réel : 292K$
    - Profit potentiel : 449K$
    - Manque à gagner : 157K$
- Des clients générant un fort CA peuvent en réalité être destructeurs de valeur (profits négatifs)
- Les 7 clients classés "Top clients" génèrent à eux seuls 14,2 % du profit total
- Faiblement rentables individuellement, les "Clients à potentiel" compensent collectivement les pertes et soutiennent le profit global
- 3 sous-catégories sur 17 non rentables
    - Tables : ventes importantes (~250K) mais profits négatifs(−20K)
    - Bookcase : ventes correctes (~115K) mais perte de −3,6K
    - Supplies : ventes plus faibles (~47K) mais profits négatif −1,1K

### Conclusion globale

La rentabilité est pénalisée par une politique de remises excessives et un pilotage trop orienté volume. 
Les ventes non rentables détruisent près de 35 % du profit potentiel, tandis que le chiffre d’affaires masque des clients et catégories destructeurs de valeur.
La performance repose sur un nombre limité de clients clés et sur l’effet de masse des clients à potentiel, rendant le modèle fragile.
Le principal levier de création de valeur réside désormais dans la discipline commerciale et la rentabilité, plutôt que dans la croissance des volumes.

### Recommandations stratégiques

**Objectif** : Récupérer une part significative du profit potentiel perdu (157 K$) en améliorant la discipline commerciale, la rentabilité des transactions et la création de valeur par client et par catégorie, sans dépendre d’une hausse des volumes.

**1) Reprendre le contrôle de la politique de remises** (priorité)

- Fixer un seuil de remise maximale (ex. 10 %) sans validation managériale
- Stopper les ventes à pertes
- Supprimer les remises sur les sous-catégories structurellement déficitaires (Tables, Bookcases, Supplies)
- Mettre en place un contrôle systématique de la rentabilité des ventes, avec alerte en cas de marge négative
- Autoriser les fortes remises uniquement si : volume minimum garanti ET marge cible respectée

Impact attendu : réduction immédiate des pertes transactionnelles.

**2) Gestion du catalogue produits**
- Tables : revoir pricing, remises et conditions de vente
- Bookcases et Supplies : revoir la position stratégique (soit redressement de la marge ou supression du catalogue)

Impact attendu : élimination de pertes structurelles récurrentes.

**3) Gestion du portefeuille clients**

- Protéger "les Top clients" : mise en place une politique de fidélisation orientée valeur (priorité de service, personnalisation de la relation, conditions logistiques adaptées, communication spéciales dédiée), sans recours aux remises tarifaires.
- Consolider les "Clients à potentiel" : optimisation des ventes, formation des vendeurs à la vente de valeur, upselling et cross-selling, orientation vers des produits plus rentables, et encadrement strict des remises.
- Assainissement des comptes critiques : réévaluation ou sortie des clients destructeurs de valeur (renégociation stricte des conditions pour les profils à marge négative)

Impact attendu : Hausse immédiate de la contribution au profit

**4) Pilotage de la performance et suivi des ventes**

- Reporting mensuel : focus sur les indicateurs critiques (ventes à perte, marge nette par client, poids des remises).
- Analyse d'opportunité : suivi du profit potentiel pour identifier les leviers de croissance immédiats. 

Impact attendu : pilotage proactif, décisions rapides
