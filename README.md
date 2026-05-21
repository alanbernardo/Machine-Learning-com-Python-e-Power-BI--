📊 Segmentação de Clientes com Machine Learning e Power BI

Projeto desenvolvido como prática de aprendizado no curso Microsoft Power BI Para Business Intelligence e Data Science da entity["organization","Data Science Academy","Brasil"].

🚀 Sobre o Projeto

Este projeto tem como objetivo aplicar técnicas de Machine Learning para realizar a segmentação de clientes utilizando o algoritmo K-Means Clustering.

Além da análise em Python, os dados foram integrados ao Power BI para criação de dashboards e visualizações analíticas.

A proposta principal foi identificar padrões de comportamento entre clientes com base em variáveis como:

Idade
Renda anual
Pontuação de gastos
🧠 Principais Conceitos Trabalhados
Análise Exploratória de Dados (EDA)
Tratamento e padronização de dados
Clusterização com K-Means
Integração Python + Power BI
Visualização de dados
Business Intelligence
🛠️ Tecnologias Utilizadas
Tecnologia	Finalidade
Python	Processamento e análise de dados
Pandas	Manipulação de dados
Scikit-Learn	Machine Learning
Power BI	Dashboards e visualizações
Jupyter Notebook	Desenvolvimento do projeto
📂 Estrutura do Projeto
├── Lab7.ipynb
├── Lab7-Final.pbix
├── Lab7-JupyterNotebook.pbix
├── dados/
│   ├── dados_clientes.csv
│   └── segmentos.csv
└── imagens/
    └── dashboard.png
🔍 Etapas do Desenvolvimento
1. Importação dos Dados

Os dados foram carregados utilizando Pandas.

import pandas as pd


df = pd.read_csv('dados_clientes.csv')
2. Análise Exploratória

Nesta etapa foram realizadas análises estatísticas e identificação de padrões nos dados.

Principais análises:

Distribuição das variáveis
Perfil dos clientes
Correlação entre informações
Comportamento de consumo
3. Padronização dos Dados

Foi utilizado o StandardScaler para normalização das variáveis.

from sklearn.preprocessing import StandardScaler

Essa etapa é importante para garantir melhor desempenho do algoritmo de clusterização.

4. Clusterização com K-Means

O algoritmo K-Means foi utilizado para agrupar clientes com características semelhantes.

from sklearn.cluster import KMeans

Com isso, foi possível:

Identificar perfis de clientes
Criar segmentos estratégicos
Melhorar análises de negócio
5. Visualização no Power BI

Após o processamento em Python, os resultados foram integrados ao Power BI para construção de dashboards interativos.

Arquivos do projeto:

Lab7-Final.pbix
Lab7-JupyterNotebook.pbix
📈 Resultados Obtidos

O projeto permitiu:

✅ Aplicar Machine Learning na prática
✅ Trabalhar com segmentação de clientes
✅ Integrar Python ao Power BI
✅ Criar dashboards analíticos
✅ Desenvolver visão analítica para negócios

💡 Possíveis Aplicações

A clusterização de clientes pode ser utilizada em:

Marketing direcionado
Estratégias comerciais
Personalização de ofertas
Fidelização de clientes
Análise comportamental
▶️ Como Executar o Projeto
Clone o repositório
git clone https://github.com/seu-usuario/seu-repositorio.git
Instale as dependências
pip install pandas scikit-learn
Execute o Notebook

👨‍💻 Autor
Alan Bernardo da Silva

Estudando:

Data Analytics
Business Intelligence
Power BI
Python
Machine Learning

mais alinhado com projetos de Data Science e BI

Agora ele está mais apresentável para recrutadores e para demonstrar aprendizado prático em Machine Learning + Power BI.
