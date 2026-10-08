# Une question de brasserie, trois examens distincts

Par Presque.digital · 7 octobre 2026 · [English](brewery.en.md)

« Peut-on embouteiller ce brassin ? » doit préserver trois questions différentes. Il s'agit d'un exemple fictif de lecture des preuves, pas d'une liste réglementaire complète ni d'un résultat certifié.

| Examen | Pièces à relier | Lacune à laisser visible | Personne responsable |
| --- | --- | --- | --- |
| Préparation du brassin | Planning, notes et autorisation consignée | Une date prévue ne prouve pas que le brassin est prêt | Brasseur responsable du brassin |
| HACCP et traçabilité | Contrôles du plan propre à la brasserie, lots d'ingrédients et liens vers le brassin | Un résultat manquant ne peut pas devenir un contrôle réussi | Responsable de la sécurité alimentaire |
| Documents d'accises | Registre de brassage, stock de bière finie et mouvements pertinents | Une quantité non rapprochée ne peut pas devenir un chiffre de déclaration vérifié | Responsable de l'administration des accises |

## Exemple fictif

Pour un parcours plus complet et des modèles réutilisables, consulter [Documents de brasserie et décisions](https://presque.digital/fr/resources/brewery-records/) et les [outils publics de brasserie](../toolkit/fr/README.md).

Pour le [brassin fictif B-014](../examples/batch.json), l'embouteillage est prévu jeudi, mais aucune autorisation n'est consignée. Un contrôle de nettoyage prévu par le plan HACCP de la brasserie inventée n'a aucun résultat consigné. La quantité conditionnée n'est pas encore rapprochée du stock de bière finie.

Une réponse utile nomme chaque lacune, relie le document source et indique la personne responsable de l'examen. Le planning seul ne permet pas de confirmer que le brassin est prêt. Ces absences ne prouvent ni l'échec d'un contrôle ni des droits impayés. Cet exemple ne présente pas le contrôle de nettoyage comme un point critique universel.

Une validation sanitaire ne règle pas l'administration des accises ; une écriture d'accises ne prouve pas que le brassin est prêt sur le plan sanitaire. Dans le JSON, l'autorisation et le résultat manquants sont `null` ; le rapprochement des quantités a le statut distinct `not_reviewed`. Il s'agit de lacunes documentaires et d'examens à réaliser, pas de constats automatiques de non-conformité.

Pour un usage réel, conservez le plan applicable de la brasserie, les identifiants sources, les dates de consultation et les décisions consignées. Une lacune ne doit pas être remplacée par une réussite supposée ou une quantité inventée.

## Contexte et limites du projet

Les références officielles belges présentent [l'autocontrôle fondé sur les principes HACCP et la traçabilité](https://www.foodweb.favv-afsca.be/professionnels/autocontrole/default.asp), ainsi que [l'administration et les registres d'accises pour le brassage](https://finances.belgium.be/fr/douanes_accises/entreprises/accises/produits-soumis-%C3%A0-accise/alcool-et-boissons-alcoolis%C3%A9es/le). Ces liens ne rendent pas l'exemple exhaustif. Voir les [notes sur les sources](../SOURCES.md).

OBIA — Operon Brewery Intelligent Assistant — est en pilote privé. Son objectif est de relier les questions opérationnelles aux documents sources et de préparer un dossier de conformité candidat à examiner. Cet exemple ne démontre ni certification ni dépôt automatique des déclarations.

[Exemple illustratif](https://presque.digital/fr/journal/question-source-review/) · [Projet et limites actuelles](https://presque.digital/fr/work/obia/) · [Licence](../LICENSE.md)
