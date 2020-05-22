Respostas dos Exercícios de Múltipla Escolha

1. Exercício 1 (Fundamentos de Machine Learning)
Considere um algoritmo de aprendizagem de máquina que interpreta marcações de e-mail (spam ou não spam) realizadas por um usuário. Baseado nesta observação, o algoritmo aprende a filtrar os e-mails de forma mais eficaz. Neste caso, a tarefa T da definição de aprendizagem de máquina consiste em

(X) a) Classificar um e-mail como spam ou não spam.
( ) b) Observar as marcações de e-mail como spam ou não spam.
( ) c) O número ou razão de e-mails corretamente classificados como spam ou não spam.
( ) d) Não é possível aplicar aprendizagem de máquina neste caso do enunciado.


2. Exercício 2 (Fundamentos de Machine Learning)
Considere um algoritmo de aprendizagem de máquina que interpreta marcações de e-mail (spam ou não spam) realizadas por um usuário. Baseado nesta observação, o algoritmo aprende a filtrar os e-mails de forma mais eficaz. Neste caso, a métrica P da definição de aprendizagem de máquina consiste em

( ) a) Classificar um e-mail como spam ou não spam.
( ) b) Observar as marcações de e-mail como spam ou não spam.
(X) c) O número ou razão de e-mails corretamente classificados como spam ou não spam.
( ) d) Não é possível aplicar aprendizagem de máquina neste caso do enunciado.


3. Exercício 3 (Fundamentos de Machine Learning)
Considere um algoritmo de aprendizagem de máquina que interpreta marcações de e-mail (spam ou não spam) realizadas por um usuário. Baseado nesta observação, o algoritmo aprende a filtrar os e-mails de forma mais eficaz. Neste caso, a experiência E da definição de aprendizagem de máquina consiste em

( ) a) Classificar um e-mail como spam ou não spam.
(X) b) Observar as marcações de e-mail como spam ou não spam.
( ) c) O número ou razão de e-mails corretamente classificados como spam ou não spam.
( ) d) Não é possível aplicar aprendizagem de máquina neste caso do enunciado.

4. Exercício 4 (Métricas de Desempenho)
A avaliação de performance ou desempenho de modelos de machine learning é um ponto de relevância e, de fato, temos uma etapa de avaliação que pode fazer parte de um projeto de ciência de dados. Uma métrica amplamente conhecida na literatura é colocada abaixo:

Sobre a interpretação dessa métrica de desempenho, marque a alternativa correta:

( ) a) A aplicação da métrica MSE só ocorre na aprendizagem não supervisionada.
( ) b) Na equação, o termo yi consiste na i-ésima estimativa do modelo de ML.
(X) c) Só é possível estimar, empiricamente, o MSE para o conjunto de treinamento.
( ) d) Quanto maior é o valor do MSE, pior será o desempenho do modelo de ML avaliado.


5. Exercício 5 (Métricas de Desempenho)
As Figuras (a) e (b) abaixo, extraídas do livro An Introduction to Statistical Learning, discutem a relação entre o MSEtrein e MSEtest, ou seja, o desempenho dos modelos de ML nas fases de treinamento e teste. Sobre tal relação, marque a alternativa correta:

( ) a) A razão pela qual o MSEtest não segue o decaimento do MSEtrein reside na falha de generalização do modelo smoothing splines utilizado.
( ) b) O comportamento em "U" para curva do MSEtest ocorre porque a função hipótese verdadeira é do tipo não linear.
( ) c) Nota-se que existe uma garantia de performance de teste (i.e., baixo MSEtest) se nós ajustarmos o modelo de ML com os dados de treinamento.
(X) d) A diferença entre MSEtrein e MSEtest é explicada pelo fato de que o processo de aprendizagem das técnicas de ML se baseia na minimização do MSEtrein e, por conta disso, não pode garantir ótima generalização para os dados de teste (i.e., baixo MSEtest).


6. Exercício 6 (Técnicas de ML)
No estudo de machine learning, realizar a associação de técnicas de aprendizagem de máquina de acordo com o supervisionamento aplicado no processo de treinamento do modelo é um aspecto importante. Sobre esse tópico, marquea alternativa correta:

( ) a) O algoritmo K-Nearest Neighbors ou K-Vizinhos mais próximos pode ser aplicado em problemas somente de forma não supervisionada.
( ) b) Não existe uma relação entre os algoritmos - Árvores de Decisão (Decision Threes) e Florestas Aleatórias (Random Forests).
( ) c) Redes neurais artificiais podem ser usadas em problemas considerando a aprendizagem supervisionada e não supervisionada.
( ) d) A análise de componentes principais (PCA) é uma técnica supervisionada de aprendizagem de máquina.

7. Exercício 7 (Desempenho de Classificadores)

Um hospital conta com uma equipe de pesquisadores em ciência de dados e inteligência artificial, avaliando diversos classificadores construídos para análise de problemas pulmonares dos pacientes. O objetivo consiste em levantar a performance dos classificadores para compreender, adotar e posteriormente testar os melhores modelos treinados. Cada classificador atua para apontar riscos de doenças pulmonares em futuros pacientes, isto é, o resultado da aplicação de modelo de ML aponta a presença ou ausência de risco de doença pulmonar de um determinado paciente que dá entrada no hospital com sintomas relacionados à parte respiratória-pulmonar*.

O exemplo abaixo consiste nos resultados de desempenho sobre o treinamento de um classificador construído a partir de centenas de imagens médicas pulmonares armazenadas no banco de dados de um hospital.

Matriz de Resultados de Treinamento do Classificador
Predição do Classificador
            Risco presente Risco ausente
Realidade
            Risco presente VP = 100 FN = 70
            Risco ausente FP = 150 VN = 1200


Considerando as informações apresentadas, marque a alternativa correta:

(X) a) A acurácia do classificador é 85%, caracterizando o desempenho de forma completa.
( ) b) A precisão calculada permite dizer que o classificador tem alto desempenho.
( ) c) O desbalanceamento dos dados, especialmente com a quantidade de pacientes sem risco, aumenta a acurácia do modelo.
( ) d) Falsos positivos e negativos têm impacto equivalente sobre o suporte às decisões dos resultados do classificador.

8. Exercício 8 (Técnicas de ML)

Alguns livros de ML trazem a informação de que a aprendizagem não supervisionada é
desafiadora, no comparativo com o treinamento de modelo de forma supervisionada. Claro, o
treinamento de um modelo não supervisionado ocorre de modo diferente pelo simples fato de
não possuirmos dados rotulados com as saídas conhecidas. Nesse sentido, a aprendizagem
não supervisionada é conduzida como parte da análise exploratória de dados e uma das
técnicas mais conhecidas da aprendizagem estatística é a análise de componentes principais,
PCA - Principal Component Analysis.

Marque a alternativa que descreve corretamente qual é o conceito fundamental da PCA:

(X) a) A PCA é uma técnica de aprendizagem de máquina não supervisionada e se refere a
um processo de cômputo dos componentes principais de um grupo maior de variáveis
(características), permitindo descrever a variabilidade estatística contida nos dados com
um grupo menor de variáveis.
( ) b) PCA é uma técnica de aprendizagem semisupervisionada e se refere a um processo
de aglomeração de variáveis a partir de um conjunto menor de características, chamadas
de componentes principais.
( ) c) A PCA é uma técnica de aprendizagem não supervisionada e se refere ao processo de
predição de variáveis ou características de interesse, a partir de componentes principais
não ortogonais entre si.
( ) d) A PCA é uma técnica de aprendizagem não supervisionada e se refere a um processo
de visualização de dados para que todas as dimensões e características possam ser
analisadas por meio de gráficos de correlação entre todas as variáveis.

9. Exercício 9 (Modos de Aprendizagem)

Na categoria modos de aprendizagem, marque a alternativa que descreve corretamente qual
é a diferença de generalização entre modo de aprendizagem baseado em instâncias e modelos:

( ) a) Ambos os modos de aprendizagem, baseados em instâncias e modelos, se fundamentam
apenas em métricas de similaridade.
– Na classificação de um potencial motorista para os serviços de corrida (aplicativos de
transporte privado como Uber) as distâncias entre as coordenadas de localização de uma
pessoa (por meio de seu smarphone) e os potenciais motoristas são um exemplo de
informação que pode ser incluída no cálculo de métricas de similaridade.
(X) b) Na aprendizagem baseada em instâncias a generalização realizada pelo modelo de
ML é baseada em métricas de similaridade, enquanto a aprendizagem baseada em
modelos formula equações matemáticas que são usadas para fazer a generalização.
– Na classificação de um potencial motorista para os serviços de corrida (aplicativos de
transporte privado como Uber) é possível aplicar modelos baseados em instâncias para
classificação de potenciais motoristas como também a construção de classificadores a
partir de modelos matemáticos usados para tal tarefa (classificação).
( ) c) A aprendizagem baseada em modelos realiza sua generalização por meio de equações
matemáticas, tal como o algoritmo K-NN, enquanto a generalização por instâncias se
baseia em métricas de desempenho.
( ) d) Não existem diferenças entre os modos de aprendizagem de máquina baseados em
instâncias e modelos.

10. Exercício 10 (Fundamentos de ML)

Em vários livros e artigos científicos, além dos diversos materiais que encontramos na
internet, vemos o uso intercambiável ou equivalente entre as expressões algoritmos de aprendizagem
supervisionados, técnicas e/ou modelos de machine learning supervisionadas. A
Figura abaixo apresenta uma terminologia adequada e em sintonia com diversas literaturas
de alto nível da área e nos permite esclarecer os conceitos e diferenças entre essas expressões
para o caso supervisionado.
Baseado na figura, marque a alternativa que descreve o conceito de modelo supervisionado
de machine learning:

( ) a) O modelo de aprendizagem de máquina é o algoritmo de aprendizagem usado para treinamento.
( ) b) O modelo de aprendizagem de máquina supervisionado consiste na combinação entre uma função hipótese candidata e um algoritmo de aprendizagem.
( ) c) O modelo de aprendizagem de máquina consiste em um teste feito entre a função hipótese candidata e a verdadeira.
(X) d) O modelo de aprendizagem de máquina consiste no conjunto de funções hipóteses candidatas que são combinadas com um único algoritmo de aprendizagem de máquina.