# 💻 Laboratório Azure - Criação e Configuração de uma Máquina Virtual

Este repositório foi criado como parte do desafio prático da DIO para demonstrar conhecimentos sobre a plataforma **Microsoft Azure**, com foco na criação e configuração de **máquinas virtuais**.

---

## 📌 Objetivo

O objetivo principal deste projeto é praticar a criação de uma máquina virtual no Azure, documentar todas as etapas do processo e compartilhar anotações úteis para estudos futuros e implementações em ambientes reais.

---

## 🧠 Conceitos Abordados

- Introdução à computação em nuvem e ao Azure
- Diferença entre tipos de recursos (Resource Group, VM, Rede Virtual, etc.)
- Criação de uma máquina virtual Windows no Portal do Azure
- Configurações básicas: nome, SO, tamanho, autenticação
- Acesso remoto via RDP
- Boas práticas de segurança e gerenciamento
- Prevenção de cobranças (encerramento e exclusão da VM)

---

## ⚙️ Passo a Passo da Criação da VM

### 1. Acessando o Azure
- Acesse o [Portal do Azure](https://portal.azure.com/)
- Faça login com sua conta Microsoft

### 2. Criando um Resource Group
- Navegue até “Resource Groups”
- Clique em “+ Create”
- Dê um nome e escolha uma região

### 3. Criando a Máquina Virtual
- Acesse “Virtual Machines” > “+ Add”
- Selecione:
  - Nome da VM
  - Região
  - Imagem: Windows Server 2019
  - Tamanho (Ex: B1s – gratuito elegível)
  - Autenticação: usuário/senha
  - Porta: habilitar RDP (porta 3389)

### 4. Revisar e Criar
- Clique em “Review + create”
- Verifique e clique em “Create”

### 5. Acesso Remoto
- Após o provisionamento, clique em “Connect”
- Faça o download do arquivo RDP
- Acesse com o login/senha definidos

---

## 📂 Estrutura do Repositório


azure-vm-lab-dio/
│
├── README.md
├── dicas.md


# 🧩 Dicas e Anotações Úteis sobre Azure

## ⚠️ Evite Cobranças Indevidas
- Ao finalizar o uso da VM, exclua os recursos criados (VM, disco, IP, grupo de recursos).
- Monitore sua conta com o **Azure Cost Management**.

## 🔐 Segurança
- Nunca exponha portas desnecessárias.
- Utilize senhas fortes e, se possível, habilite autenticação multifator.

## 📌 Organização
- Use **Resource Groups** para agrupar recursos relacionados.
- Adicione **tags** a cada recurso para facilitar rastreamento e gerenciamento.

## 💡 Dica Extra
- Explore a criação de VMs com **Azure CLI** ou **ARM Templates** para automatização.


