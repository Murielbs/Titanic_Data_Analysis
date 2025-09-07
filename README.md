# Titanic_Data_Analysis

Este projeto tem como objetivo analisar os dados dos passageiros do Titanic, identificando os fatores que mais influenciaram na **sobrevivência**.  
Utilizamos técnicas de **tratamento de dados**, **análise descritiva** e **visualização gráfica** para extrair insights a partir do dataset clássico do Titanic.

---

## 👨‍🏫 Integrantes do Grupo
- Muriel  
- Vinicius  
- Edmael  
- Gabriel  
- Carol  

---

## 📊 Etapas da Análise

1. **Tratamento de Dados**
   - Preenchimento de valores ausentes (mediana para idade, moda/Unknown para outras variáveis).
   - Transformação de variáveis categóricas em numéricas com `LabelEncoder`.
   - Padronização de dados com `StandardScaler`.

2. **Análise Descritiva**
   - Cálculo de média, mediana, moda, desvio padrão e frequências.
   - Resumo estatístico com `.describe()`.

3. **Visualizações**
   - Histograma da distribuição de idades.  
   - Boxplot comparando idade por sobrevivência.  
   - Gráfico de dispersão (idade × tarifa por sobrevivência).  
   - Gráfico de pizza/barras mostrando a proporção de sobreviventes.  