
<h1 align="center">Enterprise ERP — B2B</h1>

<p align="center">
  Enterprise Resource Planning System | VHC Soluções
</p>


<p align="center">
  <img src="./erp-badges.svg" alt="ERP project status"/>
</p>


---

## Overview | Visão geral

Sistema integrado de gestão empresarial desenvolvido
pela VHC Soluções, voltado à centralização de processos
financeiros, comerciais e operacionais.

The project focuses on enterprise management, modular
software architecture, data consistency and scalability.

## Tech Stack

![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Flyway](https://img.shields.io/badge/Flyway-CC0200?style=for-the-badge&logo=flyway&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)

---

## Business Modules

| Module | Description |
|---|---|
| Financial | Gestão financeira empresarial |
| Registration | Gerenciamento de cadastros |
| Inventory | Controle de estoque |
| CRM | Gestão de relacionamento com clientes |

## Architecture

Diagrama conceitual e simplificado da solução:

```mermaid
flowchart TD
    A[User Interface] --> B[REST API]
    B --> C[Spring Boot Backend]
    C --> D[Business Rules]
    D --> E[Data Access]
    E --> F[(PostgreSQL)]
    G[Flyway] --> F
```

### Engineering Principles

- Multi-tenant architecture
- Modular software design
- REST API integration
- Database versioning
- Data isolation
- Authentication and authorization
- Technical documentation
- Version control

---

## My Responsibilities

Como responsável pela área técnica da VHC Soluções,
minhas atividades envolvem:

- Definição da arquitetura de software.
- Levantamento e análise de requisitos.
- Desenvolvimento e integração de funcionalidades.
- Modelagem de bancos de dados relacionais.
- Definição de regras de negócio.
- Configuração de ambientes de desenvolvimento.
- Gerenciamento de branches e pull requests.
- Testes, validação e diagnóstico de falhas.
- Documentação técnica.
- Desenvolvimento assistido por inteligência artificial.

---

## Development Workflow

```mermaid
flowchart LR
    A[Requirements] --> B[Planning]
    B --> C[Development]
    C --> D[Validation]
    D --> E[Code Review]
    E --> F[Integration]
```

---

## Screenshots & Demonstration

Capturas reais do sistema em execução no ambiente
local de homologação.

### Executive Dashboard

Visão consolidada dos indicadores financeiros e
da situação empresarial.

<p align="center">
  <img src="./screenshots/01-dashboard.png" width="100%" alt="Executive Dashboard"/>
</p>

### Financial Management

Gestão de contas a receber e demonstrativos
de resultados gerenciais.

| Accounts Receivable | Income Statement |
|---|---|
| ![Contas a receber](./screenshots/03-contas-receber.png) | ![DRE](./screenshots/04-dre-gerencial.png) |

### Commercial Management & CRM

Gerenciamento de produtos, oportunidades comerciais
e pedidos de venda.

| Product Management | CRM Opportunities |
|---|---|
| ![Produtos](./screenshots/02-produtos.png) | ![CRM](./screenshots/05-oportunidades-crm.png) |

<p align="center">
  <img src="./screenshots/06-pedidos-venda.png" width="100%" alt="Sales Orders"/>
</p>

### Inventory & Human Resources

Governança de estoque e gerenciamento de cargos.

| Inventory Governance | Human Resources |
|---|---|
| ![Estoque](./screenshots/07-governanca-estoque.png) | ![RH](./screenshots/08-cargos-rh.png) |

> Screenshots captured in a local development
> and testing environment.

---

## Project Status

- Current stage: Active development
- Environment: Local
- Graphical interface: Available
- Source code: Private

---

## Confidentiality

Este repositório possui finalidade exclusivamente
demonstrativa e profissional.

O código-fonte, as regras de negócio proprietárias
e as informações internas pertencem à VHC Soluções
e não são disponibilizados publicamente.

---

## Author

**Victor Hugo Motta Terraciano**

Software Developer & Co-founder at VHC Soluções

[GitHub Profile](https://github.com/zzovittin) |
[Company Website](https://vhcsolucoes.com.br)
