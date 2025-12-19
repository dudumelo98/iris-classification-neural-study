# Iris Classification - Neural Network & Logistic Regression Study

Este projeto é um estudo prático de Classificação de Dados utilizando a ferramenta Orange Data Mining. O objetivo foi analisar como diferentes algoritmos de Inteligência Artificial se comportam ao tentar separar grupos de dados com diferentes níveis de semelhança.

## 📊 Metodologia do Experimento
O fluxo de trabalho (workflow) foi estruturado da seguinte forma:

![Fluxo do Projeto](imagens/imagem.png)

- **Criação de Dados**: Utilização do widget Paint Data para gerar pontos que simulam as três espécies da flor Iris.
- **Modelagem**: Implementação paralela de uma Neural Network (Rede Neural) e uma Logistic Regression (Regressão Logística).
- **Avaliação**: Uso do widget Test and Score com a técnica de Cross-Validation (5 dobras) para medir a precisão dos modelos.

## 🧠 Conclusões Técnicas
Ao analisar o gráfico de dispersão (Scatter Plot), chegamos às seguintes conclusões:

- **Grupo Azul (Iris-setosa)**: Ficou completamente isolado no gráfico. Isso ocorre porque suas características físicas são únicas, tornando-o um grupo "linearmente separável" e fácil de identificar pela IA com 100% de precisão.
- **Grupos Vermelho e Verde**: Apresentaram uma zona de sobreposição. Como as flores possuem medidas muito parecidas, os modelos tiveram maior dificuldade em traçar uma fronteira de decisão, resultando em pequenas falhas de classificação nessas áreas.
- **Desempenho dos Modelos**: A Regressão Logística apresentou uma acurácia superior (0.967) em comparação à Rede Neural (0.927) para este conjunto específico de dados.

## 📂 Estrutura do Repositório
- `/images`: Prints do workflow e dos gráficos de resultados.
- `projeto iris.ows`: Arquivo original do Orange com toda a lógica do experimento.
- `Desafio_Iris_Final.xlsx`: Planilha com os dados e as predições finais exportadas.
