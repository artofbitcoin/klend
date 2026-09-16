# 4. Liquidation et limites

La liquidation rembourse une dette et saisit une garantie lorsque le ratio de santé franchit le seuil. Les montants sont bornés par les réserves et les règles de close factor.

Le liquidateur doit fournir les comptes attendus et respecter les contraintes de marché. Les vérifications d’autorité empêchent un programme externe de modifier une position qui ne lui appartient pas.

Les risques portent sur l’oracle, les arrondis, la liquidité de sortie, les comptes mal initialisés et les migrations de programme.

Dernier chapitre : les tests du dépôt sont la référence pour approfondir les scénarios ; ils n’ont pas été exécutés pour ce parcours documentaire.
