# Credit Scoring - Curso do Alura
- **Plataforma do curso**: Alura
- **Instrutora**: Karol Penteado
- **Data Info**: Statlog (German Credit Data) DataSet
- **Data [link](https://archive.ics.uci.edu/ml/datasets/statlog+(german+credit+data))**

## Modelagem
- O Credit Scoring é um modelo estatístico multivariado que cria um modelo matemático e estima, através de uma probabilidade, a chance do nosso cliente ser adimplente ou inadimplente

```python
-------------------------------------------------------------------------
| cliente ---empréstimo---> banco ---negar/conceder?---> credit scoring |
-------------------------------------------------------------------------
```

- Existem alguns algoritmos que são capazes de fazer essa classificação, por exemplo: a regressão logística, o random forest, Naive Bayes, support vector machine.

- A princípio, vamos começar aplicando o modelo de classificação, **regressão logística**. 

- A **regressão logística** consiste em uma técnica muito usada no sistema financeiro. 

- Este modelo possui um alto comprometimento com a explicabilidade. Nós conseguimos acompanhar muito bem as variáveis ao longo do tempo, conseguimos replicar muito bem esse modelo e isso é bom para fins de fiscalização, além do baixo custo computacional.

- No sistema financeiro nós não analisamos **o indivíduo**.

- A análise é direcionada para o comportamento de um grupo, portanto, ajustamos o indivíduo dentro de um dos grupos
