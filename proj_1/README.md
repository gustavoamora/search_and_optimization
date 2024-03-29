# busca
Search Problems

Descrição do Trabalho

## Questão 1 (Q1) 

Implementar e comparar o desempenho dos algoritmos de busca:
(i) Depth-first search, 
(ii)Uniform cost search e 
(iii) A* search. 

Para o desenvolvimento do trabalho não é permitido o uso de bibliotecas que implementem os
algoritmos, mas é permitido usar bibliotecas auxiliares, e.g., que implementem estruturas de
dados (ex: NetworkX, etc).
Para comparar os algoritmos, deve ser usado um labirinto com tamanho 300x300 com percentual
de bloqueio 50%, e as métricas de comparação são:
1. tempo de execução;
2. número de nós expandidos;
3. número de nós gerados;
4. custo do caminho e
5. tamanho do caminho.
   
Você deverá criar uma Tabela comparativa com os algoritmos de busca (nas linhas) e as
respectivas métricas resultantes (nas colunas) para cada algoritmo.
Ao medir o tempo de execução, desligue a visualização porque o custo de atualização da
visualização é maior que o custo do algoritmo. Para a comparação ser justa, tome o cuidado de
usar o mesmo labirinto em todos os casos (e.g., fixe o parâmetro seed=42 da classe MazeProblem).

## Questão 2 (Q2) 

Implementar os algoritmos UCS e A* search para o problema clássico de roteamento entre cidades
da Romêmia. O roteamento deve ser feito entre as cidades ‘Arad’ e ‘Bucharest’. 
Compare os resultados obtidos pela aplicação dos algoritmos UCS e A* search em relação ao
(i)caminho obtido e (ii) custo do caminho através de uma tabela.

## Relatório

Em adição aos códigos, deve ser escrito um relatório curto (3-4 páginas) com a estrutura abaixo:
· Fundamentação Teórica: Descrever brevemente os algoritmos implementados e suas
diferenças. Faça uma tabela com as complexidades dos algoritmos BFS, DFS, UCS e A*.
· Experimentos: Descrever como foi realizado o experimento e os resultados esperados
considerando a teoria. Incluir a configuração do computador que será usado nos
experimentos.
· Resultados: Apresentar a comparação dos algoritmos como uma tabela em que linhas são
os algoritmos e colunas são as métricas. Discutir se os resultados foram consistentes com
o esperado pela teoria. Se não, apresentar hipóteses do porquê.
