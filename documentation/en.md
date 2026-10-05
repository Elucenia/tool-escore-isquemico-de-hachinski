<!-- ELUCENIA technical documentation · escore-isquemico-de-hachinski · en · no clinical/professional/rights approval -->

# Hachinski Ischemic Score

[conditions, sources and permissions](https://elucenia.org/en/tools/escore-isquemico-de-hachinski)

## How to use

Use the tool in the portal or open index.html through a local HTTP server. Select the language, complete the fields and calculate.

## Inputs and units

### Abrupt onset

`abrupto`

### Stepwise deterioration

`degraus`

### Fluctuating course

`flutuante`

### Nocturnal confusion

`noturna`

### Relative preservation of personality

`personalidade`

### Depression

`depressao`

### Somatic complaints

`somaticas`

### Emotional incontinence (lability)

`labilidade`

### History of hypertension

`has`

### History of stroke

`avc`

### Evidence of associated atherosclerosis

`ateroscl`

### Focal neurological symptoms

`sintomas`

### Focal neurological signs

`sinais`

## Method edition

Hachinski 1975: 13 factors, total 0–18; not the reduced Rosen variant

## Documented formula

2 points: abrupt onset, fluctuating course, stroke history, focal symptoms, focal signs. 1 point: stepwise deterioration, nocturnal confusion, preserved personality, depression, somatic complaints, emotional lability, hypertension, atherosclerosis. Total: 0 to 18.

## Limits and population

Supports differentiation between degenerative and multi-infarct dementia. Performance was lower in mixed dementia. A score does not replace etiological assessment; published cutoffs belong to the populations and variants studied.

## References

- [Hachinski VC et al. Cerebral blood flow in dementia. Arch Neurol, 1975.](https://doi.org/10.1001/archneur.1975.00490510088009)

- [Moroney JT et al. Meta-analysis of the Hachinski Ischemic Score in pathologically verified dementias. Neurology, 1997.](https://doi.org/10.1212/WNL.49.4.1096)

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
