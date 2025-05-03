# 💾 Desafio DIO: Configuração de Banco de Dados no Azure

Este repositório documenta o processo de criação e configuração de uma instância de Banco de Dados SQL no Microsoft Azure, como parte do laboratório prático da plataforma DIO.

---

## 🧠 Objetivo

O objetivo deste projeto é aplicar os conceitos aprendidos durante as aulas, criar uma instância de banco de dados no Azure e documentar todo o processo com anotações, dicas e imagens, promovendo o aprendizado prático e colaborativo.

---

## 📌 Pré-requisitos

Antes de iniciar, você precisa:

- Conta Microsoft com acesso ao portal Azure (https://portal.azure.com)
- Acesso às aulas da trilha DIO
- Git instalado no computador
- Conta no GitHub

---

## 🔧 Passo a Passo da Configuração

### 1. Acessar o Portal do Azure
- Acesse o [Portal Azure](https://portal.azure.com)
- Faça login com sua conta Microsoft

### 2. Criar um Recurso de Banco de Dados SQL
- Vá em **"Criar um recurso" > "Banco de Dados" > "Banco de Dados SQL"**
- Preencha os campos obrigatórios:
  - **Nome do Banco de Dados**
  - **Grupo de Recursos**
  - **Servidor SQL (criar novo, se necessário)**

### 3. Configurar o Servidor SQL
- Defina:
  - Nome do servidor
  - Localização (ex: Brasil Sul)
  - Usuário e senha do administrador

### 4. Selecionar Plano de Preço
- Use o plano **Desenvolvimento/Teste (DTU-based ou vCore-based)** conforme as opções disponíveis na sua conta gratuita ou trial.

### 5. Regras de Firewall
- Configure o acesso ao banco:
  - Adicione o IP do seu computador
  - Permita acesso a serviços do Azure, se necessário

### 6. Conectar ao Banco de Dados
- Copie a **string de conexão**
- Use um cliente como **Azure Data Studio** ou **SQL Server Management Studio (SSMS)**

---

## 📎 Dicas Úteis

- Utilize o botão "Mostrar string de conexão" para copiar os dados de acesso rapidamente.
- Adicione apenas os IPs confiáveis para garantir a segurança do banco.
- Monitore o desempenho da instância no painel do Azure.

---


