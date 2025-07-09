# - 🔒 Projeto de Bolsas DevSecOps/AWS,  Compass UOL, abril 2025 🔒 -

## 📦 GitOps de uma aplicação 📦

## 📜 0 - Breve resumo >
No quarto projeto, utilizando o ArgoCD levantamos a aplicação [Online Boutique](https://github.com/GoogleCloudPlatform/microservices-demo) para treinarmos conceitos de Kubernetes:  

---
## ✂️ 1 - Criação de repositórios >
### Primeiro eu criei um Fork do repositório do projeto:  

![Primeiro print](/Prints/1.1.png)  

### E depois criei um repositório apenas com arquivo ymal do Online Boutique:  

![Segundo print](/Prints/1.2.png)  

---
## 🐙 2 - Baixando o ArgoCD >
### Em seguida, executei os seguintes comandos no meu PowerShell para instalar o ArgoCD no meu Docker Desktop:  

`kubectl create namespace argocd`  
`kubectl apply -n argocd -f https://raw.githubusercontent.com/argoproj/argocd/stable/manifests/install.yaml`  

---
## 🚪 3 - Rodando localmente >
### Para o terceiro passo, precisei rodar localmente o ArgoCD: 

![Terceiro print](/Prints/3.1.png)  
>- Utilizando o comando `kubectl port-forward svc/argocd-server -n argocd 8080:443` já obtemos o resultado esperado;  

![Quarto print](/Prints/3.2.png)  
![Quinto print](/Prints/3.3.png)  

---
## 🤖 4 - Configurando a aplicação no ArgoCD >
### : 
![Sexto print](/Prints/4.1.png)  
![Sétimo print](/Prints/4.2.png)  
![Oitavo print](/Prints/4.3.png)  
![Nono print](/Prints/4.4.png)  
![Décimo print](/Prints/4.5.png)  
![Print Onze](/Prints/4.6.png)  
![Print Doze](/Prints/4.7.png)  

---
## 🖥️ 5 - Acessando o front localmente >
### : 
![Print Treze](/Prints/5.1.png)  
![Print Quatorze](/Prints/5.2.png)  
![Print Quinze](/Prints/5.3.png)  

---
## 👥 6 - Aumentando número de réplicas >
### : 
![Print Dezesseis](/Prints/6.1.png)  
![Print Dezessete](/Prints/6.2.png) 
