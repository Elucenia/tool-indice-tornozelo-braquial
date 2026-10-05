<!-- ELUCENIA technical documentation · indice-tornozelo-braquial · fr · no clinical/professional/rights approval -->

# Indice de pression systolique cheville-bras (IPS)

[conditions, sources et autorisations](https://elucenia.org/fr/outils/indice-tornozelo-braquial)

## Mode d’emploi

Utilisez l’outil sur le portail ou ouvrez index.html via un serveur HTTP local. Sélectionnez la langue, remplissez les champs et lancez le calcul.

## Données d’entrée et unités

### Pression artérielle systolique du bras droit

`bd`

mmHg · intervalle: 50–300

### Pression artérielle systolique du bras gauche

`be`

mmHg · intervalle: 50–300

### Pression systolique la plus élevée à la cheville droite (tibiale postérieure ou pédieuse)

`td`

mmHg · intervalle: 0–350

### Pression systolique la plus élevée à la cheville gauche (tibiale postérieure ou pédieuse)

`te`

mmHg · intervalle: 0–350

## Édition de la méthode

AHA 2012 : indice cheville-bras, PAS maximale à la cheville/PAS brachiale maximale ; indice le plus faible entre les jambes

## Formule documentée

Indice cheville-bras de chaque jambe = pression systolique la plus élevée de cette cheville ÷ pression systolique brachiale la plus élevée (entre les deux bras). L’indice du patient est le plus faible des deux côtés.

## Limites et population

Calculez pour chaque jambe le rapport entre la pression systolique la plus élevée à la cheville de ce côté et la pression la plus élevée des deux bras ; n’utilisez pas une moyenne de ces pressions. Les artères incompressibles, fréquentes dans le diabète et la maladie rénale chronique, peuvent augmenter artificiellement l’indice et nécessiter une évaluation supplémentaire. Une valeur normale au repos n’exclut pas toute ischémie, et l’indice isolé peut être insuffisant dans l’ischémie chronique menaçant le membre. L’outil ne remplace ni une technique de mesure appropriée, ni les symptômes, ni l’examen vasculaire, ni les tests complémentaires.

## Références

- [Aboyans V et al. Measurement and interpretation of the ankle-brachial index: a scientific statement from the American Heart Association. Circulation, 2012.](https://doi.org/10.1161/CIR.0b013e318276fbcb)

- [Gerhard-Herman MD et al. 2016 AHA/ACC Guideline on the Management of Patients With Lower Extremity Peripheral Artery Disease. Circulation, 2017.](https://doi.org/10.1161/CIR.0000000000000471)

- [AHA/ACC2024 lower-extremity PAD guideline](https://www.ahajournals.org/doi/full/10.1161/CIR.0000000000001251)

## Reproduire les tests techniques

Exécutez node test.cjs dans le répertoire racine de ce dépôt pour reproduire les cas synthétiques enregistrés. Les données d’entrée, les résultats attendus et les tolérances d’origine sont conservés. Les tests techniques ne constituent pas une validation clinique.

```sh
node test.cjs
```

tool.json contient les sources, l’édition et le périmètre de la revue. examples.json conserve les données d’entrée et les résultats attendus des cas synthétiques ; results.json consigne les résultats obtenus.

[Fiche et références](../tool.json) · [Code JavaScript](../calculator.js) · [Cas de référence](../examples.json) · [results.json](../results.json)

## Revue et conditions d’utilisation

Aucune révision clinique indépendante n’a été effectuée.

Cette interface est une traduction réalisée par nos soins, et non une édition officielle ou certifiée. La revue clinique indépendante, la révision linguistique professionnelle et l’autorisation des droits sur les instruments n’ont pas été réalisées.

Résultat de la formule ou de la classification. L’interprétation, la conduite et l’applicabilité dépendent de l’évaluation professionnelle et de la source sélectionnée.

## Licence et attribution

Apache-2.0 s’applique uniquement au code d’ELUCENIA. Les droits sur les instruments, publications, traductions et données restent ceux de leurs titulaires respectifs. Conservez LICENSE et NOTICE.

ELUCENIA · Felipe Guedes · Copyright © 2026
