# Conteúdo estático do portal LabQS

Este sub-módulo contém o conteúdo do portal LabQS

## Atualização do conteúdo estático

O conteúdo estático deve ser atualizado no projeto do portal pelo comando:

```sh
python3 ./manage.py collectstatic
```

Em seguida o conteúdo deve ser copiado para este submódulo pois eventualmente a pasta no projeto do LabQS não irá refletir o conteúdo do sub-módulo