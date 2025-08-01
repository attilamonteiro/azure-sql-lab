# 💾 Azure SQL - Laboratório Prático

Este repositório contém anotações, resumos e explicações sobre o processo de criação e configuração de uma instância de banco de dados SQL na plataforma Microsoft Azure.

## 🎯 Objetivo

Documentar, de forma prática e clara, todos os passos realizados para provisionar uma instância gerenciada de banco de dados SQL no Azure.

## 🧠 Aprendizados

- Criação de instância SQL no Azure  
- Configuração de firewall e acesso remoto  
- Utilização do Azure Portal  
- Conexão a partir do SSMS ou Azure Data Studio  
- Gerenciamento básico do banco de dados

## 🛠️ Tecnologias e Ferramentas

- Microsoft Azure  
- SQL Server Management Studio (SSMS)  
- Azure Data Studio  
- Git e GitHub

## 📝 Passo a Passo

### 1. Acesso ao Azure
- Criar uma conta (se necessário)
- Acessar o portal: [https://portal.azure.com](https://portal.azure.com)

### 2. Criar uma Instância de Banco de Dados SQL
- Ir até **Criar recurso > Banco de Dados SQL**
- Escolher grupo de recursos e nome para o banco
- Criar um novo servidor SQL (com login e senha)

### 3. Configuração de Rede
- Habilitar acesso ao seu IP local (configuração de firewall)
- Permitir conexões de outros serviços do Azure

### 4. Conexão com a Instância
- Conectar via SSMS ou Azure Data Studio usando o host, login e senha definidos
- Executar comandos SQL de teste

## 💡 Dicas Importantes

- O nome do servidor deve ser único globalmente  
- Utilize camadas de preços gratuitas, se disponíveis  
- Salve seu login/senha em local seguro

## 📚 Referências

- [Documentação Oficial - SQL no Azure](https://learn.microsoft.com/pt-br/azure/azure-sql/)  
- [Início Rápido - Criar SQL no Azure](https://learn.microsoft.com/pt-br/azure/azure-sql/database/single-database-create-quickstart)

---
