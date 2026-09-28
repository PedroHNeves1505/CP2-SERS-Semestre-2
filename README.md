# CP2-SERS-Semestre-2

## Integrante 
Integrante: Pedro Henrique Neves<br>
RM: 571382

# Objetivo
Este repositório tem como objetivo documentar o desenvolvimento do Checkpoint 2 (CP2) da disciplina, dividido em duas etapas principais de Machine Learning aplicadas ao setor energético:

1. **Tarefa 1 — Classificação (ANEEL):** Aplicação e comparação de modelos de aprendizado de máquina supervisionado (**Logistic Regression**, **Random Forest** e **K-Nearest Neighbors**) para a classificação de usinas/geradores de energia com base em dados da ANEEL. O modelo **Random Forest** destacou-se como o melhor desempenho geral, alcançando uma acurácia de aproximadamente 97,55%.

2. **Tarefa 2 — Regressão (Open-Meteo):** Implementação e avaliação de modelos preditivos (**Linear Regression**, **Random Forest** e **K-Nearest Neighbors**) voltados à estimativa de radiação solar utilizando dados meteorológicos da Open-Meteo. Novamente, o **Random Forest** obteve a superioridade técnica, registrando o melhor coeficiente de determinação ($R^2$ de 0.9264) e os menores erros de predição (MSE e MAE).

## Tarefa 1 — Classificação (ANEEL)

#### Tabela Comparativa entre modelos
| Modelo | Acurácia | Precisão | Recall | F1 Score |
| :--- | :---: | :---: | :---: | :---: |
| **Logistic Regression** | 0.7126 | 0.7064 | 0.7063 | 0.7058 |
| **Random Forest** | 0.9755 | 0.9769 | 0.9741 | 0.9753 |
| **K-Nearest Neighbors** | 0.9626 | 0.9628 | 0.9618 | 0.9623 |

## Tarefa 2 — Regressão (Open-Meteo)

#### Tabela Comparatia entre modelos
| Modelo | R² Score | MSE | MAE |
| :--- | :---: | :---: | :---: |
| **Linear Regression** | 0.6211 | 24816.37 | 121.59 |
| **Random Forest** | 0.9264 | 4816.96 | 48.33 |
| **K-Nearest Neighbors** | 0.5727 | 27984.96 | 126.50 |
