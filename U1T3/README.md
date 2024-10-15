# U1T3 - Medicamentos Registrados no Brasil | 🇧🇷

### Dados Abertos Medicamentos:
##### A base de dados abertos de registro de medicamentos é um projeto de inteligência de Dados que extrai informações do sistema Datavisa para listar os produtos que tenham sido registrados pela Anvisa, incluindo aqueles cujo registro já esteja válido ou cancelado/caduco, de acordo como informado no portal de consultas da Agência.

#### Students: Gabriel Vitor Pereira dos Santos and João Victor Soares da Silva Vieira.

### 🔗 Video with the explanation of the assignment [here]().
##### Hipóteses a serem testadas:
1. Hipótese da Categoria Regulatória:
○ Medicamentos da mesma categoria regulatória tendem a compartilhar
mais princípios ativos?
2. Hipótese da Empresa:
○ Medicamentos da mesma empresa tendem a compartilhar mais
princípios ativos?
3. Hipótese da Complexidade:
○ Medicamentos com mais princípios ativos tendem a se conectar com
medicamentos de similar complexidade?

#### References

- :books: [Coscia, Michele. The Atlas for the Aspiring Network Scientist](https://www.networkatlas.eu/)

> Rede #01
Co-ocorrência de Princípios Ativos entre Medicamentos
● Nós (vértices): Cada medicamento é um nó.
● Arestas (Edges): Existe uma aresta entre dois medicamentos se eles
compartilham ao menos um princípio ativo.
● Assortatividade: Calcular a assortatividade com base na categoria
regulatória dos medicamentos.
Pergunta a ser respondida:
○ Medicamentos da mesma categoria regulatória tendem a compartilhar
princípios ativos?
----------------
> Rede #02
Grafo Bipartido de Medicamentos e Princípios Ativos
● Nós (vértices): Medicamentos e princípios ativos são nós distintos.
● Arestas (Edges): Uma aresta conecta um medicamento aos seus
respectivos princípios ativos.
● Assortatividade: Calcular a assortatividade por grau dentro do grafo
bipartido para determinar se os princípios ativos que se conectam a
medicamentos complexos (com muitos princípios ativos) tendem a se
conectar também a medicamentos com perfis de complexidade
semelhante.
Pergunta a ser respondida:
○ Princípios ativos compartilhados por medicamentos complexos tendem
a se conectar a medicamentos com perfis de complexidade similar?
-----------------
> Rede #03
Co-ocorrência por Empresa ou Classe Terapêutica
● Nós (Nodes): Cada medicamento é um nó.
● Arestas (Edges): Existe uma aresta entre dois medicamentos se eles
compartilham ao menos um princípio ativo.
● Assortatividade: Calcular a assortatividade com base na empresa ou classe
terapêutica dos medicamentos.
Pergunta a ser respondida:
○ Medicamentos da mesma empresa ou classe terapêutica tendem a
compartilhar mais princípios ativos?

