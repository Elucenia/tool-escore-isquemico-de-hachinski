<!-- ELUCENIA technical documentation · escore-isquemico-de-hachinski · de · no clinical/professional/rights approval -->

# Hachinski-Ischämie-Score

[Bedingungen, Quellen und Berechtigungen](https://elucenia.org/de/werkzeuge/escore-isquemico-de-hachinski)

## Verwendung

Verwenden Sie das Werkzeug im Portal oder öffnen Sie index.html über einen lokalen HTTP-Server. Wählen Sie die Sprache, füllen Sie die Felder aus und berechnen Sie das Ergebnis.

## Eingaben und Einheiten

### Abrupter Beginn

`abrupto`

### Stufenweise Verschlechterung

`degraus`

### Fluktuierender Verlauf

`flutuante`

### Nächtliche Verwirrtheit

`noturna`

### Relative Erhaltung der Persönlichkeit

`personalidade`

### Depression

`depressao`

### Somatische Beschwerden

`somaticas`

### Emotionale Inkontinenz (Labilität)

`labilidade`

### Hypertonie in der Anamnese

`has`

### Schlaganfall in der Anamnese

`avc`

### Hinweise auf begleitende Atherosklerose

`ateroscl`

### Fokale neurologische Symptome

`sintomas`

### Fokale neurologische Zeichen

`sinais`

## Fassung der Methode

Hachinski 1975: 13 Faktoren, Gesamt 0–18; keine verkürzte Rosen-Variante

## Dokumentierte Formel

2 Punkte: abrupter Beginn, fluktuierender Verlauf, Schlaganfallanamnese, fokale Symptome, fokale Zeichen. 1 Punkt: stufenweise Verschlechterung, nächtliche Verwirrtheit, erhaltene Persönlichkeit, Depression, somatische Beschwerden, emotionale Labilität, Hypertonie, Atherosklerose. Gesamt: 0 bis 18.

## Grenzen und Population

Unterstützt die Unterscheidung degenerativer Demenz von Multiinfarktdemenz. Bei gemischter Demenz war die Leistung geringer. Eine Punktzahl ersetzt keine ätiologische Beurteilung; veröffentlichte Schwellen gehören zu den untersuchten Populationen und Varianten.

## Referenzen

- [Hachinski VC et al. Cerebral blood flow in dementia. Arch Neurol, 1975.](https://doi.org/10.1001/archneur.1975.00490510088009)

- [Moroney JT et al. Meta-analysis of the Hachinski Ischemic Score in pathologically verified dementias. Neurology, 1997.](https://doi.org/10.1212/WNL.49.4.1096)

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

## Dokumentierte Ergebnisse

Die folgenden Angaben bewahren die Ausgaben der Methode für synthetische Beispiele. Sie stellen keine unabhängige klinische Validierung dar.

### 1

Spricht für eine primär degenerative Demenz (≤ 4 Punkte)

Schließt einen begleitenden vaskulären Anteil nicht aus: Neurobildgebung prüfen.


### 2

Intermediärer Bereich (5 bis 6 Punkte): mögliche Mischdemenz


### 3

Spricht für eine vaskuläre Demenz (≥ 7 Punkte)

Mit Neurobildgebung bestätigen (Infarkte, Erkrankung der kleinen Gefäße).

