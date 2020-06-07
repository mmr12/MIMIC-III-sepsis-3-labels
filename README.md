# MIMIC-III Sepsis-3 Labels
An SQL and Python based implementation of the extraction of sepsis III labels in the MIMIC-III dataset.
This code is part of INSERT LINK

## Reproduce the labels
This code assumes you have access to the MIMIC-III dataset in Postgres format.

First make sure all the requirements in ```requirements.txt``` are met:
```pip install -r requirements.txt```

Then run:
`python make_labels.py [-h] -u SQLUSER -pw SQLPASS -ht HOST -db DBNAME -r
                      SCHEMA_READ_NAME [-w SCHEMA_WRITE_NAME]`
                      
## Aknowledgements
If you find this code useful we would appreciate if you could cite our work.

