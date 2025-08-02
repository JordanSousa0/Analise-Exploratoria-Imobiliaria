# ✅ Objetivo do Projeto
Analisar dados de aluguéis para entender padrões, comportamentos do mercado e gerar insights estratégicos para o setor imobiliário.

---

# 🧰 Ferramentas e Tecnologias Utilizadas

- **Linguagem:** Python  
- **Bibliotecas:** `pandas`, `numpy`, `matplotlib`, `seaborn`  
- **Fonte de dados:** https://raw.githubusercontent.com/alura-cursos/pandas-conhecendo-a-biblioteca/main/base-de-dados/aluguel.csv
- **Processos:** Limpeza, transformação, filtragem, visualização e análise estatística

---

# 🔍 Principais Etapas da Análise

## 🔎 Exploração Inicial
Identificação das colunas, tipos de variáveis e distribuição de valores.

## 💰 Valor Médio por Tipo de Imóvel
Comparação entre apartamentos, casas e imóveis comerciais.  
➡️ **Imóveis comerciais apresentaram os valores de aluguel mais altos.**

## 🧼 Refino da Base
Imóveis comerciais foram removidos para focar na análise de imóveis residenciais.

## 🏢 Distribuição Percentual por Tipo
Apartamentos representam a maioria dos registros, justificando o foco neles.

## 🎯 Foco em Apartamentos
Seleção apenas de apartamentos para análises mais direcionadas e aprofundadas.

## ❌ Tratamento de Dados Nulos
Valores ausentes foram identificados e tratados (via exclusão ou imputação).

## 🧹 Remoção de Registros Irrelevantes
Exclusão de registros com valores inconsistentes ou fora do padrão.

## 🏷️ Criação de Colunas Categóricas
Colunas derivadas foram criadas para enriquecer a análise, como faixas de valores, agrupamentos, etc.

---

# 📊 Principais Insights

- Imóveis comerciais tem o maior valor médio, mas foram excluídos da análise final para manter o foco em imóveis residenciais.
- Apartamentos são amplamente predominantes no mercado de aluguel do Rio de Janeiro.
- Após tratamento de dados e remoção de outliers, observou-se uma distribuição mais realista e consistente dos preços.
- O uso de gráficos horizontais e mapas de calor contribuiu para uma visualização clara dos padrões e relações entre variáveis.

---

# 📈 Análise de Correlação

Uma matriz de correlação foi gerada para investigar relações entre as principais variáveis numéricas.

### 🔗 Correlação com o Valor do Aluguel:

| Variável    | Correlação com Valor | Interpretação                                                    |
|-------------|----------------------|------------------------------------------------------------------|
| Área        | 0.87                 | Forte relação positiva — imóveis maiores tendem a ter aluguéis mais caros. |
| IPTU        | 0.76                 | Correlação alta — imóveis com IPTU elevado geralmente têm aluguel mais caro. |
| Suítes      | 0.71                 | Correlação considerável — mais suítes indicam padrão mais alto.  |
| Vagas       | 0.67                 | Correlação moderada — mais vagas associadas a maior valor de aluguel. |
| Quartos     | 0.57                 | Correlação moderada — influencia o preço, mas com menor intensidade. |
| Condomínio  | 0.37                 | Correlação fraca — valor do condomínio não afeta diretamente o aluguel. |

### 🧩 Outras Relações Relevantes:

- **Área x Quartos (0.70)** e **Área x Suítes (0.74)**: imóveis maiores oferecem mais cômodos e comodidades.
- **IPTU x Suítes (0.81)**: imóveis com mais suítes tendem a estar em áreas valorizadas.
- **Vagas x Suítes (0.79)**: imóveis com mais vagas e suítes indicam padrão elevado.

---

# 📌 Conclusões Finais

- O mercado de aluguel no Rio de Janeiro é fortemente centrado em apartamentos, o que justifica a segmentação e especialização da análise.
- As variáveis **área**, **IPTU** e **suítes** são as que mais influenciam o valor do aluguel.
- O processo de limpeza, categorização e análise de correlação forneceu uma base sólida para futuros modelos preditivos ou tomadas de decisão no setor.
- As técnicas de visualização utilizadas facilitaram a interpretação e comunicação dos dados, apoiando **insights estratégicos com clareza**.
