# Classificação de Vinhos — Análise Comparativa de Modelos

Atividade para a disciplina de Programação Avançada - 2026.2
Este repositório contém uma análise preditiva para classificação de vinhos utilizando algoritmos de Aprendizado de Máquina. O projeto explora o impacto do pré-processamento de dados (como o tratamento de linhas duplicadas) na acurácia e generalização dos modelos.

---

## 📌 Visão Geral

O objetivo principal é comparar o desempenho de diferentes classificadores antes e depois da remoção de duplicatas no conjunto de dados, avaliando o custo-benefício entre ganho de acurácia e risco de *data leakage*.

### Resultados Principais

| Modelo | Tratamento | Acurácia Média (Validação Cruzada) |
| :--- | :--- | :--- |
| **Random Forest** | **Com Duplicadas** | **$0.9949 \pm 0.0025$** *(Maior pontuação)* |
| Random Forest | Sem Duplicadas | $0.9942 \pm 0.0030$ |
| KNN | Com Duplicadas | $0.9812 \pm 0.0040$ |
| KNN | Sem Duplicadas | $0.9415 \pm 0.0055$ |

---

## 🛠️ Tecnologias Utilizadas

* **Linguagem:** Python
* **Bibliotecas:** `pandas`, `numpy`, `scikit-learn`, `matplotlib` 
