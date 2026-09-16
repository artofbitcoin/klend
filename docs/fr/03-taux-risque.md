# 3. Taux et risque

Les taux dépendent de l’utilisation et des paramètres de chaque réserve. Le modèle doit distinguer la dette, les intérêts accumulés et les frais de protocole.

Les limites de prêt, le loan-to-value et le liquidation threshold déterminent la marge disponible. Un compte peut rester emprunteur tout en devenant liquidable lorsque la valeur oracle baisse.

Les oracles et leurs timestamps sont des dépendances critiques. Une donnée trop ancienne, mal décimée ou absente doit empêcher une décision dangereuse.

La conception Solana ajoute des contrôles de propriétaires et de comptes mutables : une instruction correcte sur le plan économique peut néanmoins être invalide si sa topologie de comptes est incorrecte.

Suite : [liquidation et limites](04-liquidation-limites.md).
