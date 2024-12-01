# Análise de Dados de Vendas e Clustering

## Fontes dos Dados
Os dados utilizados são provenientes de um arquivo Excel **TABELA_VENDAS.xlsx**, que contém informações sobre vendas.

## Ferramentas Utilizadas
- **Python**
- **Pandas**
- **Scikit-learn**
- **Matplotlib**

## Como Executar
1. Instale as dependências: `pip install pandas scikit-learn matplotlib openpyxl`.
2. Carregue os dados utilizando o código.
3. Execute o código para ver as métricas de aprendizado supervisionado e os clusters gerados.

## Resultados
- **Métricas do Modelo de Regressão Linear**: MAE, RMSE, R².
- **Modelo de K-Means**: Método do Cotovelo, Silhouette Score, Gráfico de Clusters.

## Relatório de Análise de Dados de Vendas e Clustering
Fontes dos Dados
Os dados utilizados neste projeto são provenientes de uma tabela de vendas, que foi extraída do arquivo TABELA_VENDAS.xlsx. Esse arquivo contém informações como quantidade de pedidos, preço de custo unitário, e o total de vendas para diferentes produtos e regiões.

Fonte: Arquivo fornecido pelo usuário (pode incluir mais detalhes, como link para acesso, se aplicável).

## Ferramentas Utilizadas
Este projeto foi desenvolvido com as seguintes ferramentas e bibliotecas:

Python: Linguagem de programação utilizada para análise de dados e desenvolvimento do modelo de aprendizado de máquina.
Pandas: Biblioteca para manipulação e análise de dados (como a leitura do arquivo Excel e a manipulação de DataFrames).
Scikit-learn: Biblioteca para aprendizado de máquina. Foi utilizada para:
Modelo de Regressão Linear (para análise supervisionada).
K-Means (para análise não supervisionada - clustering).
Matplotlib: Biblioteca para visualização de dados e gráficos.
Jupyter Notebook (opcional): Ambiente interativo utilizado para desenvolvimento e execução do código.
Instruções para Execução do Projeto
Pré-requisitos
Certifique-se de ter Python 3.x instalado em seu sistema.
Instale as bibliotecas necessárias utilizando o pip:
bash
Copiar código
pip install pandas scikit-learn matplotlib openpyxl
Passos para Execução
Carregue o arquivo de dados: O arquivo TABELA_VENDAS.xlsx deve estar no mesmo diretório do script ou você pode ajustar o caminho do arquivo no código.

Pré-processamento dos dados: O código realiza o pré-processamento dos dados para garantir que as variáveis necessárias não tenham valores ausentes.

## Modelo de Regressão Linear (Supervisionado):

O modelo de regressão linear é treinado para prever o Total Venda com base nas variáveis Pedidos Qtd e Preço Custo Unit.
As métricas do modelo (MAE, RMSE, R²) serão exibidas como resultado.
Modelo de Clustering (Não Supervisionado):

O modelo K-Means é utilizado para agrupar os dados em clusters baseados em Pedidos Qtd e Total Venda.
O número ideal de clusters é determinado pelo Método do Cotovelo, e a qualidade do agrupamento é medida pelo Silhouette Score.
Os clusters são visualizados em um gráfico de dispersão.
Execução do Código
Modelo de Regressão Linear (Supervisionado):

Execute a célula que contém o código para o modelo de regressão linear.
O modelo será treinado e as métricas (MAE, RMSE, R²) serão exibidas.
Modelo de K-Means (Não Supervisionado):

Execute a célula que contém o código para o modelo de clustering.
O gráfico do Método do Cotovelo será exibido, ajudando a escolher o número ideal de clusters.
O Silhouette Score e os gráficos de dispersão dos clusters serão apresentados.
Resultados Obtidos
Regressão Linear
MAE (Erro Médio Absoluto): A medida do erro médio das previsões em relação aos valores reais. Quanto menor, melhor.
RMSE (Raiz do Erro Quadrático Médio): Avalia a magnitude do erro médio em unidades da variável dependente. Menores valores indicam um modelo mais preciso.
R² (Coeficiente de Determinação): Mede o grau de explicação da variabilidade dos dados. Um valor próximo de 1 indica que o modelo explica bem os dados.
Exemplo de resultados para o modelo de regressão linear:

arduino
Copiar código
Métricas do Modelo:
MAE (Erro Médio Absoluto): 150.32
RMSE (Raiz do Erro Quadrático Médio): 200.14
R² (Coeficiente de Determinação): 0.87
K-Means Clustering
Método do Cotovelo: O gráfico gerado pelo método ajuda a identificar o número ideal de clusters, visualizando a diminuição da inércia à medida que o número de clusters aumenta.
Silhouette Score: Mede a qualidade do agrupamento. Valores próximos de 1 indicam que os clusters são bem definidos.
Gráfico de Clusters: Exibe a distribuição dos dados nos diferentes clusters gerados.
Exemplo de resultados para o modelo de clustering:

yaml
Copiar código
Silhouette Score: 0.78
Gráficos gerados:

Método do Cotovelo
Gráfico de dispersão dos clusters
Conclusão
Neste projeto, utilizamos modelos de aprendizado de máquina supervisionado (regressão linear) e não supervisionado (K-Means) para analisar e agrupar os dados de vendas. As métricas de desempenho e as visualizações geradas ajudaram a entender melhor a relação entre as variáveis e a identificar padrões nos dados. O código pode ser facilmente ajustado para outros conjuntos de dados, bastando modificar o caminho do arquivo e as variáveis de interesse.


