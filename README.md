data source: [Kaggle](https://www.kaggle.com/datasets/shekpaul/global-superstore/data)

управление зависимостями с помощью conda:

- Сохранение окружения

```
conda env export --from-history > environment.yml
```

- Установка окружения

```
conda env create -f environment.yml
```