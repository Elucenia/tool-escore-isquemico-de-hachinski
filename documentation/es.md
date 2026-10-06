<!-- ELUCENIA technical documentation · escore-isquemico-de-hachinski · es · no clinical/professional/rights approval -->

# Puntuación isquémica de Hachinski

[condiciones, fuentes y permisos](https://elucenia.org/es/herramientas/escore-isquemico-de-hachinski)

## Cómo usar

Utilice la herramienta en el portal o abra index.html mediante un servidor HTTP local. Seleccione el idioma, complete los campos y calcule.

## Entradas y unidades

### Inicio abrupto

`abrupto`

### Deterioro escalonado

`degraus`

### Curso fluctuante

`flutuante`

### Confusión nocturna

`noturna`

### Conservación relativa de la personalidad

`personalidade`

### Depresión

`depressao`

### Quejas somáticas

`somaticas`

### Incontinencia (labilidad) emocional

`labilidade`

### Antecedentes de hipertensión

`has`

### Antecedentes de ictus

`avc`

### Evidencia de aterosclerosis asociada

`ateroscl`

### Síntomas neurológicos focales

`sintomas`

### Signos neurológicos focales

`sinais`

## Edición del método

Hachinski 1975: 13 factores, total 0–18; no variante reducida de Rosen

## Fórmula documentada

2 puntos: inicio brusco, curso fluctuante, ictus previo, síntomas focales, signos focales. 1 punto: deterioro escalonado, confusión nocturna, personalidad preservada, depresión, quejas somáticas, labilidad emocional, hipertensión, aterosclerosis. Total: 0 a 18.

## Límites y población

Apoya la diferenciación entre demencia degenerativa y por múltiples infartos. El rendimiento fue inferior en la demencia mixta. Una puntuación no sustituye la evaluación etiológica; los puntos de corte publicados pertenecen a las poblaciones y variantes estudiadas.

## Referencias

- [Hachinski VC et al. Cerebral blood flow in dementia. Arch Neurol, 1975.](https://doi.org/10.1001/archneur.1975.00490510088009)

- [Moroney JT et al. Meta-analysis of the Hachinski Ischemic Score in pathologically verified dementias. Neurology, 1997.](https://doi.org/10.1212/WNL.49.4.1096)

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

Sugiere demencia degenerativa primaria (≤ 4 puntos)

No excluye un componente vascular asociado: verifique la neuroimagen.


### 2

Rango intermedio (5 a 6 puntos): posible demencia mixta


### 3

Sugiere demencia vascular (≥ 7 puntos)

Confirmar con neuroimagen (infartos, enfermedad de pequeños vasos).

