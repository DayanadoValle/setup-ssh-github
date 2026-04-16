# \# Setup SSH GitHub

# 

# Este projeto demonstra a configuração de autenticação SSH entre um computador local e o GitHub.

# 

# \## Objetivo

# Permitir o envio de commits sem uso de senha, utilizando chave SSH.

# 

# \## Passos realizados

# 

# 1\. Instalação do Git

# 2\. Geração de chave SSH com ed25519

# 3\. Adição da chave no GitHub

# 4\. Teste de conexão SSH

# 5\. Criação de repositório local

# 6\. Primeiro commit e push via SSH

# 

# \## Comandos principais utilizados

# 

# ```bash

# ssh-keygen -t ed25519 -C "email"

# cat \~/.ssh/id\_ed25519.pub

# ssh -T git@github.com

# git init

# git add .

# git commit -m "first commit"

# git push origin main

