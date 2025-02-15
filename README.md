# Projeto de Análise de Dados Everything Plus

## Descrição do Projeto
Este projeto consiste em uma análise de dados da loja online fictícia Everything Plus, especializada na venda de utensílios domésticos. O objetivo principal da análise é identificar estratégias para melhorar as vendas da empresa, utilizando ofertas personalizadas para diferentes grupos de clientes por meio de uma segmentação de mercado eficaz.
A empresa deseja otimizar suas estratégias de promoção e propaganda, focando na criação de ofertas que atendam às necessidades e preferências específicas de seus consumidores. Para alcançar esse objetivo, o setor de marketing e o setor comercial da empresa serão responsáveis por conduzir a análise e identificar o melhor caminho para aumentar a atratividade das ofertas e, consequentemente, as vendas da loja.
A análise envolverá a segmentação dos clientes, com base em comportamentos de compra e outras variáveis relevantes. O intuito é entender quais grupos de consumidores têm características ou necessidades similares, para que a empresa possa criar ofertas direcionadas e mais eficazes. Além disso, será realizada uma análise de vendas e comportamento do consumidor, com o objetivo de estudar o histórico de compras dos clientes e identificar quais produtos são mais populares, quais estratégias de marketing têm se mostrado mais eficientes, e quais fatores influenciam as decisões de compra.
A partir desses dados, o projeto buscará desenvolver estratégias de promoção personalizadas, com o foco em criar campanhas de marketing direcionadas, como promoções especiais e ofertas personalizadas. Essas ações visam aumentar a conversão de clientes e fomentar a fidelização. Por fim, será realizada uma avaliação dos resultados, analisando campanhas anteriores para ajustar as estratégias e maximizar o impacto das futuras promoções.
Essa análise será crucial para que a Everything Plus adote abordagens mais assertivas e personalizadas, garantindo um aumento nas vendas e uma melhor experiência para os consumidores, além de posicionar a empresa de forma mais competitiva no mercado.

## As tarefas são:
- Análise Exploratória de Dados (EDA): A análise exploratória de dados (EDA) será realizada inicialmente para entender a estrutura do banco de dados e as características dos dados disponíveis. Isso incluirá a identificação de padrões, tendências e a verificação da qualidade dos dados, como valores ausentes e inconsistências. A EDA ajudará a detectar relações entre variáveis importantes, como produtos mais comprados, comportamento de compra dos clientes e a sazonalidade das vendas.
- Segmentação dos Usuários com Base no Histórico de Compras: A segmentação de clientes será feita com base no histórico de compras, utilizando técnicas de agrupamento, como K-means ou análise de clusters. O objetivo é dividir os clientes em grupos distintos, com base em características como frequência de compra, valor gasto, tipos de produtos adquiridos, entre outros. Isso permitirá identificar grupos de consumidores com comportamentos semelhantes, facilitando a criação de ofertas mais direcionadas e personalizadas.
- Desenvolver Ofertas Personalizadas para Diferentes Usuários: Com a segmentação dos clientes realizada, será possível criar ofertas personalizadas para cada grupo. Por exemplo, clientes que compram com frequência podem receber descontos em novos produtos ou ofertas de fidelidade, enquanto clientes que compram de maneira esporádica podem ser incentivados com promoções de produtos complementares. O objetivo é aumentar a conversão e a fidelidade dos clientes, tornando as campanhas de marketing mais eficazes e direcionadas.
- Teste de Hipótese Estatística: Será realizado um teste de hipótese estatística para verificar a eficácia das ofertas personalizadas. Isso incluirá a formulação de hipóteses, como "Ofertas personalizadas aumentam a taxa de conversão em X% em relação às ofertas genéricas", e a aplicação de testes como o teste T ou o teste de qui-quadrado para comparar os resultados. O teste ajudará a validar se as mudanças nas estratégias de marketing estão gerando os resultados esperados ou se ajustes adicionais são necessários.

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
- Python: A principal linguagem utilizada para a análise de dados devido à sua flexibilidade e ampla gama de bibliotecas para análise e visualização de dados. Python é uma escolha popular devido à sua facilidade de uso e suporte a diversas bibliotecas especializadas.
- Pandas: Biblioteca fundamental para manipulação e análise de dados. Pandas permite a organização, limpeza, transformação e análise de dados de forma eficiente, trabalhando com estruturas como DataFrames que facilitam o manuseio de grandes volumes de dados.
- Matplotlib: Biblioteca usada para criar gráficos em Python. Matplotlib é versátil e permite a criação de gráficos estáticos, interativos e animados, sendo essencial para a visualização de dados e para a geração de gráficos personalizáveis.
- Seaborn: Biblioteca baseada no Matplotlib, mas com recursos adicionais para facilitar a criação de gráficos mais complexos e atraentes. Seaborn é usado para visualização de dados estatísticos, proporcionando gráficos com uma aparência mais refinada e integração direta com Pandas.
- Datetime: Biblioteca para manipulação de datas e horas. Permite que você extraia, modifique e compare dados de datas de maneira eficaz, o que é útil em análises temporais e de séries históricas.
- Sklearn: Biblioteca de aprendizado de máquina que oferece ferramentas para modelagem de dados, como algoritmos de classificação, regressão e agrupamento (clustering). Sklearn é amplamente utilizado para aplicar modelos preditivos e técnicas de machine learning em projetos de dados.
- Scipy.cluster.hierarchy: Parte da biblioteca SciPy, esta ferramenta é usada para criar agrupamentos hierárquicos de dados. Através de métodos como aglomeração (agglomerative clustering), é possível identificar padrões e estruturar os dados em grupos, facilitando a segmentação e análise de comportamentos semelhantes.

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
- Grandes quantidades vendidas de produtos de baixo valor: A análise indica que a empresa tem uma alta rotatividade de produtos com preços baixos, o que gera uma grande quantidade de vendas, mas com margens reduzidas. Esse dado é importante para estratégias de marketing, pois pode indicar a necessidade de promover mais produtos com maior valor agregado para aumentar o lucro por unidade.
- Média de 4 compras por ano: A média de compras anuais dos clientes revela um comportamento de compra regular, com um foco na retenção de clientes e não em compras esporádicas. Isso sugere que é importante criar programas de fidelidade ou promoções periódicas para manter o interesse dos clientes ao longo do ano.
- Clientes mais rentáveis são os que fazem muitas compras: A análise revela que os clientes que compram mais frequentemente geram maior receita para a empresa. Com isso, uma estratégia eficiente seria focar em ações de retenção e fidelização para esses clientes, bem como oferecer vantagens para compras repetidas, como descontos progressivos ou promoções exclusivas.
- Compras aumentam do meio do ano para frente: Os dados indicam uma tendência sazonal, com um aumento nas compras a partir do meio do ano. A empresa pode aproveitar esse pico para planejar campanhas promocionais mais agressivas e melhor posicionar seus produtos nos meses de maior demanda.
- Final do ano é o período com mais vendas e faturamento: O período de fim de ano é um ponto de grande interesse para a empresa, com vendas e faturamento mais elevados. Estratégias específicas, como promoções temáticas, descontos de final de ano ou campanhas publicitárias, podem ser implantadas para maximizar o lucro durante esse período.
- Variação nas métricas entre dias, meses ou horas do dia, com picos de vendas: Os dados mostram que há flutuação significativa nas vendas, pedidos e faturamento dependendo do período do dia, do mês ou até mesmo do dia da semana. Isso oferece uma oportunidade para ajustar a estratégia de marketing e alocar recursos de forma mais eficiente durante os horários e datas de pico.
- Análise da data da última compra dos clientes: Ao saber a data da última compra de cada cliente, é possível segmentá-los e identificar os que são mais fiéis, os que estão prestes a abandonar a empresa e os recém-chegados. Isso permite que a empresa direcione seus investimentos em marketing e atendimento de forma mais eficaz, criando campanhas para reter clientes próximos da inatividade e atrair novos compradores.
 
## Aprendizados
- Análise de dados: O processo de examinar e interpretar grandes volumes de dados para extrair informações úteis. A análise de dados permite compreender o comportamento dos clientes, identificar padrões e tomar decisões informadas para melhorar o desempenho da empresa.
- Limpeza de dados: Refere-se ao processo de corrigir ou remover dados inconsistentes, incorretos ou incompletos de um conjunto de dados. Esse passo é essencial para garantir que as análises sejam precisas e confiáveis, evitando a distorção de resultados devido a erros nos dados.
- Análise de funil de vendas: A análise de funil de vendas consiste em acompanhar as etapas do processo de compra, desde o primeiro contato com o cliente até a conversão em venda. Ela ajuda a entender onde os clientes abandonam o processo e permite implementar ações para melhorar a conversão em cada etapa do funil.
- Construção e análise de gráficos: Criar representações visuais dos dados para facilitar a compreensão de padrões, tendências e insights. Gráficos bem construídos ajudam a comunicar claramente os resultados e facilitam a análise das informações de maneira intuitiva.
- Análise exploratória de dados (EDA): A EDA é um processo inicial de análise de dados que envolve examinar as variáveis do conjunto de dados, buscar padrões e identificar possíveis relações. Essa etapa é crucial para entender os dados antes de aplicar técnicas mais avançadas de análise, como modelos preditivos.
- Formulação de hipóteses: A formulação de hipóteses envolve criar suposições sobre os dados com base no entendimento inicial e nas perguntas de pesquisa. Essas hipóteses guiam a análise, ajudando a testar teorias sobre como diferentes fatores podem influenciar o comportamento ou o desempenho do negócio.

## Contexto real
- Empresas que desejam entender melhor o comportamento de seus clientes: Organizações que buscam insights profundos sobre as preferências, necessidades e comportamentos de compra dos consumidores, a fim de otimizar suas estratégias de marketing, vendas e atendimento ao cliente.
- Novas empresas que desejam entender melhor o mercado: Startups ou empresas em fase inicial que precisam compreender as dinâmicas do mercado, identificar nichos de clientes e entender a concorrência para tomar decisões estratégicas e posicionar seus produtos ou serviços de forma eficaz.
- Analistas de dados que querem entender melhor o mercado: Profissionais especializados em análise de dados que buscam aplicar técnicas analíticas para explorar tendências de mercado, identificar padrões de comportamento e extrair informações valiosas que possam informar decisões de negócios.
- Empresas de pesquisa que querem saber mais a opinião dos clientes de alguma empresa: Organizações especializadas em pesquisa de mercado que realizam estudos sobre a percepção e a satisfação dos consumidores, ajudando empresas a aprimorar seus produtos, serviços e estratégias de marketing com base no feedback do cliente.
- Empresas de marketing que querem oferecer uma melhor experiência aos clientes: Agências de marketing que visam melhorar a experiência do cliente, personalizar as ofertas, otimizar campanhas e fidelizar consumidores, utilizando dados e insights para tomar decisões estratégicas mais precisas e eficazes.

## Como executar o Projeto
- Clone o repositório
- Navegue até o diretório do projeto
- Abra o projeto no seu IDE favorito
- Instale as dependências
- Execute o script principal
