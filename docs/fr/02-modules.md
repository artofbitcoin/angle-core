# 2. Architecture des modules

Angle sépare le Core Module, le module d’emprunt et les stratégies de rendement. Cette découpe limite le couplage et permet de faire évoluer une famille de contrats sans réécrire toute la gouvernance.

Les contrats transverses, comme agToken, peuvent exister dans plusieurs dépôts ou versions. Pour comprendre un déploiement réel, il faut donc identifier la version utilisée et ses adresses, plutôt que déduire l’état on-chain du seul dépôt.

Le routeur, les contrôleurs et les contrats de DAO forment les points de jonction entre utilisateurs, réserves et gouvernance.

[Chapitre suivant : gouvernance et surplus](03-governance-surplus.md)
