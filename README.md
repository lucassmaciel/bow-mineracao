# Classificação de rating de reviews (Bag of Words)

Trabalho de Mineração de Dados: prever a nota (1 a 5 estrelas) de reviews de produtos da Amazon em português a partir do texto.

## Abordagem

- Bag of Words e TF-IDF com features linguísticas do spaCy.
- Modelos comparados: Naive Bayes, LinearSVC, Regressão Logística e Random Forest.
- Métrica principal: F1 macro.

## Arquivos

- `main.ipynb`: experimentos e treinamento.
- `relatorio.ipynb`: relatório com os resultados.
- `data/`: `train.csv`, `test.csv` e `sample_submission.csv`.
- `figures/`: distribuição das notas, comparação dos modelos e matriz de confusão.
- `submission.csv`: predições enviadas.

## Como rodar

```bash
uv sync
uv run jupyter notebook main.ipynb
```
