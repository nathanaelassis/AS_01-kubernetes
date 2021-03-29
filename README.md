# AS_01 - Kubernetes
- MySQL e NGINX

## Kubernetes on-line
- https://www.katacoda.com/courses/kubernetes/playground
  
## Comandos utilizados
```vi nginx.yml``` - Criando yml nginx </br>
```vi mysql.yml``` - Criando yml mysql </br>
```kubectl apply -f nginx.yml``` - Aplicando configuração </br>
```kubectl apply -f mysql.yml``` - Aplicando configuração </br>
```kubectl get pods``` - Listando PODs </br>
```kubectl get svc``` - Listando Serviço </br>
```curl IPnginx:80``` - Verificando comunicação </br>
```kubectl exec -ti nomePodMySQL -- /bin/bash``` - Entrando no POD </br>
```mysql -u mysql -pmysql``` - Entrando no database </br>

## kubectl Cheat Sheet
- https://kubernetes.io/pt/docs/reference/kubectl/cheatsheet/