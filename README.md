data source: [Kaggle](https://www.kaggle.com/datasets/abbas829/global-superstore-sales-dataset/data)

управление зависимостями с помощью conda:

- Сохранение окружения

```
conda env export --from-history > environment.yml
```

- Установка окружения

```
conda env create -f environment.yml
```