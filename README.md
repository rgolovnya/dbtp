# DBT project

```
dbt init dbt_hol
cd dbt_hol
```

### Configure dbt profiles

~/.dbt/profiles.yml


### update dbt project 

dbt_project.yml 

### Validate the configuration

dbt debug

dbt run --model l10_staging 


dbt run --model +tfm_stock_history


dbt run --model +tfm_stock_history_major_currency

```
dbt docs generate
dbt docs serve
```

### upload datasets
dbt seed

dbt run -m tfm_book

dbt run -m tfm_book+


```
dbt run 
dbt docs serve
```

dbt test


### Deployment
```
dbt seed --target=prod
dbt run  --target=prod
```
