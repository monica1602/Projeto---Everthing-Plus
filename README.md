# Projeto de Análise de Dados Everything Plus

## Descrição do Projeto
Este projeto consiste em uma análise de dados da loja Everything Plus, uma loja online fictícia que vende utensílios domésticos. A empresa deseja melhorar suas vendas através de ofertas personalizadas para diferentes usuários por meio da segmentação de clientes. O setor de marketing e o setor comercial precisam fazer uma análise para decidir qual a melhor maneira de realizar promoções e propagandas

## As tarefas são:
- Análise exploratória de dados
- Segmentação dos usuários com base no histórico de compras
- Desenvolver ofertas personalizadas para diferentes usuários
- Teste de hipótese estatística

## Dicionário de dados
- ecommerce_dataset_us.csv: contém o histórico de transações
  - 'InvoiceNo': identificador de item
  - 'StockCode': nome de item
  - 'Description': nome de item
  - 'Quantity': quantidade de itens no pedido
  - 'InvoiceDate': data do pedido
  - 'UnitPrice': preço do item
  - 'CustomerId': identificação do cliente que fez o pedido

## Ferramentas e Bilbiotecas utilizadas
  - Pyhton: Linguagem principal utilizada para análise
  - Pandas: Biblioteca para maniupulação e análise de dados
  - Matplotlib: Biblioteca para criação de gráficos
  - Seaborn: Biblioteca de visualizações de dados
  - Datetime: Biblioteca para manipulação de datas e horas
  - Sklearn: Biblioteca utilizada para agrupar os dados com machine learn
  - Scipy.cluster.hierarchy: Biblioteca para criação de agrupamentos com machine learning

## Imagens

### Tabelas vendas
<img src="https://github.com/user-attachments/assets/de1d88ec-7378-46ac-b925-69d8b5ec6e3d" alt="Projeto Final"/>

### Agrupamento por data e número de pedidos
<img src="https://github.com/user-attachments/assets/ba03a525-46f2-4799-827e-c9aa86d81716" alt="Projeto Final" width="200"/>

### Agrupamento por data e número de usuários
<img src="https://github.com/user-attachments/assets/b55342ae-5192-433b-a727-0949ad915e37" alt="Projeto Final" width="200"/>

### Agrupamento por data e soma de quantidade pedida
<img src="https://github.com/user-attachments/assets/c9c0aeed-2a23-4715-ac4f-2f675681f5b6" alt="Projeto Final" width="200"/>

### Agrupamento por data e soma do valor de todos os itens
<img src="https://github.com/user-attachments/assets/074e5e9a-1adc-4b1d-9881-44b9273dde2e" alt="Projeto Final" width="200"/>

### Agrupamento por dia do mês e número de pedidos
<img src="https://github.com/user-attachments/assets/4c6b03e5-c8d3-4164-9546-46f173226378" alt="Projeto Final" width="200"/>

### Agrupamento por dia do mês e soma da quantidade pedida
<img src="https://github.com/user-attachments/assets/b2ef1aef-447a-4ff8-aef3-6559eb15e149" alt="Projeto Final" width="200"/>

### Agrupamento por dia do mês e número de usuários
<img src="https://github.com/user-attachments/assets/dadd4856-5ce4-443f-ab96-15d397ccbe1f" alt="Projeto Final" width="200"/>

### Agrupamento por dia do mês e soma do valor
<img src="https://github.com/user-attachments/assets/beb9ed76-a8db-4e2a-890d-26ca41358030" alt="Projeto Final" width="200"/>

### Agrupamento por hora do dia e número de pedido
<img src="https://github.com/user-attachments/assets/0aeb408f-9efe-4ade-85e3-8928bf19132b" alt="Projeto Final" width="200"/>

### Agrupamento por hora do dia e quantidade pedida
<img src="https://github.com/user-attachments/assets/4f4ff937-662e-4ed8-9223-8b9c20583e2f" alt="Projeto Final" width="200"/>

### Agrupamento por hora do dia e número de usuários
<img src="https://github.com/user-attachments/assets/caf956d2-04b3-43f4-a466-7332238eb2e0" alt="Projeto Final" width="200"/>

### Agrupamento por hora do dia e valor total
<img src="https://github.com/user-attachments/assets/d1c8cd1b-d490-4b46-8c83-c21d1adb9992" alt="Projeto Final" width="200"/>

### Agrupamento por mês do ano e número de pedidos
<img src="https://github.com/user-attachments/assets/ec7eaffb-812e-44f7-a86b-a0b40c90d6de" alt="Projeto Final" width="200"/>

### Agrupamento por mês do ano e quantidade pedida
<img src="https://github.com/user-attachments/assets/2a86d07f-b30c-46a6-9304-c739ddb7bf5e" alt="Projeto Final" width="200"/>

### Agrupamento por mês do ano e número de usuários
<img src="https://github.com/user-attachments/assets/6853cc5f-15a4-4f46-a2cf-723e1c7bec39" alt="Projeto Final" width="200"/>

### Agrupamento por mês do ano e valor total
<img src="https://github.com/user-attachments/assets/135eff68-faf8-4959-b241-2a185f350e16" alt="Projeto Final" width="200"/>

### Segmentação RFM classificação
<img src="https://github.com/user-attachments/assets/21d9e430-68b5-448a-94cb-57c5339007cf" alt="Projeto Final" width="200"/>

### Segmentação RFM time
<img src="https://github.com/user-attachments/assets/39fe98c5-1b5a-42dd-9c74-dadcabae8602" alt="Projeto Final" width="200"/>

### Segmentação RFM total
<img src="https://github.com/user-attachments/assets/1712cbd7-2b0f-4c2c-9381-97d96dadf008" alt="Projeto Final" width="200"/>

## Resultados
  - Grandes quantidades vendidas de produtos de baixo valor
  - Média de 4 compras por ano
  - Os clientes mais rentáveis são os que fazem muitas compras
  - As compras aumentam do meio do ano para frente
  - O final do ano é o período com mais vendas e faturamento
  - A quantidade de clientes, de pedidos, a quantidade e o valor total podem variar muito entre os dias, meses ou horas do dia, porém em todos os casos existem picos. Ou seja, é possível saber quando e onde investir mais
  - Sabendo a data da última compra de cada cliente é possível saber quasi clientes possivelmente já perdemos, quais mais compram, quais são novos. E com isso saber onde e quando investir  
 
## Aprendizados
- Análise de dados
- Limpeza de dados
- Análise de funil de vendas
- Contrução e análise de gráficos
- Análise exploratória de dados
- Formulação de hipóteses

## Contexto real
- Empresas que desejam entender melhor o comportamento de seus clientes
- Novas empresas que desejam entender melhor o mercado
- Analistas de dados que querem entender melhor o mercado
- Empresas de pesquisa que querem saber mais a opnião dos clientes de alguma empresa
- Empresas de marketing que querem oferecer uma melhor experiência aos clientes

## Como executar o Projeto
- Clone o repositório
- Navegue até o diretório do projeto
- Abra o projeto no seu IDE favorito
- Instale as dependências
- Execute o script principal
