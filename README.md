# Projeto Python IA: Inteligência Artificial de Previsões

## Descrição do Projeto

Este projeto utiliza **Inteligência Artificial (IA)** para prever o **score de crédito** de clientes com base em seus dados. O score pode ser classificado como **Ruim**, **OK** ou **Bom**. O objetivo é criar um modelo de IA que analise os dados dos clientes e forneça uma previsão confiável para auxiliar na tomada de decisões financeiras.

## Passos do Projeto

1. **Importar a base de dados**  
   A base de dados utilizada contém informações detalhadas sobre os clientes, como idade, profissão, salário anual, número de contas, entre outros.

2. **Preparar a base de dados para a IA**  
   Os dados foram processados e codificados para que a IA pudesse interpretá-los corretamente. Foi utilizado o `LabelEncoder` para transformar dados categóricos em numéricos.

3. **Criar e treinar a IA**  
   Dois modelos de IA foram criados:
   - **Random Forest Classifier**
   - **K-Nearest Neighbors (KNN)**  
   Ambos os modelos foram treinados com os dados de treino.

4. **Escolher o melhor modelo**  
   A precisão dos modelos foi avaliada utilizando a métrica `accuracy_score`. O modelo com melhor desempenho foi selecionado para as previsões.

5. **Prever novos clientes**  
   O modelo escolhido foi utilizado para prever o score de crédito de novos clientes com base em seus dados.

## Tecnologias Utilizadas

- **Python**  
  - `pandas` para manipulação de dados.  
  - `scikit-learn` para criação e treinamento dos modelos de IA.  

## Resultados

- O modelo foi capaz de prever o score de crédito com boa precisão.  
- Exemplos de previsões para novos clientes:
  - **Entrada:** Dados do cliente.  
  - **Saída:** Score de crédito (e.g., Ruim, OK, Bom).

## Como Executar o Projeto

1. Certifique-se de ter o Python instalado em sua máquina.
2. Instale as dependências necessárias:
   ```bash
   pip install pandas scikit-learn
   ```
3. Execute o script principal no Jupyter Notebook ou em um ambiente Python compatível.

## Arquivos no Repositório

- `inicial.ipynb`: Notebook principal com o código do projeto.
- `clientes.csv`: Base de dados com informações dos clientes.
- `novos_clientes.csv`: Base de dados com informações de novos clientes para previsão.

## Contato

Caso tenha dúvidas ou sugestões, entre em contato comigo pelo [LinkedIn](https://www.linkedin.com/in/guisandoli/) ou envie um e-mail para **guisandolidna@gmail.com**.
```
