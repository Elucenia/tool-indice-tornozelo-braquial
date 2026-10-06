<!-- ELUCENIA technical documentation · indice-tornozelo-braquial · it · no clinical/professional/rights approval -->

# Indice caviglia-braccio (ABI)

[condizioni, fonti e autorizzazioni](https://elucenia.org/it/strumenti/indice-tornozelo-braquial)

## Come usare

Usi lo strumento nel portale oppure apra index.html tramite un server HTTP locale. Selezioni la lingua, compili i campi ed esegua il calcolo.

## Dati di ingresso e unità

### Pressione arteriosa sistolica del braccio destro

`bd`

mmHg · intervallo: 50–300

### Pressione arteriosa sistolica del braccio sinistro

`be`

mmHg · intervallo: 50–300

### Pressione sistolica maggiore alla caviglia destra (tibiale posteriore o pedidia)

`td`

mmHg · intervallo: 0–350

### Pressione sistolica maggiore alla caviglia sinistra (tibiale posteriore o pedidia)

`te`

mmHg · intervallo: 0–350

## Edizione del metodo

AHA 2012: ABI massima PAS alla caviglia/massima PAS brachiale; ABI minore tra le gambe

## Formula documentata

ABI di ogni gamba = massima pressione sistolica di quella caviglia ÷ massima pressione sistolica brachiale (tra le due braccia). L’ABI del paziente è il minore dei due lati.

## Limiti e popolazione

Calcolare ogni gamba usando la pressione sistolica più alta alla caviglia di quel lato e la pressione più alta dei due bracci; non usare una media di queste pressioni. Le arterie non comprimibili, frequenti nel diabete e nella malattia renale cronica, possono elevare falsamente l’indice e richiedere ulteriori valutazioni. Un valore normale a riposo non esclude ogni ischemia, e il solo indice può essere insufficiente nell’ischemia cronica minacciante l’arto. Lo strumento non sostituisce una tecnica di misurazione adeguata, i sintomi, l’esame vascolare o gli accertamenti complementari.

## Riferimenti

- [Aboyans V et al. Measurement and interpretation of the ankle-brachial index: a scientific statement from the American Heart Association. Circulation, 2012.](https://doi.org/10.1161/CIR.0b013e318276fbcb)

- [Gerhard-Herman MD et al. 2016 AHA/ACC Guideline on the Management of Patients With Lower Extremity Peripheral Artery Disease. Circulation, 2017.](https://doi.org/10.1161/CIR.0000000000000471)

- [AHA/ACC2024 lower-extremity PAD guideline](https://www.ahajournals.org/doi/full/10.1161/CIR.0000000000001251)

## Riprodurre i test tecnici

Esegua node test.cjs nella cartella principale di questo repository per ripetere i casi sintetici registrati. Gli input, i risultati attesi e le tolleranze originali sono conservati. I test tecnici non costituiscono validazione clinica.

```sh
node test.cjs
```

tool.json contiene le fonti, l’edizione e l’ambito della revisione. examples.json conserva gli input e i risultati attesi dei casi sintetici; results.json registra i risultati ottenuti.

[Scheda e riferimenti](../tool.json) · [Codice JavaScript](../calculator.js) · [Casi di riferimento](../examples.json) · [results.json](../results.json)

## Revisione e condizioni d’uso

Non è stata effettuata una revisione clinica indipendente.

Questa interfaccia è una traduzione realizzata dagli autori, non un’edizione ufficiale o certificata. Non sono state eseguite la revisione clinica indipendente, la revisione linguistica professionale né la verifica delle autorizzazioni relative ai diritti sugli strumenti.

Risultato della formula o classificazione. Interpretazione, condotta e applicabilità dipendono dalla valutazione professionale e dalla fonte selezionata.

## Licenza e attribuzione

Apache-2.0 si applica solo al codice di ELUCENIA. I diritti su strumenti, pubblicazioni, traduzioni e dati restano ai rispettivi titolari. Conservi LICENSE e NOTICE.

ELUCENIA · Felipe Guedes · Copyright © 2026

## Risultati documentati

Le informazioni seguenti conservano gli output del metodo per esempi sintetici. Non costituiscono una validazione clinica indipendente.

### 1

Classificazione: arteriopatia periferica lieve

| Dettagli del risultato | |
| --- | --- |
| ABI destro | 0,90 (arteriopatia periferica lieve) |
| ABI sinistro | 1,08 (normale) |
| Pressione brachiale utilizzata | 130 mmHg |


### 2

Arterie non comprimibili su almeno un lato: usare l’indice alluce-braccio

| Dettagli del risultato | |
| --- | --- |
| ABI destro | 1,50 (non comprimibile) |
| ABI sinistro | 1,08 (normale) |
| Pressione brachiale utilizzata | 120 mmHg |

