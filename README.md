# AS_01 - Kubernetes

## Kubernetes on-line
- https://www.katacoda.com/courses/kubernetes/playground
  
## Comandos utilizados
```vi nginx.yml``` - Criando yml nginx
```vi mysql.yml``` - Criando yml mysql
```kubectl apply -f nginx.yml``` - Aplicando configuração
```kubectl apply -f mysql.yml``` - Aplicando configuração
```kubectl get pods``` - Verificando PODs
```kubectl get svc``` - Verificando Serviço
```curl IPnginx:80``` - Verificando comunicação
```kubectl exec -ti nomePodMySQL -- /bin/bash``` - Entrando no POD
```mysql -u mysql -pmysql``` - Entrando no database