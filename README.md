# Detecção de Fraude em Cartões de Crédito 💳

Este projeto aplica técnicas de Machine Learning para identificar transações fraudulentas em um dataset altamente desbalanceado (0.17% de fraudes).

## 🚀 Tecnologias Usadas
- Python (Pandas, Scikit-Learn)
- Random Forest Classifier
- Validação Cruzada Estratificada (Stratified K-Fold)
- Análise de Feature Importance

## 📊 Resultados
- **F1-Score:** 0.85 (Validado via Cross-Validation)
- **Estratégia:** Ajuste de Limiar (Threshold) para priorizar o Recall e capturar mais fraudes.

## 📂 Estrutura
O código baixa automaticamente os dados do OpenML, realiza o pré-processamento, treina o modelo e gera gráficos de avaliação (Curva ROC e Precision-Recall).
