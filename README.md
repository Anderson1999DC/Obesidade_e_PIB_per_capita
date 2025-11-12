# 🌎 Análise da Relação entre Obesidade e PIB Per Capita (1975–2016)

Este projeto tem como objetivo investigar **se existe correlação entre o crescimento econômico e os índices de obesidade** em diferentes países ao longo das últimas décadas.

A análise foi baseada em duas bases públicas do **Kaggle**:

- [Obesity among adults by country (1975–2016)](https://www.kaggle.com/amanarora/obesity-among-adults-by-country-19752016/)
- [GDP Per Person (1901–2011)](https://www.kaggle.com/divyansh22/gdp-per-person-19012011)

---

## 🎯 Objetivo do Projeto

O estudo busca compreender **como o aumento do PIB per capita pode estar relacionado à evolução da obesidade mundial**, considerando:

- Diferenças regionais e socioeconômicas;
- Diferenças entre gêneros;
- Evolução temporal das duas variáveis entre 1975 e 2016.

---

## 🧠 Técnicas e Bibliotecas Utilizadas

- **Pandas** → Leitura, limpeza e manipulação de dados;  
- **NumPy** → Cálculos estatísticos e tratamento numérico;  
- **Matplotlib** e **Plotly** → Visualizações e comparações interativas;  
- **Correlação de Pearson** → Identificação de relações entre PIB e obesidade;  
- **Tratamento de dados faltantes e padronização de tipos** → Garantia de consistência antes da análise;  
- **Integração entre bases distintas** → Junção e filtragem de dados por país e ano.

---

## ⚙️ Etapas da Análise

1. **Coleta e importação de dados**
   - Leitura dos arquivos CSV com informações de obesidade e PIB per capita.
2. **Limpeza e padronização**
   - Remoção de colunas redundantes;
   - Conversão de valores para tipo numérico;
   - Exclusão de registros incompletos;
   - Definição do índice temporal.
3. **Integração das bases**
   - Junção entre os datasets por país e ano.
4. **Análise exploratória**
   - Estatísticas descritivas;
   - Identificação de outliers e padrões;
   - Visualização das tendências globais.
5. **Análise de correlação**
   - Aplicação do **coeficiente de Pearson** para medir a força da relação entre o PIB per capita e a taxa de obesidade.
6. **Visualização dos resultados**
   - Gráficos de dispersão, séries temporais e mapas interativos com destaque para os países com maiores índices.

---

## 📈 Principais Descobertas

- Existe **correlação positiva moderada** entre o aumento do PIB per capita e o crescimento das taxas de obesidade ao longo das décadas.  
- Países com **maior desenvolvimento econômico** apresentaram **maiores níveis de obesidade**, indicando influência de fatores como consumo de ultraprocessados e estilo de vida urbano.  
- Em países de renda mais baixa, a obesidade ainda é um problema crescente, mas em ritmo mais lento.  
- **Diferenças entre gêneros** foram observadas, com **maior prevalência de obesidade em mulheres** em diversas regiões.  

---

🎥 [Visualizar notebook completo com gráficos interativos no nbviewer](https://nbviewer.org/github/Anderson1999DC/Obesidade_e_PIB_per_capita/blob/main/Analise_de_correlacao_PIB_e_obesidade.ipynb)

---

## 🧩 Estrutura do Projeto

Obesidade_e_PIB_per_capita/
│
├── datasets/
│ ├── obesity.csv
│ ├── gdp.csv
│
├── Analise_de_correlacao_PIB_e_obesidade.ipynb
├── requirements.txt
└── README.md

---

## 💻 Como Executar o Projeto

1. Clone o repositório:
   ```bash
   git clone https://github.com/Anderson1999DC/Obesidade_e_PIB_per_capita.git
2. Acesse a pasta do projeto:
   cd Obesidade_e_PIB_per_capita

3. Instale as dependências
   pip install -r requirements.txt
4. Execute o notebook:   
   Analise_de_correlacao_PIB_e_obesidade.ipynb


---

📚 Conclusão

O estudo demonstra que a evolução econômica tende a acompanhar o aumento das taxas de obesidade, revelando que o crescimento do PIB não implica necessariamente em melhora de qualidade de vida.
Essa relação reforça a importância de políticas públicas voltadas à educação alimentar e ao acesso equilibrado à nutrição, principalmente em países em desenvolvimento.

---

## 👨‍💻 Autor

**Anderson Coelho**  
📊 Analista de Dados | Python | Power BI | SQL | Excel  

🔗 [LinkedIn](https://www.linkedin.com/in/anderson-coelho-42671634a/)  
💼 [Portfólio no GitHub](https://github.com/Anderson1999DC?tab=repositories)
