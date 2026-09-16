# 2. Réserves et positions

Un dépôt augmente la réserve d’un actif et crédite une position de fournisseur. Un emprunt crée une dette indexée qui évolue avec les paramètres du marché.

Les comptes de réserve portent les liquidités, les limites, les taux et les oracles. Les positions utilisateurs référencent ces comptes au lieu de recopier toute la configuration.

Les conversions entre montant brut, unités de réserve et fractions de part exigent une précision stable. Les arrondis peuvent devenir économiques lorsqu’un compte est proche d’une limite.

Le programme vérifie les propriétaires de comptes, les seeds PDA et les associations attendues avant toute modification d’état.

Suite : [taux et risque](03-taux-risque.md).
