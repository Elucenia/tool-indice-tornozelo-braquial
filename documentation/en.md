<!-- ELUCENIA technical documentation · indice-tornozelo-braquial · en · no clinical/professional/rights approval -->

# Ankle–brachial index (ABI)

[conditions, sources and permissions](https://elucenia.org/en/tools/indice-tornozelo-braquial)

## How to use

Use the tool in the portal or open index.html through a local HTTP server. Select the language, complete the fields and calculate.

## Inputs and units

### Right-arm systolic blood pressure

`bd`

mmHg · range: 50–300

### Left-arm systolic blood pressure

`be`

mmHg · range: 50–300

### Higher right ankle systolic pressure (posterior tibial or dorsalis pedis)

`td`

mmHg · range: 0–350

### Higher left ankle systolic pressure (posterior tibial or dorsalis pedis)

`te`

mmHg · range: 0–350

## Method edition

AHA 2012: ABI highest ankle SBP/highest brachial SBP; lower ABI between legs

## Documented formula

ABI of each leg = highest systolic pressure at that ankle ÷ highest brachial systolic pressure (between both arms). The patient’s ABI is the lower of the two sides.

## Limits and population

Calculate each leg using the higher ankle systolic pressure on that side and the higher pressure from the two arms; do not use an average of these pressures. Noncompressible arteries, common in diabetes and chronic kidney disease, can falsely elevate the index and require further assessment. A normal resting value does not exclude all ischemia, and the index alone may be insufficient in chronic limb-threatening ischemia. The tool does not replace proper measurement technique, symptoms, vascular examination or complementary tests.

## References

- [Aboyans V et al. Measurement and interpretation of the ankle-brachial index: a scientific statement from the American Heart Association. Circulation, 2012.](https://doi.org/10.1161/CIR.0b013e318276fbcb)

- [Gerhard-Herman MD et al. 2016 AHA/ACC Guideline on the Management of Patients With Lower Extremity Peripheral Artery Disease. Circulation, 2017.](https://doi.org/10.1161/CIR.0000000000000471)

- [AHA/ACC2024 lower-extremity PAD guideline](https://www.ahajournals.org/doi/full/10.1161/CIR.0000000000001251)

## Reproduce the technical tests

Run node test.cjs in the root directory of this repository to repeat the recorded synthetic cases. Original inputs, expectations and tolerances are preserved. Technical tests do not constitute clinical validation.

```sh
node test.cjs
```

tool.json contains sources, edition and review scope. examples.json retains synthetic inputs and expectations; results.json records the obtained results.

[Record and references](../tool.json) · [JavaScript code](../calculator.js) · [Reference cases](../examples.json) · [results.json](../results.json)

## Review and conditions of use

Independent clinical review has not been performed.

This interface is an authorial translation, not an official or certified edition. Independent clinical review, professional language review and instrument rights clearance have not been performed.

Formula or classification result. Interpretation, care and applicability depend on professional assessment and the selected source.

## License and attribution

Apache-2.0 applies only to ELUCENIA code. Rights to instruments, publications, translations and data remain with their respective holders. Preserve LICENSE and NOTICE.

ELUCENIA · Felipe Guedes · Copyright © 2026

## Documented results

The information below preserves the method outputs for synthetic examples. It does not constitute independent clinical validation.

### 1

Classification: mild PAD

| Result details | |
| --- | --- |
| Right ABI | 0.90 (mild PAD) |
| Left ABI | 1.08 (normal) |
| Brachial pressure used | 130 mmHg |


### 2

Non-compressible arteries on at least one side: use the toe-brachial index

| Result details | |
| --- | --- |
| Right ABI | 1.50 (non-compressible) |
| Left ABI | 1.08 (normal) |
| Brachial pressure used | 120 mmHg |

