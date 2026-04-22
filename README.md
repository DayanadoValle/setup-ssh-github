# 🚀 Setup Git + SSH + GitHub

> Projeto de configuração de ambiente Git com autenticação SSH e versionamento no GitHub.

---

## 👩‍💻 Sobre o projeto

Este projeto tem como objetivo demonstrar a configuração completa do Git e integração com o GitHub utilizando SSH, permitindo autenticação segura e envio de projetos sem necessidade de senha.

---

## 🎯 Objetivos

- Configurar Git no ambiente local
- Gerar e configurar chave SSH (ed25519)
- Conectar o computador ao GitHub
- Criar repositório versionado
- Realizar commits e push via SSH

---

## ⚙️ Tecnologias utilizadas

- Git
- Git Bash
- GitHub
- SSH (ed25519)
- Windows

---
## 📚 Referência oficial

Este projeto foi baseado na documentação oficial do GitHub sobre autenticação SSH:

👉 https://docs.github.com/pt/authentication/connecting-to-github-with-ssh

---
## 🔐 Configuração SSH

### Geração da chave
```bash
ssh-keygen -t ed25519 -C "email"
```
### Local da chave
```bash
~/.ssh/id_ed25519.pub
```
### Teste de conexão
```bash
ssh -T git@github.com
```
✔ Resultado: autenticação bem-sucedida

---

## 📁 Criação do projeto

```bash
mkdir setup-ssh-github
cd setup-ssh-github
git init
```
---

## 📦 Versionamento com Git

```bash
git add .
git commit -m ""
```

---

## 🌐 Conexão com GitHub (SSH)

```bash
git remote add origin git@github.com:DayanadoValle/setup-ssh-github.git
git branch -M main
git push -u origin main
```
---

## 🚀 Resultado final

- SSH configurado com sucesso  
- GitHub conectado ao ambiente local  
- Repositório versionado  
- README publicado  
- Push realizado com sucesso  

---

## 🧠 Aprendizados

- Configuração de SSH no GitHub  
- Uso de Git (add, commit, push)  
- Fluxo de versionamento de código  
- Integração entre Git local e GitHub remoto  

---

## 🏁 Conclusão

Este projeto consolidou o processo de configuração do ambiente Git e integração com GitHub utilizando SSH, reforçando boas práticas de versionamento e controle de código.

---

## 📌 Autor

Dayana do Valle
