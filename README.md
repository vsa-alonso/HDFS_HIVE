# HDFS_HIVE

Organização do ambiente de trabalho:

Para obtenção da imagem do docker, foi clonado o repositório  https://github.com/fabiogjardim/bigdata_docker.


## Importação dos datasets

```
#! /bin/bash

wget --no-check-certificate 'https://docs.google.com/uc?export=download&id=1kweRdKbpHemHPgEZBLREfoi5dTuibcRd' -O 'Copia de customeraddress.csv'
wget --no-check-certificate 'https://docs.google.com/uc?export=download&id=1K0uYlD9En3hP2u7e1cCLgF_gBydilDWI' -O 'salesorderhead.csv'
wget --no-check-certificate 'https://docs.google.com/uc?export=download&id=1ChW5hfwmD4l6llZIeLesvVZLUr9BnGu9' -O 'salesorderdetail.csv'
wget --no-check-certificate 'https://docs.google.com/uc?export=download&id=1x6GuS7pq2M_pqv1s0CIP6qiGXZaEjeZd' -O 'productmodeldescription.csv'
wget --no-check-certificate 'https://docs.google.com/uc?export=download&id=1EwXN_iNohdnpgw-CogzeNNXpFp_ZwwYu' -O 'productmodel.csv'
wget --no-check-certificate 'https://docs.google.com/uc?export=download&id=1Ybxo4GB7v73d1qacgVtCwnfSaQkQCOxS' -O 'productdescription.csv'
wget --no-check-certificate 'https://docs.google.com/uc?export=download&id=1AKgHJ1InA7YAAFwQNGhwY29kiL34L7bc' -O 'productcategory.csv'
wget --no-check-certificate 'https://docs.google.com/uc?export=download&id=11bDt7PGrVfdhJZRIeOLgrqLUXf2opUqF' -O 'product.csv'
wget --no-check-certificate 'https://docs.google.com/uc?export=download&id=18YskJR7QaZPPbt6uBNN48eGQNYbUYGpB' -O 'customeraddress.csv'
wget --no-check-certificate 'https://docs.google.com/uc?export=download&id=1j0i4sGBuY996uC8qcS8ZZvLTBN2YqK6a' -O 'customer.csv'
wget --no-check-certificate 'https://docs.google.com/uc?export=download&id=1xiR-JmKVcL2r4EJkrJ-mqd8HInLdqasa' -O 'address.csv'
```

