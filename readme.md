# TP1 - Algoritmos 2

## Aplicações de algoritmos geométricos

### Objetivos
O objetivo central deste trabalho prático é abordar aspectos práticos de
implementação dos algoritmos geométricos vistos nas aulas teóricas. Em particular,
abordaremos aspectos práticos das árvores k-dimensionais para solução de problemas
em outra área da computação. Dessa forma, veremos, além dos detalhes de
implementação de tal estrutura, sua aplicação em outros contextos que não
exatamente em geometria computacional.

### Atividades realizadas:
1. Implementar a classe árvore kd que receba um conjunto de pontos no espaço
k-dimensional e construa a estrutura adequadamente. Os pontos devem ser 
armazenados obrigatoriamente nas folhas. Não serão aceitas implementações
que armazenem pontos em nós intermediários. O rótulo das instâncias
(pontos) não deve ser considerados na construção da árvore.
2. Implementar a classe x-NN que recebe um conjunto de pontos treinamento e
outro de teste, constrói a árvore kd com o conjunto de treinamento, e, depois,
para cada ponto A no conjunto de teste, recupera os x pontos mais próximos
de A e determina a classe de A pelo voto majoritário (em caso de empate
escolhe arbitrariamente).
3. A classe deve fornecer as estatísticas da classificação
(acurácia/precisão/revocação – links com as definições nas referências) e as
classes dos pontos no conjunto de teste. 