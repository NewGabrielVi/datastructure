# U1T4 - Criar uma rede referente a cidade Natal-RN

#### Student: Gabriel Vitor Pereira dos Santos.

### 🔗 Video with the explanation of the assignment [here](https://www.loom.com/share/eace3816d8a94d9a899bff0836e0f027?sid=6d583182-b8d0-45af-b7f4-b2653776bc91).

#### References

- :books: [Coscia, Michele. The Atlas for the Aspiring Network Scientist](https://www.networkatlas.eu/)
- https://github.com/gboeing/osmnx-examples

### Métricas estudadas e usadas:
* Cycles; 
* Average Shortest Path Length; 
* Diameter of Network;
* Shortest Path Length; 
* Connected Components; 
* Giant Connected Components; 
* number connected components, BFS, DFS, SCC, WCC;
* Clustering Coefficient.
----------------
# Explicação: 
### Foi útilizado as métricas apresentadas em sala de aula e aplicadas em código sobre o o gráfico do mapa de Natal - RN, abaixo está os resultados de cada métrica apresentada, mais detalhes do código podem ser vistos em U1T4.ipynb.


## Gráfo de Natal-RN
![gráfico](images/gráfico.png)
# Principais resultados de acordo com cada tópico:
## Cycles: Quantos ciclos independentes existem na rede de Natal?
![cycles](images/Cycles.png)
## Average Shortest Path Length: Qual é o comprimento médio do caminho mais curto na rede?
![AVG](images/AVG.png)
## Diameter of Network: Qual é o diâmetro da rede?
![Diameter](images/Diameter.png)
## Shortest Path Length: Qual é o comprimento do caminho mais curto entre dois nós?
![Shortest Path Length](images/ShortestPathLength.png)
## Connected Components: Quantos componentes conectados existem na rede?
![Connected Components](images/ConnectedComponents.png)
## Giant Connected Components: Qual é a quantidade de componentes gigantes conectados?
![Giant Connected Components](images/GiantConnectedComponents.png)
## Observações sobre BFS, DFS, SCC, WCC: 
#### BFS (Busca em Largura) e DFS (Busca em Profundidade) são algoritmos que podem ser utilizados para explorar a rede, mas não são diretamente quantificáveis como as métricas acima. Você pode utilizá-los para verificar a conectividade ou explorar caminhos.
![BFSeDFS](images/BFSeDFS.png)
#### SCC (Strongly Connected Components) e WCC (Weakly Connected Components) podem ser calculadas para grafos direcionados ou não direcionados. Para isso, você deve usar funções adequadas:
![SCC](images/SCC.png)
## Clustering Coefficient: Qual é o coeficiente de agrupamento médio da rede?
![ClusteringCoefficient](images/ClusteringCoefficient.png)

