<!-- ELUCENIA technical documentation · indice-tornozelo-braquial · es · no clinical/professional/rights approval -->

# Índice tobillo-brazo (ITB)

[condiciones, fuentes y permisos](https://elucenia.org/es/herramientas/indice-tornozelo-braquial)

## Cómo usar

Utilice la herramienta en el portal o abra index.html mediante un servidor HTTP local. Seleccione el idioma, complete los campos y calcule.

## Entradas y unidades

### Presión arterial sistólica del brazo derecho

`bd`

mmHg · intervalo: 50–300

### Presión arterial sistólica del brazo izquierdo

`be`

mmHg · intervalo: 50–300

### Mayor presión sistólica del tobillo derecho (tibial posterior o pedia)

`td`

mmHg · intervalo: 0–350

### Mayor presión sistólica del tobillo izquierdo (tibial posterior o pedia)

`te`

mmHg · intervalo: 0–350

## Edición del método

AHA 2012: ITB mayor PAS del tobillo/mayor PAS braquial; menor ITB entre piernas

## Fórmula documentada

ITB de cada pierna = mayor presión sistólica de ese tobillo ÷ mayor presión sistólica braquial (entre los dos brazos). El ITB del paciente es el menor de los dos lados.

## Límites y población

Calcule cada pierna con la mayor presión sistólica del tobillo de ese lado y la mayor presión de los dos brazos; no utilice una media de esas presiones. Las arterias no compresibles, frecuentes en la diabetes y la enfermedad renal crónica, pueden elevar falsamente el índice y exigir una evaluación adicional. Un valor normal en reposo no excluye toda isquemia, y el índice aislado puede ser insuficiente en la isquemia crónica amenazante de la extremidad. La herramienta no sustituye la técnica adecuada de medición, los síntomas, la exploración vascular ni las pruebas complementarias.

## Referencias

- [Aboyans V et al. Measurement and interpretation of the ankle-brachial index: a scientific statement from the American Heart Association. Circulation, 2012.](https://doi.org/10.1161/CIR.0b013e318276fbcb)

- [Gerhard-Herman MD et al. 2016 AHA/ACC Guideline on the Management of Patients With Lower Extremity Peripheral Artery Disease. Circulation, 2017.](https://doi.org/10.1161/CIR.0000000000000471)

- [AHA/ACC2024 lower-extremity PAD guideline](https://www.ahajournals.org/doi/full/10.1161/CIR.0000000000001251)

## Reproducir las pruebas técnicas

Ejecute node test.cjs en el directorio raíz de este repositorio para repetir los casos sintéticos registrados. Se conservan las entradas, los resultados esperados y las tolerancias originales. Las pruebas técnicas no constituyen validación clínica.

```sh
node test.cjs
```

tool.json contiene las fuentes, la edición y el alcance de la revisión. examples.json conserva las entradas y los resultados esperados de los casos sintéticos; results.json registra los resultados obtenidos.

[Ficha y referencias](../tool.json) · [Código JavaScript](../calculator.js) · [Casos de referencia](../examples.json) · [results.json](../results.json)

## Revisión y condiciones de uso

No se ha realizado una revisión clínica independiente.

Esta interfaz es una traducción de elaboración propia, no una edición oficial o certificada. No se han realizado la revisión clínica independiente, la revisión lingüística profesional ni la autorización de derechos de los instrumentos.

Resultado de la fórmula o clasificación. La interpretación, la conducta y la aplicabilidad dependen de la evaluación profesional y de la fuente seleccionada.

## Licencia y atribución

Apache-2.0 se aplica únicamente al código de ELUCENIA. Los derechos de los instrumentos, publicaciones, traducciones y datos permanecen en manos de sus respectivos titulares. Conserve LICENSE y NOTICE.

ELUCENIA · Felipe Guedes · Copyright © 2026

## Resultados documentados

La información siguiente conserva las salidas del método para ejemplos sintéticos. No constituye una validación clínica independiente.

### 1

Clasificación: EAP leve

| Detalles del resultado | |
| --- | --- |
| ITB derecho | 0,90 (EAP leve) |
| ITB izquierdo | 1,08 (normal) |
| Presión braquial utilizada | 130 mmHg |


### 2

Arterias no compresibles en al menos un lado: use el índice dedo del pie-braquial

| Detalles del resultado | |
| --- | --- |
| ITB derecho | 1,50 (no compresible) |
| ITB izquierdo | 1,08 (normal) |
| Presión braquial utilizada | 120 mmHg |

