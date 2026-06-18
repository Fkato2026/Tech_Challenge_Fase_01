# Tech Challenge - Fase 1 | Data Analytics (FIAP Postech)

## 📌 Comportamento do Consumidor de Alto Valor no E-commerce: Evidências do Caso Olist

### Análise Multidimensional de Operações, Logística e Satisfação do Cliente (2016-2018)

Este repositório contém o desenvolvimento do **Tech Challenge (Fase 1)** do curso de Data Analytics da FIAP Postech (Turma 14DTAT - Grupo 10).

O projeto apresenta um diagnóstico analítico e estratégico baseado em aproximadamente **100 mil pedidos da plataforma Olist**, cobrindo o período entre 2016 e 2018 e explorando o comportamento do consumidor de alto valor dentro do ecossistema do e-commerce.

---

## 🎯 Objetivo do Projeto

Responder à seguinte pergunta de negócio:

> **Qual é o comportamento do consumidor de alto valor dentro do ecossistema da Olist?**

Por meio do modelo **RFM (Recência, Frequência e Valor Monetário)**, buscamos identificar os clientes mais valiosos e compreender seus padrões de consumo, categorias de interesse, distribuição geográfica e sensibilidade a falhas operacionais.

---

## 📊 Estrutura Multidimensional do Diagnóstico

A análise foi desenvolvida em cinco perspectivas principais:

1. **Núcleo Transacional**  
   Correlação entre pedidos e itens vendidos.

2. **Geografia**  
   Distribuição e localização dos clientes e sellers.

3. **Produtos**  
   Peso, volume e categorias comercializadas.

4. **Financeiro**  
   Faturamento, meios de pagamento e parcelamento.

5. **Satisfação**  
   Avaliações dos clientes e análise dos comentários.

---

## 💡 Principais Insights de Negócio

### 🛒 Perfil do Cliente Premium

Os consumidores de maior valor apresentam baixa frequência de compra, porém elevado ticket médio, concentrando suas aquisições em categorias de maior valor agregado.

### 💰 Volume x Receita

Apesar da categoria `cama_mesa_banho` liderar em volume de pedidos, as categorias:

- `beleza_saude`
- `relogios_presentes`

são responsáveis por grande parte do faturamento da plataforma.

### 🌎 Concentração Geográfica

O estado de São Paulo concentra aproximadamente R$ 6 milhões em receita, favorecido pela proximidade logística com os sellers.

Rotas mais longas representam desafios operacionais importantes, principalmente para clientes premium.

### ⭐ Impacto dos Atrasos

- Pedidos entregues dentro do prazo: **4,18 estrelas**
- Pedidos entregues com atraso: **2,11 estrelas**

Os resultados evidenciam a relação direta entre eficiência logística e satisfação do cliente.

---

## 🛠️ Tecnologias Utilizadas

- Python 3
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Plotly
- Jupyter Notebook

---

## 📁 Estrutura do Repositório

```text
TECH_CHALLENGE_FASE_01
│
├── DataSet/
│   ├── olist_customers_dataset.csv
│   ├── olist_geolocation_dataset.csv
│   ├── olist_order_items_dataset.csv
│   ├── olist_order_payments_dataset.csv
│   ├── olist_order_reviews_dataset.csv
│   ├── olist_orders_dataset.csv
│   ├── olist_products_dataset.csv
│   ├── olist_sellers_dataset.csv
│   └── product_category_name_translation.csv
│
├── Notebook/
│   └── tech_challenge_fase_01.ipynb
│
├── .gitignore
├── requirements.txt 
└── README.md
```

---

## 📈 Principais Conclusões

- O consumidor de alto valor possui baixa recorrência e elevado ticket médio;
- O faturamento é impulsionado por categorias de maior valor agregado;
- A logística exerce influência direta na experiência do cliente;
- Atrasos impactam significativamente a satisfação dos consumidores;
- Regiões mais distantes representam desafios operacionais importantes.

---

## 📚 Base de Dados

**Brazilian E-Commerce Public Dataset by Olist**

https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce

---

## 👥 Integrantes

**FIAP Pós-Tech em Data Analytics – Grupo 10**

- Fabio Eiji Kato
- (Adicionar demais integrantes)

---

## 📌 Considerações Finais

Este projeto demonstra a aplicação prática de técnicas de análise exploratória, engenharia de dados e geração de insights estratégicos, evidenciando como dados operacionais podem ser transformados em informações relevantes para apoiar a tomada de decisão.