<!-- ELUCENIA technical documentation · indice-tornozelo-braquial · de · no clinical/professional/rights approval -->

# Knöchel-Arm-Index (ABI)

[Bedingungen, Quellen und Berechtigungen](https://elucenia.org/de/werkzeuge/indice-tornozelo-braquial)

## Verwendung

Verwenden Sie das Werkzeug im Portal oder öffnen Sie index.html über einen lokalen HTTP-Server. Wählen Sie die Sprache, füllen Sie die Felder aus und berechnen Sie das Ergebnis.

## Eingaben und Einheiten

### Systolischer Blutdruck am rechten Arm

`bd`

mmHg · Bereich: 50–300

### Systolischer Blutdruck am linken Arm

`be`

mmHg · Bereich: 50–300

### Höchster systolischer Druck am rechten Knöchel (A. tibialis posterior oder A. dorsalis pedis)

`td`

mmHg · Bereich: 0–350

### Höchster systolischer Druck am linken Knöchel (A. tibialis posterior oder A. dorsalis pedis)

`te`

mmHg · Bereich: 0–350

## Fassung der Methode

AHA 2012: ABI höchster Knöchel-SBD/höchster Oberarm-SBD; niedrigerer ABI beider Beine

## Dokumentierte Formel

ABI jedes Beins = höchster systolischer Druck an diesem Knöchel ÷ höchster systolischer Oberarmdruck (aus beiden Armen). Der ABI des Patienten ist der niedrigere der beiden Seiten.

## Grenzen und Population

Berechnen Sie den Index für jedes Bein mit dem höheren systolischen Knöcheldruck dieser Seite und dem höheren Druck der beiden Arme; verwenden Sie keinen Mittelwert dieser Drücke. Nicht komprimierbare Arterien, die bei Diabetes und chronischer Nierenkrankheit häufig vorkommen, können den Index fälschlich erhöhen und eine zusätzliche Beurteilung erfordern. Ein normaler Ruhewert schließt nicht jede Ischämie aus, und der Index allein kann bei chronischer gliedmaßenbedrohender Ischämie unzureichend sein. Das Werkzeug ersetzt weder eine geeignete Messtechnik noch Symptome, Gefäßuntersuchung oder ergänzende Tests.

## Referenzen

- [Aboyans V et al. Measurement and interpretation of the ankle-brachial index: a scientific statement from the American Heart Association. Circulation, 2012.](https://doi.org/10.1161/CIR.0b013e318276fbcb)

- [Gerhard-Herman MD et al. 2016 AHA/ACC Guideline on the Management of Patients With Lower Extremity Peripheral Artery Disease. Circulation, 2017.](https://doi.org/10.1161/CIR.0000000000000471)

- [AHA/ACC2024 lower-extremity PAD guideline](https://www.ahajournals.org/doi/full/10.1161/CIR.0000000000001251)

## Technische Tests reproduzieren

Führen Sie node test.cjs im Stammverzeichnis dieses Repositorys aus, um die dokumentierten synthetischen Fälle zu wiederholen. Ursprüngliche Eingaben, erwartete Ergebnisse und Toleranzen bleiben erhalten. Technische Tests stellen keine klinische Validierung dar.

```sh
node test.cjs
```

tool.json enthält Quellen, Ausgabe und Umfang der Überprüfung. examples.json bewahrt die synthetischen Eingaben und erwarteten Ergebnisse; results.json dokumentiert die tatsächlich erhaltenen Ergebnisse.

[Eintrag und Referenzen](../tool.json) · [JavaScript-Code](../calculator.js) · [Referenzfälle](../examples.json) · [results.json](../results.json)

## Überprüfung und Nutzungsbedingungen

Eine unabhängige klinische Prüfung wurde nicht durchgeführt.

Diese Benutzeroberfläche ist eine selbst erstellte Übersetzung und keine offizielle oder zertifizierte Ausgabe. Eine unabhängige klinische Überprüfung, eine professionelle sprachliche Prüfung und eine Klärung der Rechte an den Instrumenten wurden nicht durchgeführt.

Ergebnis der Formel oder Klassifikation. Interpretation, Vorgehen und Anwendbarkeit hängen von der fachlichen Beurteilung und der ausgewählten Quelle ab.

## Lizenz und Urheberangaben

Apache-2.0 gilt nur für den ELUCENIA-Code. Die Rechte an Instrumenten, Veröffentlichungen, Übersetzungen und Daten verbleiben bei den jeweiligen Rechteinhabern. Bewahren Sie LICENSE und NOTICE auf.

ELUCENIA · Felipe Guedes · Copyright © 2026
