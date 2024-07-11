# Projeto de Análise de Dados Everything Plus

## Descrição do Projeto
Este projeto é uma tarefa analítica da loja Everything Plus, uma loja online fictícia que vende utensílios domésticos. Ele foi desenvolvido como a entrega final do curso de analista de dados da Tripleten e tem como objetivo demonstrar na prática os conhecimentos adquiridos durante o curso.

**Contexto:** A empresa Everything Plus deseja melhorar suas vendas desenvolvendo ofertas mais personalizadas para diferentes usuários por meio da segmentação de clientes. O setor de marketing, juntamente com o comercial, precisa de uma análise precisa para tomar decisões informadas sobre promoções e propagandas.

### Objetivos
- Realizar a análise exploratória de dados.
- Segmentar os usuários com base no histórico de compras, implementando ideias próprias para a segmentação.
- Desenvolver ofertas personalizadas para diferentes usuários.
- Formular e testar hipóteses estatísticas.

## Ferramentas e Bibliotecas Utilizadas
- Python: Linguagem principal utilizada para a análise.
- Pandas: Biblioteca para manipulação e análise de dados.
- Matplotlib.pyplot, plotly.graph_objects e seaborn: Bibliotecas para criação de gráficos.
- sklearn: Machine learning.
- scipy.cluster.hierarchy: Criação de agrupamentos com machine learning.

## Tabela
O arquivo `ecommerce_dataset_us.csv` contém as seguintes colunas:
- `InvoiceNo` — identificador de pedido
- `StockCode` — identificador de item
- `Description` — nome de item
- `Quantity` — quantidade de itens
- `InvoiceDate` — data do pedido
- `UnitPrice` — preço por item
- `CustomerID` — identificador do cliente

## Metodologia

##### Objetivo
- Definir os objetivos do estudo e sua importância.
- Identificar o público-alvo interessado nos resultados.
- Determinar quais decisões serão baseadas nas análises.

##### Análise Exploratória de Dados
- Importar as bibliotecas necessárias.
- Carregar e visualizar os dados.

##### Pré-processamento
- Identificar e tratar valores ausentes.
  - Substituir CustomerID nulos.
- Renomear colunas para nomes intuitivos e padronizados.
- Corrigir valores anômalos.
- Remover valores duplicados.

##### Análise dos Dados
- Propor hipóteses de segmentação e comportamento do cliente.
- Criar colunas adicionais para facilitar a análise.
  - Coluna preço da compra.
  - Coluna mês da data do pedido.
  - Coluna preço do pedido.
  - Coluna preço do primeiro pedido.
  - Coluna total gasto.
  - Coluna itens no pedido.
  - Coluna quantidade de pedidos.
- Organizar a ordem das colunas.

##### Visualização dos Dados
- Desenhar histogramas e outros gráficos relevantes.
  - Gráfico pedido x tempo.
  - Gráfico faturamento x tempo.
  - Gráfico total de pedidos x total gasto.

##### Agrupamento de Dados
- Filtrar dados relevantes.
- Agrupar dados por clientes.
- Criar mapas de calor para visualização.

##### Segmentação de Clientes
- Padronizar os dados.
- Aplicar técnicas de aprendizado de máquina para segmentação.
  - Dendrograma para visualização hierárquica.
  - K-means para clustering.
  - Identificação de padrões nos agrupamentos formados pela IA.

##### Refinamento dos Dados
- Filtrar e ajustar novamente os grupos.
- Reaplicar o K-means para validação dos clusters.

##### Conclusões
- Analisar como ficou a divisão dos dados.
- Elaborar conclusões com base nos resultados obtidos.

## Resultados
Identificou-se que muitos produtos de baixo valor são vendidos em grandes quantidades. Além disso, há pedidos com diversos produtos diferentes, elevando o valor médio dos pedidos. Os clientes fazem compras com certa frequência, cerca de 4 compras por ano em média. Os clientes mais rentáveis são os que fazem muitas compras. Muitos clientes começaram a comprar a partir de uma primeira compra de 300 dólares, indicando que, se foi uma promoção, ela foi bem-sucedida. As compras aumentam do meio do ano para frente, sendo o final do ano o período com mais vendas e faturamento, com destaque para novembro.

Os valores são menos relevantes que a quantidade de produtos. Uma grande parcela da clientela faz poucas compras e de baixo valor.


## Aprendizados

Este projeto permitiu-me desenvolver as seguintes habilidades:

- Análise de dados: interpretação e extração de insights valiosos a partir de grandes volumes de dados.
- Limpeza de dados: identificação e correção de valores ausentes, duplicados e anômalos.
- Manipulação de tabelas: reorganização e transformação de dados para facilitar a análise.
- Análise de funil de vendas: compreensão das diferentes etapas do processo de vendas e identificação de pontos de melhoria.
- Criação de gráficos interativos: utilização de bibliotecas como Matplotlib, Plotly e Seaborn para visualizar dados de maneira intuitiva e informativa.
- Segmentação de clientes com aprendizado de máquina: aplicação de técnicas de clustering para identificar grupos distintos de clientes.
- Pré-processamento de dados: preparação dos dados para análise, incluindo normalização e padronização.
- Formulação de hipóteses: desenvolvimento e teste de suposições sobre o comportamento dos clientes com base nos dados.
- Visualização de dados: criação de mapas de calor e outros tipos de visualizações para identificar padrões e tendências.
- Documentação de projetos: elaboração de documentação clara e detalhada para garantir que o projeto seja compreensível e replicável.
- Utilização de bibliotecas e ferramentas: aplicação prática de diversas bibliotecas e ferramentas do ecossistema Python, como Pandas, Seaborn, Plotly, Sklearn e Scipy.
- Tomada de decisões baseadas em dados: uso de insights derivados da análise de dados para orientar decisões estratégicas.

## Como Executar o Projeto

- Clone o repositório.
- Navegue até o diretório do projeto.
- Abra o projeto no seu IDE favorito.
- Instale as dependências.
- Execute o script principal.

## Contato

Andre Corso Camara  
[LinkedIn](https://www.linkedin.com/in/andre-corso-c%C3%A2mara/)  
Email: devandrecorso@hotmail.com

Assim, a seção Aprendizados ficou mais robusta, refletindo um conjunto mais amplo de habilidades desenvolvidas ao longo do projeto.