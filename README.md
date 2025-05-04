🚗 Previsão de Preço de Veículos com Random Forest
Autor: Antonio Vinicius
📌 Objetivo do Projeto
Este projeto tem como finalidade desenvolver um modelo de regressão utilizando o algoritmo Random Forest para prever o preço de veículos (variável Price) com base em diversas características do conjunto de dados.

A avaliação da performance do modelo será feita por meio da métrica MAE (Mean Absolute Error), sendo que quanto menor o MAE, mais eficiente é o modelo.

🧠 Tecnologias e Bibliotecas Utilizadas
Python 3.x

pandas

numpy

matplotlib

seaborn

scikit-learn



prophet (para comparações com modelos de séries temporais)

🗃️ Base de Dados
O conjunto de dados utilizado contém informações sobre veículos, incluindo variáveis como marca, modelo, ano, tipo de combustível, quilometragem, entre outros. Os dados foram armazenados e consultados com MongoDB, garantindo flexibilidade e escalabilidade no tratamento das informações.

🔍 Etapas do Projeto
Coleta e Armazenamento dos Dados

Dados inseridos e manipulados.

Análise Exploratória (EDA)

Gráficos completos com o uso de matplotlib e seaborn para entender padrões e correlações entre variáveis.

Pré-processamento

Limpeza, tratamento de valores nulos, codificação de variáveis categóricas e normalização.

Modelagem

Criação e treinamento do modelo de regressão com o algoritmo Random Forest.

Ajuste de hiperparâmetros para otimização do desempenho.

Avaliação do Modelo

Cálculo da métrica MAE.

Comparação de desempenho com modelos alternativos, como o Prophet.

Visualizações Finais

Geração de gráficos e relatórios que mostram a performance do modelo e os principais fatores que impactam no preço dos veículos.

📈 Resultados Esperados
Obtenção de um modelo com baixo erro absoluto médio (MAE).

Identificação das variáveis que mais influenciam no preço de um veículo.

Visualizações claras e interativas que auxiliem a interpretação dos resultados.
