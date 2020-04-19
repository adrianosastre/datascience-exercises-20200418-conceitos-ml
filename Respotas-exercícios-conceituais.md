Respostas dos Exercícios Conceituais

1. Com suas palavras, forneça uma definição para a aprendizagem de máquina.

Diferentemente da abordagem tradicional de desenvolvimento de software onde algoritmos são programados para retornar resultados corretos de acordo com dados de entrada, a Aprendizagem de Máquina é uma área dentro da Inteligência Artificial, onde são fornecidos os dados de entrada e os resultados, e o sistema é responsável por encontrar o melhor algoritmo que retorne esses resultados.

2. Cite, pelo menos, três problemas reais nos quais técnicas de Machine Learning poderiam ser utilizadas.

a. Auxílio em diagnósticos de doenças, por exemplo câncer, dado imagens de entrada, por exemplo resultados de ressonância magnética, raios-x e/ou tomografia computadorizada. Um exemplo disso são APIs da empresa Varian, fabricantes de equipamentos LINEAC (aceleradores lineares) para tratamentos de radioterapia.
b. Reconhecimento de rostos e identificação de pessoas em imagens, como conversado em aula, em algoritmos do Google e Facebook.
c. Previsão do tempo, onde os dados históricos com as temperaturas e condições climáticas de diversas regiões podem ser dados de entrada para o treinamento de algoritmos de machine learning (aprendizagem supervisionada), para prever por exemplo temperaturas (regressão), ou dias de chuvas ou tempo seco (classificação).

3. Diferencie aprendizagem supervisionada da não supervisionada.

a. Na aprendizagem supervisionada, os dados de entrada e saída são sabidos de antemão, então técnicas e algoritmos de ML são utilizados para que, dados novos dados de entrada, os dados de saída sejam 'adivinhados'.
b. A aprendizagem não supervisionada geralmente é utilizada para identificar padrões, em bases de dados com muitas variáveis, onde não se sabe de antemão os dados de saída. Pode ser utilizada também para visualização e redução da dimensionalidade dos dados, ajudando assim na análise exploratória dos dados.

4. Qual o significado dos dados de treinamento rotulados (label traning dataset)?

Utilizados na aprendizagem supervisionada por classificação, os rótulos (labels) correspondem a identificações de certas propriedades ou características, classificando assim certos objetos do banco de dados.

5. Defina, com suas palavras, o que é um modelo de machine learning.

Um Modelo de ML é a combinação de determinada técnica (ex: Redes Neurais) com determinado algoritmo (ex: retro-propagação), possibilitando efetuar o treinamento desse modelo em um determinado banco de dados.

6. Que tipo de algoritmo de machine learning, em termos de categoria, poderia ser usado para segmentar clientes em múltiplos grupos?

Tipo: Aprendizagem Supervisionada por classficação.

7. Explique, com suas palavras, as principais diferenças entre aprendizagem online e offline

Em aprendizagem offline, o banco de dados de treinamento é fixo, e uma vez o modelo treinado, o mesmo é utilizado em novos dados, sem alterações.
Em aprendizagem online, a medida que novos dados são produzidos, o modelo é re-treinado.

8. Qual é a diferença entre os parâmetros e hiperparâmetros em um modelo de ML?

a. Um parâmetro é uma variável de configuração interna ao modelo, cujo valor pode ser estimado pelos dados. São parte do modelo aprendido pelos dados de treinamento.
b. Um hiperparâmetro é uma configuração externa ao modelo, cujo valor não pode ser estimado pelos dados de treinamento.

9. Explique a diferença entre os modos de aprendizagem que são baseados em modelos ou instâncias.

a. Baseado em modelos: As pressuposições sobre o domínio do problema são tratadas na forma de modelo matemático. Um modelo consiste em aplicar uma técnica (ex: rede neural) e um algoritmo (ex: retro-propagação) para resolução de um problema.
b. Baseado em instâncias: a generalização é realizada por métricas de similaridade (“aprende com as instâncias vizinhas”). Exemplo: KNN (K-nearest neighbor). Nesse caso, a "vizinhança" nem sempre é relacionada à distância física, podem existir várias variáveis a serem utilizadas.

10. Se um modelo de ML atinge um bom desempenho sobre os dados de treinamento, mas não generaliza bem para novos dados (teste), o que pode estar acontecendo? O que poderia ser realizado para melhorar a generalização do modelo de ML?

Nesse caso, o modelo foi super treinado ("passou do ponto") para os dados de treinamento. 
Para melhorar a generalização desse modelo, as seguintes abordagens poderiam ser aplicadas:
- Verificar se os dados de treinamento consistem em amostras de todos os tipos de dados reais,
- Aplicar corretamente as diferenças entre dados de treino e de teste (ex: 80% / 20%), ou treino/validação/teste (ex: 80% / 10% / 10%),
- Verificar todas as métricas de desempenho resultado do modelo, todas são importantes (no exemplo da aula, para classificação, pode ser que a taxa de acurácia esteja alta, porém as de erro / recall / precisão estejam baixas).
