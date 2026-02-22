
```markdown
# 📊 Desafio TelecomX – Análise de Evasão de Clientes (Churn)

## 1. Introdução
Este projeto tem como objetivo analisar os fatores que influenciam a **evasão de clientes (churn)** em uma empresa de telecomunicações.  
A evasão impacta diretamente na receita e na fidelização, sendo essencial identificar padrões e variáveis que ajudam a prever quais clientes têm maior probabilidade de cancelar seus serviços.

---

## 2. Limpeza e Tratamento de Dados
- Importação dos dados em formato JSON.  
- Flatten das colunas aninhadas (`customer`, `phone`, `internet`, `account`, `Charges`).  
- Remoção de duplicados.  
- Tratamento de valores nulos (mediana para numéricos, “Desconhecido” para categóricos).  
- Padronização de categorias (`Gender`, `ServiceType`, `ContractType`).  
- Normalização de datas.  
- Criação da coluna **`Contas_Diarias`** a partir do faturamento mensal.

---

## 3. Análise Exploratória de Dados (EDA)
- **Distribuição de churn**: proporção de clientes que permaneceram vs. cancelaram.  
- **Variáveis categóricas**: análise por gênero, tipo de contrato e método de pagamento.  
- **Variáveis numéricas**: análise de `TotalCharges`, tempo de contrato e faturamento diário.  
- Visualizações com gráficos de barras, pizza, boxplots e histogramas.

---

## 4. Conclusões e Insights
- Contratos mensais apresentam maior evasão.  
- Métodos de pagamento menos práticos estão associados a maior churn.  
- Clientes com **baixo gasto acumulado** ou **contratos curtos** são mais propensos a cancelar.  
- Planos mais baratos mostram maior sensibilidade ao preço.

---

## 5. Recomendações
- Incentivar contratos de longo prazo com benefícios exclusivos.  
- Oferecer vantagens financeiras para clientes de planos mais baratos.  
- Melhorar a experiência de pagamento, incentivando métodos digitais.  
- Monitorar clientes com baixo gasto acumulado e criar campanhas de retenção específicas.

---

## 6. Próximos Passos
- Explorar correlações entre variáveis numéricas e churn.  
- Construir modelos preditivos de machine learning para prever evasão.  
- Implementar dashboards interativos para acompanhamento contínuo.

---

## 🚀 Acesse o Notebook no Google Colab
Clique no link abaixo para abrir e executar o notebook diretamente no Google Colab:

[![Abrir no Colab](Cópia_de_Desafio_TelecomX_BR.ipynb)

---

### 📂 Estrutura do Repositório
- `Desafio TelecomX BR.ipynb` → notebook com toda a análise. 

-`README.md` → resumo do projeto (este arquivo).  

---

👩‍💻 Desenvolvido por Maria no desafio **TelecomX BR**.


