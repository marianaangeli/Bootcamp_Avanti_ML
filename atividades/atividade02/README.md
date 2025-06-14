# 🧠 Fundamentos com Insights Práticos

[![Python](https://img.shields.io/badge/Python-3.7%2B-blue?style=flat-square&logo=python)](https://python.org)
[![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas)](https://pandas.pydata.org)
[![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy)](https://numpy.org)

> **Algoritmos fundamentais + análise crítica de métodos estatísticos**

## 🎯 O que tem aqui

**Algoritmos Básicos:**
- Filtro de ímpares e números primos
- Diferença simétrica entre listas  
- Segundo maior elemento
- Ordenação de tuplas por nome

**Análise de Dados:**
- Detecção de outliers (Desvio Padrão vs IQR)
- Concatenação de DataFrames
- Tratamento de valores NaN

## 💡 Insights Valiosos (O diferencial deste notebook)

### 🎯 **Outliers: Contexto é TUDO**
```python
# Exemplo prático: altura de pessoas
dados = [1.55, 1.60, 1.62, 1.58, 1.90, 3.00]
```

**Por que 3.00m não foi detectado pelo desvio padrão?**
- O próprio outlier "puxa" a média e desvio para cima
- Ele acaba "se protegendo de si mesmo" 
- **IQR é mais robusto** para amostras pequenas

**✅ Quando MANTER outliers:**
- Valores extremos mas **possíveis** (pessoa com 1.90m em população de 1.60m)
- Representam diversidade real dos dados

**❌ Quando REMOVER outliers:**
- Valores **impossíveis** (altura 3.00m ou -2.00m)
- Erros de digitação/sensores que comprometem análise

### 📊 **Média vs Mediana: Escolha Inteligente**
- **Média**: Dados simétricos, sem outliers significativos
- **Mediana**: Presença de outliers ou distribuição assimétrica
- **Contexto decide**: Não existe "melhor método universal"

### 🕳️ **NaN: Nem sempre é problema**
**Para dados numéricos:**
- Média → dados simétricos
- Mediana → outliers presentes  
- Moda → valores repetitivos

**Para categóricos:**
- Moda (categoria mais comum)
- Categoria padrão: "indefinido", "não informado"

> **💡 Insight chave**: Em alguns casos, é melhor manter como NaN para modelar/analisar os próprios dados ausentes!

## 🔍 Comparação Prática: IQR vs Desvio Padrão

| Método | Quando Usar | Vantagem | Desvantagem |
|--------|-------------|----------|-------------|
| **Desvio Padrão** | Dados normais, amostras grandes | Rápido, intuitivo | Sensível aos próprios outliers |
| **IQR** | Amostras pequenas, outliers presentes | Robusto, não afetado por extremos | Pode ser conservador demais |

## 🚀 Como usar

```bash
# Clone e execute
git clone https://github.com/seu-usuario/atividade02-ml.git
jupyter notebook Atividade02_ML.ipynb
```
## 🎓 O que aprendi (e você também vai!)

- **Contexto importa (e muito!!!)**: Mesmos dados, métodos diferentes dependendo do objetivo
- **Outliers podem ser ouro** - nem sempre são "ruído"
-  **Dados ausentes** podem ter histórias para contar
-   **IQR > Desvio Padrão** para amostras pequenas com outliers

---

