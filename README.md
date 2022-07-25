# Inventory-System
Blueprint Inventory System
Developed with Unreal Engine 4.27

**-- Le système d'inventaire en mode blueprints --**

OBJECTFS :
Dans un premier temps FINALISER la mécanique blueprint de l'inventaire.
L'aspect graphique est réduit au minimum, on ne s'en ossupe pas pour l'instant.
Le système d'inventaire doit être simple, complet, modulable et customisable.
Le système sera distribué gratuitement sous licence creative commons.
La participation au projet est libre et gratuite.

PRESENTATION :
- Slot based Inventaire.
- Items Stackable.
- Inventaire principal (sac à dos) + inventaires secondaires (onglets) + Equipement.
- Système d'équipement (UMG + Player preview).
- Système USE/DROP/CRAFT (items).
- Système de librairie (items Livres) avec système de classement/tri des entrées.
- Poids des items dans l'inventaire inventaire
- Système de messages (widget) intégré (exemple : vous devez d'abord obtenir le rang Novice pour lire ce livre" ou " vous avez mangé une pomme", etc.

**L'inventaire principal (sac à dos)** stocke en vrac les items au fur et à mesure que le joueur les trouve.

**Les inventaires secondaires (onglets)** classent les items selon leur catégorie :
- Armes
- Armures
- Minerais
- Livres
- Plantes
- Potions
- Consumables
- Quest items
- Upgrades, etc.,

L'onglet **Livres** contient :
- la liste des livres trouvés (scroll box),
- un descriptif du livre (Titre ; Auteur ; Langue ; Année ; Genre)
- un résumé,
- une image de l'auteur,
- le statut du livre : Lu ;  Traduit
- Un niveau de rareté
- Un bouton pour classer selon la Langue, les Auteurs, le Genre, Année, Titre
Cliquer sur un livre de la liste ouvre la page descriptive.
Une icone après le titre dans la liste indique le statut Lu et/ou Traduit et sa Rareté.

L'onglet **Plantes** permet de crafter des potions et des remèdes (mélanger deux plantes = un remède ou potion).
L'onglet **Minerais** permet de crafter les minerais (Raffiner le minerais donne du métal).
L'onglet **Armes** contient les armes trouvées par le joueur (Possibilité d'Upgrader les armes avec des upgrades).
L'onglet **Armures** contient les armures trouvées par le joueur (Possibilité d'Upgrader les armures avec des upgrades).
L'onglet **consumables** contient les consumables.
L'onglet **Upgrades** contient les Upgrades.
L'onglet **Quest Items** contient les objets de quêtes et artefacts spéciaux et objets de quête.

**Options :**
INVENTAIRE
- Prévisualisation des objets en rotation.
- Hotbar (touches 1 à 9).

AUTRES FEATURES
- Journal widget.
- Skill Tree widget.
