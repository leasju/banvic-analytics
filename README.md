# 🏦 BanVic - Desafio de Engenharia de Analytics

Este repositório contém a solução para o **Desafio de Engenharia de Analytics - BanVic**.  
O objetivo foi analisar dados bancários (agências, clientes, colaboradores, contas, propostas de crédito e transações), criar indicadores de negócio e propor insights para apoiar decisões estratégicas.

---

## 📌 Estrutura do Projeto
- `notebooks/`: Jupyter Notebook principal com toda a análise exploratória (EDA), tratamento de dados e geração de métricas.
- `dados_exportados/`: Arquivos `.csv` tratados e derivados da análise.
- `img/graficos/`: Gráficos finais usados no relatório/dashboard.
- `report/`: Relatório final em PDF contendo as análises, KPIs e recomendações.
- `requirements.txt`: Lista de dependências para reprodução do ambiente.

---

## 📊 Análises Realizadas
- **Agências**: ranking de desempenho, top 3 melhores e piores.
- **Clientes**: perfil etário, distribuição por estado.
- **Contas**: análise do saldo total e distribuição.
- **Propostas de Crédito**: taxa de aprovação, distribuição de valores.
- **Transações**: comportamento por dia da semana, meses pares vs ímpares, dias úteis vs finais de semana.
- **Dimensão de Datas**: base estruturada para análises temporais.
- **Dados externos**: integração da cotação do dólar (Banco Central) e análise de correlação com movimentações.

---

## 📈 KPIs Principais
- Quantidade total de transações  
- Valor total transacionado  
- Valor médio das transações  
- Taxa de aprovação de propostas de crédito  
- Número de clientes únicos  
- Número de agências únicas  

---

## 🚀 Ferramentas Utilizadas
- **Python**: Pandas, Seaborn, Matplotlib, NumPy  
- **Jupyter Notebook**: desenvolvimento e documentação  
- **Banco Central do Brasil API**: dados de câmbio (USD)  
- **Relatório em PDF**: geração e organização dos insights finais  

---

## 📂 Como Reproduzir
1. Clone o repositório:
   ```bash
   git clone https://github.com/<seu-usuario>/banvic-analytics-desafio.git
   cd banvic-analytics-desafio
