Modelos de Machine Learning com Dataset Iris
Este projeto implementa dois modelos de aprendizado de máquina utilizando o famoso dataset Iris. Os modelos são comparados em termos de acurácia e desempenho.

📜 Descrição do Projeto
O código treina e avalia dois modelos de machine learning:

SVM (Support Vector Machine) com kernel linear.
Random Forest.
O objetivo é analisar a performance de ambos os modelos e compará-los em relação à acurácia e outras métricas de avaliação.

📂 Estrutura do Projeto
modelo_ml.py: Arquivo principal contendo a classe Modelo, que encapsula todo o pipeline, desde o carregamento do dataset até a avaliação dos modelos.
Dataset Iris: Deve ser carregado pelo usuário no formato .csv ao executar o código.

🚀 Funcionalidades
Carregamento do Dataset: Permite selecionar o arquivo diretamente do computador.
Pré-processamento de Dados:
Tratamento de valores ausentes.
Conversão das classes de espécies em valores numéricos.
Treinamento dos Modelos:
SVM: Utiliza kernel linear para separação de classes.
Random Forest: Modelo baseado em múltiplas árvores de decisão.
Teste e Avaliação:
Acurácia dos modelos.
Relatórios de classificação (precisão, recall e F1-score).
Comparação entre os modelos.

📊 Resultados Esperados
Após a execução do código, você receberá:

Acurácia individual dos modelos.
Relatórios detalhados de cada modelo.
Uma comparação direta entre os dois modelos.

🛠️Como Executar o Código
Certifique-se de ter o Python 3.x instalado.
Instale as dependências necessárias:
pip install pandas scikit-learn
Execute o código e selecione o dataset:
python modelo_ml.py

📂 Exemplo de Dataset
O dataset Iris pode ser baixado no formato .csv e deve conter as seguintes colunas:

SepalLengthCm: Comprimento da sépala.
SepalWidthCm: Largura da sépala.
PetalLengthCm: Comprimento da pétala.
PetalWidthCm: Largura da pétala.
Species: Nome da espécie (Iris-setosa, Iris-versicolor, Iris-virginica).

📝 Observações
O dataset deve estar no formato correto antes de ser utilizado.
Certifique-se de que todos os pacotes estão instalados para evitar erros durante a execução.
