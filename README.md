## Previsão de Churn em E-Commerce

### Descrição

Este projeto tem como objetivo prever a churn (cancelamento) de clientes em um e-commerce. Para isso, foram utilizados dados do Kaggle ([https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce)) e as seguintes ferramentas:

* **Análise Exploratória de Dados (EDA)**: para entender as características dos clientes, pedidos e itens dos pedidos.
* **Modelos de classificação**: XGBClassifier, LGBMClassifier, CatBoostClassifier e LogisticRegression.
* **Ajuste de hiperparâmetros**: para otimizar o modelo XGBClassifier e obter o melhor ROC AUC.

### Resultados

A melhor classificação foi obtida com o **XGBClassifier** após o ajuste de hiperparâmetros. A média de **ROC AUC** final foi de **0.7077**.

### Estrutura do projeto

```
├── README.md
├── data
│   ├── olist_customers_dataset.csv
│   ├── olist_order_items_dataset.csv
│   ├── olist_orders_dataset.csv
├── notebooks
│   ├── previsao_churn_ecommerce.ipynb
├── requirements.txt
```

### Como usar

1. Clone o repositório:

```
git clone https://github.com/h3nriq/previsao-churn
```

2. Instale as dependências:

```
pip install -r requirements.txt
```

3. Execute o notebook:

* **previsao_churn_ecommerce.ipynb**

### Observações

* Este projeto é apenas um exemplo. Você pode adaptá-lo às suas necessidades.
* Os dados utilizados são de um e-commerce brasileiro. Se você estiver usando dados de outro país, os resultados podem ser diferentes.
