<h1 align="center">
  📊 Projeto de Data Analytics
</h1>

<div align="center">

![Python](https://img.shields.io/badge/python-3.11-blue)
![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?logo=powerbi&logoColor=black)
![Google Colab](https://img.shields.io/badge/Google%20Colab-F9AB00?logo=googlecolab&logoColor=white)
![Pandas](https://img.shields.io/badge/pandas-150458?logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/numpy-013243?logo=numpy&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557c)
![Seaborn](https://img.shields.io/badge/Seaborn-4C72B0)
![Git](https://img.shields.io/badge/git-F05032?logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/github-181717?logo=github&logoColor=white)

</div>

## 📑 Índice

- [Introdução](#introdução)

## 📌 Contexto

A **LH Nautical** é uma empresa de varejo náutico, líder em peças e acessórios do segmento, de alto padrão que enfrenta desafios comuns ao crescimento acelerado: falta de visibilidade sobre a rentabilidade real por categoria e necessidade de uma gestão de estoque baseada em dados, saindo do modelo de "intuição" para o modelo preditivo.

Este projeto foi desenvolvido como parte de um desafio de Data Analytics/Data Science, com o objetivo de analisar dados do negócio e gerar insights estratégicos que apoiem a tomada de decisão. A análise contempla desde o entendimento do problema de negócio até a construção de modelos preditivos de demanda e sistemas de recomendação baseados em Inteligência Artificial, unindo rigor estatístico à visão de crescimento de negócio.

Nota: A LH Nautical é uma empresa fictícia criada para fins de estudo de caso e desenvolvimento de competências em análise/ciência de dados.


## 🎯 Objetivo do Projeto

Desenvolver um diagnóstico profundo da saúde financeira da empresa e implementar modelos de inteligência artificial que auxiliem na tomada de decisão estratégica, focando em:
* Identificar e mitigar perdas financeiras.;
* Otimizar o giro de estoque de produtos críticos;
* Alavancar vendas através de recomendações personalizadas.


## ❓ Problema de Negócio

O principal desafio identificado foi a **erosão da margem de lucro**. Embora a empresa apresente um faturamento expressivo em meses de pico (Julho e Outubro), a análise revelou um déficit operacional oculto em categorias core. O caso mais crítico é a categoria de **Propulsão**, onde produtos específicos operavam com um percentual de perda superior a 60%. Esse cenário indica que o volume de vendas estava, na verdade, acelerando o prejuízo acumulado em vez de gerar rentabilidade real.


## 🛠️ Ferramentas Utilizadas

* **Python:** Linguagem principal para manipulação e análise de dados.
* **Pandas & Numpy:** Limpeza, transformação e cálculos estatísticos.
* **Matplotlib & Seaborn:** Visualização de dados e criação de gráficos executivos.
* **Scikit-Learn:** Implementação de algoritmos de Machine Learning (Similaridade de Cosseno).


## 🛠️ Pipeline de Dados

O fluxo de trabalho foi estruturado em 5 etapas principais para garantir a integridade dos insights:

1. **Extração e Limpeza:** Tratamento de valores nulos, conversão de tipos de dados e padronização de categorias;
2. **Exploração (EDA):** Identificação de outliers, sazonalidade de vendas e correlações entre produtos;
3. **Engenharia de Atributos:** Criação de métricas de negócio como Prejuízo Acumulado, Ticket Médio e Percentual de Perda;
4. **Modelagem Preditiva:** Desenvolvimento do modelo Baseline para controle de estoque (Yamaha 155HP) e motor de recomendação via Similaridade de Cosseno;
5. **Storytelling & Insights:** Tradução dos dados técnicos em recomendações estratégicas para a diretoria.


## 📈 Principais Insights

A análise dos dados da LH Nautical, revelou pontos críticos e oportunidades de crescimento:

1. **Déficit de Categoria (Propulsão):** Identificamos que a categoria de Propulsão acumula um prejuízo de **R$ 122.7M**. Isso indica que a estratégia de precificação ou os custos de importação estão desalinhados com a realidade do mercado.
2. **Oportunidade de Cross-Selling:** O motor de recomendação identificou uma similaridade de **87%** entre o **GPS Garmin** e o **Motor Yamaha 155HP**. Clientes que compram motores de alta performance têm alta propensão a adquirir eletrônicos de navegação de ponta.
3. **Eficiência de Estoque (Baseline):** Ao comparar o estoque real com o modelo preditivo, notamos que em meses como Outubro, a empresa manteve **30% a mais** de estoque do que o necessário, imobilizando capital que poderia ser reinvestido em marketing ou logística.

## 🚀 Recomendações Estratégicas

Com base no diagnóstico de dados, as seguintes ações são recomendadas para o ciclo 2026/2027:

1. **Revisão da Tabela de Preços (Propulsão):** Auditoria imediata nos custos de aquisição e logística dos motores com perda superior a 60%. O objetivo é reequilibrar a margem bruta ou descontinuar modelos de baixa performance financeira;
2. **Automação de Cross-Selling:** Implementar o motor de recomendação no checkout do e-commerce e no script de vendas consultivas, oferecendo eletrônicos (GPS/Sondas) para todo comprador de motores de popa;
3. **Gestão de Estoque Just-in-Time:** Adotar o modelo **Baseline Preditivo** para compras de motores Yamaha 155HP em Outubro e Novembro, reduzindo o capital imobilizado em estoque desnecessário.


## 📓 Notebook da Análise

O desenvolvimento técnico completo, incluindo a limpeza dos dados, criação dos gráficos de rentabilidade e o código do sistema de recomendação (Cosseno), pode ser acessado no link abaixo:

* [Acesse o Notebook (Google Colab/Jupyter)](Disponível em breve)

## 👩‍💻 Autora

Nome: Michele Farias
* [LinkedIn](https://www.linkedin.com/in/fariasmichele/)
  
* *Desenvolvedora de soluções de dados focadas em Business Intelligence e Analytics.*

