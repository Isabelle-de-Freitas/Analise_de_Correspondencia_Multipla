# Análise de Correspondência Múltipla (MCA)

Definição: a análise de correspondência múltipla possui o intuito de analisar a associação entre mais de duas variáveis categóricas. Somente as variáveis que apresentam associação estatisticamente significativa participam da MCA.

O objetivo deste trabalho é realizar uma análise de correnpondência múltipla sobre dados de adaptação de estudantes ao ensino online, a fim de observar como as variáveis se associam e se essas associações são estatisticamente significativas.

Para isso, utilizamos o teste qui-quadrado, cujas hipóteses são:

 * $H_0$ : as variáveis se associam de forma aleatória (não há associação significativa).

 * $H_1$ : há associação significativa entre as variáveis (forma não aleatória).

Nesse caso, os graus de liberdade são dados pela seguinte fórmula:

(I - 1) * (J - 1),

em que I é a quantidade de categorias em linha e J, a quantidade de categorias em coluna.

Para validação, será definido um nível de significância de 5%.

## Estrutura do projeto

- Contexto
- Importação de bibliotecas e pacotes
- Leitura dos dados
- Análise descritiva
- Análise diagnóstica
- Análise de Correspondência Múltipla
- Mapa perceptual
- Conclusão

**Obs.:** o Mapa Perceptual não é plotado no notebook, pois ele utiliza um pacote (plotly.io) que abre o gráfico no browser.
