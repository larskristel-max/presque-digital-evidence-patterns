# Comparer une offre avant de classer son prix

Par Presque.digital · 7 octobre 2026 · [English](comparison.en.md)

Définissez le modèle exact, l'état acceptable, la configuration requise et la destination de livraison.

| Champ | Information à conserver | Si elle manque |
| --- | --- | --- |
| Modèle et configuration | Modèle exact et options requises, comme le clavier | Laisser l'éligibilité non résolue |
| État | Neuf, reconditionné ou occasion, selon l'annonce | Ne pas supposer que l'état demandé est respecté |
| Prix de l'article | Montant et inclusion ou non des taxes | Ne pas calculer de total vérifié |
| Livraison | Disponibilité à destination et frais | Laisser le total livré inconnu |
| Suppléments obligatoires | Coûts nécessaires pour respecter les critères | Les inclure avant de classer les offres |
| Preuve | Lien source, date de consultation et information pertinente | Signaler une affirmation non vérifiée |
| Résultat de recherche | Offre trouvée, aucun résultat correspondant, page bloquée ou erreur | Conserver ces résultats distincts |

## Exemple fictif

Les [offres inventées](../examples/offers.json) concernent le même appareil fictif, demandé neuf avec un clavier AZERTY et une livraison en Belgique. Les prix incluent les taxes ; aucun supplément obligatoire n'est prévu dans cet exemple.

| Offre | Article | Livraison | Clavier | Interprétation |
| --- | --- | --- | --- | --- |
| A | 800 € | 20 € | QWERTY | 820 € livré, mais configuration exclue car elle ne respecte pas le critère |
| B | 830 € | Inconnue | AZERTY | Configuration conforme ; total livré inconnu |
| C | 850 € | 15 € | AZERTY | 865 € livré ; total utilisable pour comparer les prix |

L'offre B n'est pas une offre vérifiée à 830 € livré. L'offre A n'est pas une offre adaptée moins chère. Le total de C permet une comparaison, sans établir la fiabilité du vendeur, la qualité de la garantie ou l'intérêt d'acheter. Les frais inconnus peuvent changer le classement.

Dans le JSON, `null` indique qu'aucune valeur n'est consignée. Des frais réellement nuls seraient représentés par `0`, avec une preuve à l'appui. Une recherche sans résultat ne prouve pas l'absence d'offre adaptée partout. Une page bloquée ou une erreur ne constitue pas une recherche réussie avec zéro résultat.

Pour des offres réelles, conservez les liens datés et les informations qui justifient la configuration, les taxes, la livraison et les suppléments. Les liens `example.invalid` sont fictifs et ne constituent pas des preuves de vendeur.

[Note du projet](https://presque.digital/fr/journal/unknown-is-not-zero/) · [Disponibilité actuelle](https://presque.digital/fr/access/) · [Licence](../LICENSE.md)
