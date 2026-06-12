# Seleção de Modelos

Atividade individual de Aprendizado de Máquina e Ciência de Dados (CIn/UFPE).

Seleção de hiperparâmetros com busca aleatória (RandomizedSearchCV) para 6 classificadores no dataset IRIS: KNN, Naive Bayes, Regressão Logística, Árvore de Decisão, MLP e SVM. O tuning usa validação cruzada de 5 folds com acurácia, e a avaliação final é feita num hold-out de 20% com acurácia, precisão e recall.

O notebook [selecao_modelos_iris.ipynb](selecao_modelos_iris.ipynb) tem todo o código e os resultados. O resumo dos resultados está no [RESULTADOS.md](RESULTADOS.md).

## Como rodar

```
pip install numpy pandas matplotlib scikit-learn scipy
```

Depois é só abrir o notebook no VS Code (ou Jupyter) e executar tudo. A seed é fixa (42), então os números saem iguais aos do documento de resultados.
