# Exercicio_ETL
# Exemplo de Processo ETL - Extração, Transformação e Carregamento

Este repositório contém um exemplo prático de um processo ETL (Extração, Transformação e Carregamento) de dados usando Python, Pandas e SQLite. O objetivo do exercício é ilustrar como extrair dados de arquivos CSV e XLSX, realizar transformações para cálculo de valores, e carregar os dados em um banco de dados SQLite.

# Contexto
Este notebook faz parte de um exercício de ETL onde realizamos os seguintes passos:

Extração dos dados de arquivos CSV e XLSX.
Transformação dos dados para calcular o valor total de vendas.
Carregamento dos dados em um banco de dados SQLite e salvamento de resultados transformados em novos arquivos CSV.
O propósito é entender como manipular dados, realizar operações básicas de transformação e integrar o processo com um banco de dados local.

# Tecnologias Utilizadas
- Python (versão 3.x)
- Pandas - Para manipulação e análise de dados.
- SQLite - Para armazenamento dos dados em um banco de dados relacional local.
- Google Colab - Para rodar e testar o código.
- Git e GitHub - Para versionamento de código e colaboração.
  
# Etapas do Processo ETL
1. Extração dos Dados
Os dados foram extraídos de dois arquivos: dados.csv e dados.xlsx. Ambos os arquivos contêm informações de vendas, como nome do produto, quantidade e preço. Utilizamos a biblioteca Pandas para ler esses arquivos e transformá-los em DataFrames.

2. Transformação dos Dados
Durante a transformação, foi calculado o valor total de vendas para cada produto, multiplicando a quantidade de itens vendidos pelo preço unitário. Esse valor foi armazenado em uma nova coluna chamada "Valor Total" nos DataFrames.

3. Carregamento dos Dados

4. Consultas SQL
Realizamos consultas no banco de dados SQLite para visualizar e validar os dados carregados.

# Vantagens Obtidas
1. Automação do Processo:
Todo o processo de ETL foi automatizado, garantindo eficiência e repetibilidade.

2. Centralização dos Dados:
Todos os dados, após a transformação, foram centralizados em um banco de dados, facilitando a consulta e manipulação.

3. Facilidade na Manipulação de Dados:
Utilizar o Pandas permitiu trabalhar com os dados de forma intuitiva, realizando cálculos e transformações de maneira eficiente.

4. Escalabilidade:
O uso de SQLite permite que o projeto seja facilmente escalável para bases de dados maiores, ou integrável a outros sistemas de gerenciamento de banco de dados (como MySQL ou PostgreSQL).

# O que é o SQLite?
SQLite é um banco de dados relacional leve e integrado. Ele não requer um servidor para funcionar, pois os dados são armazenados diretamente em um arquivo local. Suas principais vantagens incluem:

Simplicidade de Uso: Ideal para projetos pequenos e testes, pois não necessita de configuração.
Portabilidade: Os dados são armazenados em um único arquivo, tornando fácil transportá-los.
Rápido para Consultas Leves: Funciona bem para consultas rápidas e processamento de datasets de pequeno a médio porte.

# Executar 
link collab: https://colab.research.google.com/drive/1NdGrRpy6c-zhJ46vjHjoMpFgQ5ta84NH?usp=sharing
