# Projeto: 
Análise dos dados de desempenho de jogadores e times profissionais da NBA.

## Equipe: 
Sin(Args)²

## Descrição: 
Agrupar dados criando estatísticas pessoais e de time e analisar essas estatísticas para comparar jogadores, times e dados específicos.

## Membros:

Antonio Carlos Farias Ferreira, 2413868, BSI, UTFPR

Lucas Ricardo Milani Ratusznei, 2402343, lucasricardomilani, BSI, UTFPR

Rodrigo Augusto Antunes dos Santos, 2402394, rodrigoaugusto2103, BSI, UTFPR

Sidnei José de Castro Ribeiro Junior, 2402408, siddijr, BSI, UTFPR

## 🎯 Objetivos

1. Identificar as principais características estatísticas de cada posição (C, F, G).
2. Avaliar qual posição mais influencia as vitórias.
3. Verificar quais posições são mais difíceis de substituir.

## 📊 Metodologia

- Limpeza e tratamento dos dados (jogadores e times).
- Criação de métricas agregadas por posição.
- Regressão logística para modelar vitórias.
- One-Class SVM para detectar anomalias no tempo de quadra.
- Análise de impacto usando Plus-Minus.

## 📈 Principais Resultados

- **Pivôs (C)** tiveram maior influência estatística na probabilidade de vitória.
- **Alas (F)** foram os mais difíceis de substituir.
- Modelo de regressão com ~57% de precisão.

## 🛠 Tecnologias

- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Scikit-learn  
- Statsmodels  

## ⚠️ Limitações

- Análise focada principalmente na temporada 2022-23.
- Baixo poder explicativo do modelo (Pseudo R² baixo).
- Limitações de hardware para múltiplas temporadas.

---

Projeto acadêmico – ICSB56
