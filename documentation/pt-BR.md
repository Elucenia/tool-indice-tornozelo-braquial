<!-- ELUCENIA technical documentation · indice-tornozelo-braquial · pt-BR · no clinical/professional/rights approval -->

# Índice tornozelo-braquial (ITB)

[condições, fontes e permissões](https://elucenia.org/pt-br/ferramentas/indice-tornozelo-braquial)

## Como usar

Use a ferramenta no portal ou abra index.html em um servidor HTTP local. Selecione o idioma, preencha os campos e calcule.

## Entradas e unidades

### PAS braço direito

`bd`

mmHg · intervalo: 50–300

### PAS braço esquerdo

`be`

mmHg · intervalo: 50–300

### Maior PAS do tornozelo direito (tibial posterior ou pediosa)

`td`

mmHg · intervalo: 0–350

### Maior PAS do tornozelo esquerdo (tibial posterior ou pediosa)

`te`

mmHg · intervalo: 0–350

## Edição do método

AHA 2012:ITBmaior PAS tornozelo/maior PASbraquial; menor ITB entre pernas

## Fórmula documentada

ITB de cada perna = maior pressão sistólica daquele tornozelo ÷ maior pressão sistólica braquial (entre os dois braços). O ITB do paciente é o menor dos dois lados.

## Limites e população

Calcule cada perna com a maior pressão sistólica do tornozelo daquele lado e a maior pressão dos dois braços; não use uma média dessas pressões. Artérias não compressíveis, frequentes em diabetes e doença renal crônica, podem elevar falsamente o índice e exigir avaliação adicional. Um valor de repouso normal não exclui toda isquemia, e o índice isolado pode ser insuficiente na isquemia crônica ameaçadora do membro. A ferramenta não substitui técnica adequada de medida, sintomas, exame vascular ou testes complementares.

## Referências

- [Aboyans V et al. Measurement and interpretation of the ankle-brachial index: a scientific statement from the American Heart Association. Circulation, 2012.](https://doi.org/10.1161/CIR.0b013e318276fbcb)

- [Gerhard-Herman MD et al. 2016 AHA/ACC Guideline on the Management of Patients With Lower Extremity Peripheral Artery Disease. Circulation, 2017.](https://doi.org/10.1161/CIR.0000000000000471)

- [AHA/ACC2024 lower-extremity PAD guideline](https://www.ahajournals.org/doi/full/10.1161/CIR.0000000000001251)

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

## Resultados documentados

As informações abaixo preservam as saídas do método para exemplos sintéticos. Não constituem validação clínica independente.

### 1

Classificação: DAOP leve

| Detalhes do resultado | |
| --- | --- |
| ITB direito | 0,90 (DAOP leve) |
| ITB esquerdo | 1,08 (normal) |
| Pressão braquial usada | 130 mmHg |


### 2

Artérias não compressíveis em pelo menos um lado: use o índice hálux-braquial

| Detalhes do resultado | |
| --- | --- |
| ITB direito | 1,50 (não compressível) |
| ITB esquerdo | 1,08 (normal) |
| Pressão braquial usada | 120 mmHg |

