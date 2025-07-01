
# 📘 Documentação do Sistema de Gestão Financeira

## 🧾 Sumário

- [Introdução](#introdução)
- [Tecnologias Utilizadas](#tecnologias-utilizadas)
- [Funcionalidades](#funcionalidades)
- [Estrutura do Projeto](#estrutura-do-projeto)
- [Requisitos](#requisitos)
- [Instalação](#instalação)
- [Autores](#autores)
- [Licença](#licença)

---

## 📌 Introdução

Este sistema foi desenvolvido para gerenciar operações administrativas e financeiras de uma empresa, com foco na organização de **clientes**, **funcionários**, **contratos**, **seguros** e **controle de horas**. Possui um dashboard interativo para análise de dados em tempo real e alertas automatizados para aniversários e lembretes.

---

## 🛠️ Tecnologias Utilizadas

- **Back-End**: PHP (versão 7.4+)
- **Banco de Dados**: MySQL
- **Front-End**: HTML5, CSS3, JavaScript
- **Bibliotecas/Auxiliares**: 
  - jQuery
  - Chart.js (para dashboards)
  - Bootstrap (estilização opcional)

---

## ⚙️ Funcionalidades

### 🔹 CRUD
- **Clientes**: Cadastro, edição, exclusão e listagem de clientes.
- **Funcionários**: Gerenciamento completo de colaboradores.
- **Contratos Financeiros**: Controle de contratos vinculados a clientes e funcionários.
- **Contratos de Seguros**: Registro e organização de contratos de seguros vinculados.

### 🔹 Operações Administrativas
- **Bloqueio de Clientes**: Sistema de bloqueio/desbloqueio por inadimplência ou outros critérios.
- **Banco de Horas**: Registro de horas extras e banco de compensações dos funcionários.
- **Comparativo de Valores Contratuais**: Ferramenta para análise de evolução ou diferença entre contratos.

### 🔹 Produtividade e Notificações
- **Dashboard Interativo**: Indicadores gráficos com informações resumidas (clientes ativos, contratos por status, etc.).
- **Atalhos para Links**: Área de links úteis personalizáveis.
- **Lembretes**: Notificações internas de tarefas e lembretes agendados.
- **Aniversários dos Clientes**: Sistema de alerta + envio automático/manual de mensagens personalizadas.
- **Bloco de Anotações**: Área para registrar anotações rápidas e privadas por usuário.

---

## 🗂️ Estrutura do Projeto

```
/app
  ├── controllers/         # Lógica de controle das rotas
  ├── models/              # Conexão e manipulação de dados (MySQL)
  ├── views/               # Arquivos HTML/CSS/JS
/public
  ├── css/
  ├── js/
  ├── index.php            # Ponto de entrada
/config
  └── database.php         # Conexão com MySQL
```

---

## ✅ Requisitos

- PHP 7.4 ou superior
- MySQL 5.7 ou superior
- Apache/Nginx com suporte a URL Rewrite
- Navegador atualizado (Chrome, Firefox, Edge)

---

