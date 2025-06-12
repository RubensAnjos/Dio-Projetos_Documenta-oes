# ☁️ Laboratório Azure - Instância de Banco de Dados SQL

Este repositório foi criado como parte do desafio prático da DIO, com foco na criação e configuração de uma **instância gerenciada de banco de dados SQL** no **Microsoft Azure**. O objetivo é consolidar o conhecimento adquirido durante as aulas e disponibilizar um material de referência para uso futuro.

---

## 🎯 Objetivo

- Criar e configurar uma instância do **Azure SQL Database**
- Documentar o processo de forma clara
- Registrar dicas e boas práticas
- Compartilhar capturas de tela para reforçar o aprendizado visual

---

## 🧠 Conceitos Abordados

- Introdução ao modelo PaaS (Plataforma como Serviço)
- Criação de um servidor SQL lógico no Azure
- Configuração de firewall e regras de acesso
- Criação de banco de dados SQL
- Acesso e conexão via ferramentas como SSMS ou Azure Data Studio
- Gerenciamento e boas práticas de segurança

---

## ⚙️ Passo a Passo da Criação da Instância SQL

### 1. Acessar o Portal do Azure
- Link: [https://portal.azure.com](https://portal.azure.com)

### 2. Criar um Servidor SQL
- Navegue até **SQL Servers** > “+ Create”
- Configure:
  - Nome do servidor
  - Login e senha do administrador
  - Região
- Clique em “Review + create” e, depois, em “Create”

### 3. Criar um Banco de Dados
- Vá até **SQL Databases** > “+ Create”
- Preencha:
  - Nome do banco de dados
  - Associe ao servidor criado anteriormente
  - Escolha plano de computação (Free ou Basic para testes)
- Finalize a criação

### 4. Configurar Acesso
- Vá até o servidor > **Firewalls and virtual networks**
- Adicione o IP da máquina local (ou permita acesso de todos — não recomendado para produção)
- Clique em “Salvar”

### 5. Acessar o Banco de Dados
- Utilize o **SQL Server Management Studio (SSMS)** ou **Azure Data Studio**
- Dados de conexão:
  - Servidor: `<nome>.database.windows.net`
  - Login e senha definidos na criação
  - Banco: nome criado no passo 3

---
# 📌 Dicas e Boas Práticas - Azure SQL

## 🔒 Segurança
- Sempre restrinja IPs ao mínimo necessário
- Evite usar o login de administrador para aplicações

## 💰 Custos
- Prefira o plano **Basic** ou **Free Tier** para ambientes de teste
- Configure alertas no Azure Cost Management para evitar surpresas

## 🧰 Ferramentas Recomendadas
- [SQL Server Management Studio (SSMS)](https://aka.ms/ssms)
- [Azure Data Studio](https://learn.microsoft.com/pt-br/sql/azure-data-studio/)

## 🎓 Para Estudo
- Crie tabelas e simule consultas usando dados fictícios
- Pratique a criação de backups lógicos (bacpac)

## 🧼 Limpeza
- Ao finalizar, delete o banco e o servidor SQL para evitar cobrança
