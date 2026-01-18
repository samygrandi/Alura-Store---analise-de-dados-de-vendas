# Alura-Store---analise-de-dados-de-vendas

📊 Análise de Desempenho das Lojas — Alura Store
📌 Visão Geral

Este projeto tem como objetivo analisar os dados de vendas de quatro lojas fictícias da Alura Store para auxiliar na tomada de decisão estratégica sobre qual loja deve ser vendida para viabilizar um novo empreendimento.

O projeto foi desenvolvido utilizando Python e bibliotecas de análise e visualização de dados, com foco em métricas de desempenho financeiro, satisfação dos clientes e custos operacionais.

🎯 Objetivo do Projeto

Avaliar o desempenho das lojas com base nos seguintes indicadores:

Faturamento total

Faturamento por categoria de produtos

Avaliação média dos clientes

Frete médio por loja

Ao final da análise, apresentar uma recomendação clara e fundamentada sobre qual loja deve ser vendida.

🛠️ Tecnologias Utilizadas

Python 3

Pandas — Manipulação e análise de dados

Matplotlib — Visualização de dados

Google Colab — Ambiente de desenvolvimento

GitHub — Versionamento e publicação do projeto

📁 Estrutura do Projeto
📦 alura-store-analise
 ┣ 📜 README.md
 ┣ 📓 analise_lojas.ipynb
 ┗ 📊 dados/
    ┣ loja_1.csv
    ┣ loja_2.csv
    ┣ loja_3.csv
    ┗ loja_4.csv

📊 Etapas da Análise
1️⃣ Importação e Tratamento dos Dados

Os dados das quatro lojas foram carregados a partir de arquivos CSV, utilizando a biblioteca Pandas.
Foram realizadas verificações iniciais para garantir a consistência das informações.

2️⃣ Análise de Faturamento

Cálculo do faturamento total por loja.

Comparação visual utilizando gráficos de barras.

Identificação da loja com menor desempenho financeiro.

3️⃣ Faturamento por Categoria

Análise do faturamento agrupado por categoria de produtos.

Identificação das 5 categorias mais relevantes (Top 5) em cada loja.

Utilização de gráficos de pizza para análise percentual.

4️⃣ Avaliação Média dos Clientes

Cálculo da média de avaliação de cada loja.

Arredondamento para duas casas decimais.

Comparação visual entre as lojas.

5️⃣ Análise do Frete Médio

Cálculo do frete médio por loja.

Visualização por meio de gráfico de barras.

Identificação de lojas com maior custo logístico.

📈 Visualizações

Foram utilizados diferentes tipos de gráficos para facilitar a interpretação dos dados:

Gráficos de barras

Gráficos de pizza

Essas visualizações permitem uma análise clara e objetiva dos indicadores de desempenho.

✅ Conclusão

Com base nos dados analisados, foi possível identificar diferenças significativas entre as lojas.
A Loja 4 apresentou:

O menor faturamento total

Avaliação média inferior às demais

Frete médio elevado

Menor desempenho nas categorias estratégicas

📌 Recomendação final:
A Loja 4 é a mais indicada para ser vendida, pois apresenta o menor desempenho geral, tornando-se a opção mais estratégica para desinvestimento e início de um novo empreendimento.

▶️ Como Executar o Projeto

Clone este repositório:

git clone https://github.com/seu-usuario/alura-store-analise.git


Abra o notebook analise_lojas.ipynb no Google Colab ou em um ambiente Jupyter.

Execute as células sequencialmente para reproduzir todas as análises e gráficos.

⚠️ Possíveis Problemas e Soluções

Erro ao carregar CSV: Verifique a conexão com a internet ou o caminho do arquivo.

Gráficos não exibidos: Confirme se todas as células foram executadas corretamente.

Diferença de valores: Certifique-se de não alterar os dados originais.

📌 Considerações Finais

Este projeto demonstra a aplicação prática de análise de dados para suporte à tomada de decisão, utilizando métricas objetivas e visualizações claras.
O README foi estruturado para facilitar o entendimento do projeto por recrutadores e outros desenvolvedores.
