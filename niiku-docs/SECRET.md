```
kubeseal --cert ~/kubeseal.crt --namespace=niiku-docs < postgresql-secret.yaml.ignore > postgresql-sealed-secret.json
```