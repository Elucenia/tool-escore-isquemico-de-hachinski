<!-- ELUCENIA technical documentation · escore-isquemico-de-hachinski · pt-BR · no clinical/professional/rights approval -->

# Escore isquêmico de Hachinski

[condições, fontes e permissões](https://elucenia.org/pt-br/ferramentas/escore-isquemico-de-hachinski)

## Como usar

Use a ferramenta no portal ou abra index.html em um servidor HTTP local. Selecione o idioma, preencha os campos e calcule.

## Entradas e unidades

### Início abrupto

`abrupto`

### Deterioração em degraus

`degraus`

### Curso flutuante

`flutuante`

### Confusão noturna

`noturna`

### Preservação relativa da personalidade

`personalidade`

### Depressão

`depressao`

### Queixas somáticas

`somaticas`

### Incontinência (labilidade) emocional

`labilidade`

### História de hipertensão

`has`

### História de AVC

`avc`

### Evidência de aterosclerose associada

`ateroscl`

### Sintomas neurológicos focais

`sintomas`

### Sinais neurológicos focais

`sinais`

## Edição do método

Hachinski 1975:13 fatores, total 0–18; sem variante reduzida Rosen

## Fórmula documentada

2 pontos: início abrupto, curso flutuante, história de AVC, sintomas focais, sinais focais. 1 ponto: deterioração em degraus, confusão noturna, preservação da personalidade, depressão, queixas somáticas, labilidade emocional, hipertensão, aterosclerose. Total: 0 a 18.

## Limites e população

Apoio à diferenciação entre demência degenerativa e por múltiplos infartos. O desempenho foi inferior na demência mista. Uma pontuação não substitui avaliação etiológica; os cortes publicados pertencem às populações e variantes estudadas.

## Referências

- [Hachinski VC et al. Cerebral blood flow in dementia. Arch Neurol, 1975.](https://doi.org/10.1001/archneur.1975.00490510088009)

- [Moroney JT et al. Meta-analysis of the Hachinski Ischemic Score in pathologically verified dementias. Neurology, 1997.](https://doi.org/10.1212/WNL.49.4.1096)

## Reproduzir os testes técnicos

Execute node test.cjs na pasta raiz deste repositório para repetir os casos sintéticos registrados. As entradas, expectativas e tolerâncias originais são preservadas. Testes técnicos não constituem validação clínica.

```sh
node test.cjs
```

tool.json contém fontes, edição e escopo de revisão. examples.json conserva as entradas e expectativas sintéticas; results.json registra os resultados obtidos.

[Ficha e referências](../tool.json) · [Código JavaScript](../calculator.js) · [Casos de referência](../examples.json) · [results.json](../results.json)

## Revisão e condições de uso

Revisão clínica independente não realizada.

Esta interface é uma tradução autoral, não uma edição oficial ou certificada. Revisão clínica independente, revisão linguística profissional e autorização de direitos de instrumentos não foram realizadas.

Resultado da fórmula ou classificação. Interpretação, conduta e aplicabilidade dependem da avaliação profissional e da fonte selecionada.

## Licença e atribuição

Apache-2.0 aplica-se somente ao código da ELUCENIA. Os instrumentos, publicações, traduções e dados mantêm os direitos dos respectivos titulares. Preserve LICENSE e NOTICE.

ELUCENIA · Felipe Guedes · Copyright © 2026
