<!-- ELUCENIA technical documentation · escore-isquemico-de-hachinski · it · no clinical/professional/rights approval -->

# Punteggio ischemico di Hachinski

[condizioni, fonti e autorizzazioni](https://elucenia.org/it/strumenti/escore-isquemico-de-hachinski)

## Come usare

Usi lo strumento nel portale oppure apra index.html tramite un server HTTP locale. Selezioni la lingua, compili i campi ed esegua il calcolo.

## Dati di ingresso e unità

### Esordio improvviso

`abrupto`

### Deterioramento a gradini

`degraus`

### Decorso fluttuante

`flutuante`

### Confusione notturna

`noturna`

### Conservazione relativa della personalità

`personalidade`

### Depressione

`depressao`

### Disturbi somatici

`somaticas`

### Incontinenza (labilità) emotiva

`labilidade`

### Anamnesi di ipertensione

`has`

### Anamnesi di ictus

`avc`

### Evidenza di aterosclerosi associata

`ateroscl`

### Sintomi neurologici focali

`sintomas`

### Segni neurologici focali

`sinais`

## Edizione del metodo

Hachinski 1975: 13 fattori, totale 0–18; non la variante ridotta di Rosen

## Formula documentata

2 punti: esordio improvviso, decorso fluttuante, ictus pregresso, sintomi focali, segni focali. 1 punto: deterioramento a gradini, confusione notturna, personalità preservata, depressione, disturbi somatici, labilità emotiva, ipertensione, aterosclerosi. Totale: 0 a 18.

## Limiti e popolazione

Supporta la distinzione tra demenza degenerativa e multi-infartuale. Le prestazioni erano inferiori nella demenza mista. Un punteggio non sostituisce la valutazione eziologica; le soglie pubblicate appartengono alle popolazioni e alle varianti studiate.

## Riferimenti

- [Hachinski VC et al. Cerebral blood flow in dementia. Arch Neurol, 1975.](https://doi.org/10.1001/archneur.1975.00490510088009)

- [Moroney JT et al. Meta-analysis of the Hachinski Ischemic Score in pathologically verified dementias. Neurology, 1997.](https://doi.org/10.1212/WNL.49.4.1096)

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
