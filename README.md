# 📊 Dashboard de Análise de Salários na Área de Dados

Este projeto é um dashboard interativo desenvolvido com **Python** e **Streamlit** para analisar salários na área de Dados ao longo dos anos, considerando fatores como nível de experiência, tipo de contrato, tamanho da empresa, trabalho remoto e localização geográfica.

O objetivo é transformar um dataset bruto em **insights visuais claros**, aplicando conceitos de análise de dados e visualização.

🔗 **Aplicação online:**  
https://dashboard-salarios-ds.streamlit.app/

---

## 🧠 O que este projeto faz

- Analisa salários anuais (em USD) na área de Data Science
- Permite filtragem por:
  - Ano
  - Nível de experiência
  - Tipo de contrato
  - Tamanho da empresa
- Exibe:
  - Salário médio e máximo
  - Cargo mais frequente
  - Distribuição salarial
  - Top cargos por salário médio
  - Proporção de trabalho remoto
  - Mapa mundial com salário médio de Data Scientists por país

---

## 🛠️ Tecnologias utilizadas

- **Python**
- **Pandas**
- **Streamlit**
- **Plotly**
- **PyArrow**
- **Git & GitHub**
- **Streamlit Cloud**

---

## ▶️ Como rodar o projeto localmente

### 1️⃣ Clonar o repositório
```bash
git clone https://github.com/tiferreira-dev/Analise-de-dados-salarios-DataScience.git
cd Analise-de-dados-salarios-DataScience

2️⃣ Criar e ativar ambiente virtual
python -m venv venv
venv\Scripts\activate  # Windows


3️⃣ Instalar as dependências
pip install -r requirements.txt

4️⃣ Executar o app
streamlit run app.py

📊 Dataset

O dataset contém informações sobre salários na área de dados, incluindo:

Ano

Cargo

Nível de experiência

Tipo de contrato

Salário anual em USD

Tipo de trabalho (remoto, híbrido, presencial)

País de residência

Tamanho da empresa

Os dados passaram por um processo de limpeza e padronização antes da análise.

🚀 Deploy

A aplicação foi deployada utilizando o Streamlit Cloud, integrado diretamente ao repositório do GitHub.
Qualquer atualização no código gera automaticamente um novo deploy.

📌 Próximos passos

Análises estatísticas mais avançadas

Comparação salarial entre países

Modelos preditivos de salário

Exportação de gráficos e relatórios

Integração com banco de dados

👨‍💻 Autor

Ygor Ferreira
Python Developer | Data Analysis | Data Science

🔗 GitHub: https://github.com/tiferreira-dev