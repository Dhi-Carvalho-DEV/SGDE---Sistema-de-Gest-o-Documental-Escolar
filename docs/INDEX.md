# INDEX — Índice da Documentação

> Portal central da documentação oficial do **Sistema de Gestão Documental Escolar (SGDE)**.

---

# Objetivo

Este documento tem como finalidade centralizar a navegação de todos os artefatos documentais do SGDE.

O INDEX representa o ponto inicial de consulta da documentação, permitindo localizar informações relacionadas à governança, arquitetura, domínio, modelagem, desenvolvimento, infraestrutura e qualidade do sistema.

---

# Organização da Documentação

A documentação do SGDE está organizada em áreas independentes, seguindo uma estrutura modular.

```text
docs/
│
├── README.md
├── INDEX.md
├── AUTHORS.md
├── HISTORY.md
├── ROADMAP.md
├── CHANGELOG.md
├── GLOSSARIO.md
│
├── 00-governanca/
├── 01-arquitetura/
├── 02-decisoes/
├── 03-dominio/
├── 04-modelagem/
├── 05-backend/
├── 06-frontend/
├── 07-api/
├── 08-deploy/
└── 09-testes/
```

---

# Documentação Institucional

Documentos responsáveis pela apresentação, organização e controle da documentação do projeto.

| Documento                      | Descrição                                | Versão | Responsável                     | Atualizado | Status |
| ------------------------------ | ---------------------------------------- | :----: | ------------------------------- | :--------: | :----: |
| [README.md](../README.md)      | Apresentação geral do projeto            |  1.0   | [AUT-001](./AUTHORS.md#aut-001) | 2026-07-23 |   ✅   |
| [README.md](./README.md)       | Guia da documentação                     |  1.0   | [AUT-001](./AUTHORS.md#aut-001) | 2026-07-23 |   ✅   |
| [AUTHORS.md](./AUTHORS.md)     | Cadastro de autores e colaboradores      |  1.0   | [AUT-001](./AUTHORS.md#aut-001) | 2026-07-23 |   ✅   |
| [ROADMAP.md](./ROADMAP.md)     | Evolução planejada do produto            |   —    | —                               |     —      |   ⏳   |
| [HISTORY.md](./HISTORY.md)     | Histórico da documentação                |   —    | —                               |     —      |   ⏳   |
| [CHANGELOG.md](./CHANGELOG.md) | Histórico de versões do software         |   —    | —                               |     —      |   ⏳   |
| [GLOSSARIO.md](./GLOSSARIO.md) | Termos e conceitos utilizados no projeto |   —    | —                               |     —      |   ⏳   |

---

# 00 — Governança

Diretório:

```text
docs/00-governanca/
```

Documentos relacionados à definição inicial do produto, objetivos, escopo e direcionamento do projeto.

| Documento                                                     | Descrição                    | Versão | Responsável | Atualizado | Status |
| ------------------------------------------------------------- | ---------------------------- | :----: | ----------- | :--------: | :----: |
| [PC-000](./00-governanca/PC-000-termo-abertura-do-produto.md) | Termo de Abertura do Produto |   —    | —           |     —      |   ⏳   |

---

# 01 — Arquitetura

Diretório:

```text
docs/01-arquitetura/
```

Documentos responsáveis pela definição da arquitetura do SGDE.

| Documento                                                         | Descrição                        | Versão | Responsável | Atualizado | Status |
| ----------------------------------------------------------------- | -------------------------------- | :----: | ----------- | :--------: | :----: |
| [SAD-000](./01-arquitetura/SAD-000-termo-de-arquitetura.md)       | Documento inicial de arquitetura |   —    | —           |     —      |   ⏳   |
| [SAD-001](./01-arquitetura/SAD-001-visao-geral-da-arquitetura.md) | Visão geral da arquitetura       |   —    | —           |     —      |   ⏳   |
| [SAD-002](./01-arquitetura/SAD-002-requisitos-arquiteturais.md)   | Requisitos arquiteturais         |   —    | —           |     —      |   ⏳   |

---

# 02 — Decisões Arquiteturais

Diretório:

```text
docs/02-decisoes/
```

Registra decisões importantes tomadas durante a evolução do sistema.

| Documento                                                | Descrição                        | Versão | Responsável | Atualizado | Status |
| -------------------------------------------------------- | -------------------------------- | :----: | ----------- | :--------: | :----: |
| [ADR-001](./02-decisoes/ADR-001-decisao-arquitetural.md) | Registro de decisão arquitetural |   —    | —           |     —      |   ⏳   |

---

# 03 — Domínio

Diretório:

```text
docs/03-dominio/
```

Documentação baseada nos princípios de Domain-Driven Design (DDD).

| Documento                                              | Descrição              | Versão | Responsável | Atualizado | Status |
| ------------------------------------------------------ | ---------------------- | :----: | ----------- | :--------: | :----: |
| [DOM-001](./03-dominio/DOM-001-visao-do-dominio.md)    | Visão geral do domínio |   —    | —           |     —      |   ⏳   |
| [BC-001](./03-dominio/BC-001-contextos-delimitados.md) | Contextos delimitados  |   —    | —           |     —      |   ⏳   |
| [ENT-001](./03-dominio/ENT-001-entidades.md)           | Entidades do domínio   |   —    | —           |     —      |   ⏳   |
| [VO-001](./03-dominio/VO-001-objetos-valor.md)         | Objetos de valor       |   —    | —           |     —      |   ⏳   |
| [AGG-001](./03-dominio/AGG-001-agregados.md)           | Agregados do domínio   |   —    | —           |     —      |   ⏳   |
| [EVT-001](./03-dominio/EVT-001-eventos-dominio.md)     | Eventos de domínio     |   —    | —           |     —      |   ⏳   |

---

# 04 — Modelagem

Diretório:

```text
docs/04-modelagem/
```

Documentos referentes aos modelos estruturais e representações do sistema.

| Documento                                              | Descrição                                 | Versão | Responsável | Atualizado | Status |
| ------------------------------------------------------ | ----------------------------------------- | :----: | ----------- | :--------: | :----: |
| [UML-001](./04-modelagem/UML-001-modelo-dominio.md)    | Modelo UML do domínio                     |   —    | —           |     —      |   ⏳   |
| [UML-002](./04-modelagem/UML-002-diagrama-classes.md)  | Diagrama de classes                       |   —    | —           |     —      |   ⏳   |
| [DER-001](./04-modelagem/DER-001-modelo-conceitual.md) | Modelo entidade-relacionamento conceitual |   —    | —           |     —      |   ⏳   |
| [DER-002](./04-modelagem/DER-002-modelo-logico.md)     | Modelo entidade-relacionamento lógico     |   —    | —           |     —      |   ⏳   |
| [DB-001](./04-modelagem/DB-001-dicionario-dados.md)    | Dicionário de dados                       |   —    | —           |     —      |   ⏳   |

---

# 05 — Backend

Diretório:

```text
docs/05-backend/
```

Documentação técnica referente ao servidor, regras de negócio, serviços e persistência.

---

# 06 — Frontend

Diretório:

```text
docs/06-frontend/
```

Documentação referente à interface do usuário, componentes e experiência de utilização.

---

# 07 — API

Diretório:

```text
docs/07-api/
```

Documentação dos serviços, endpoints, contratos e integrações.

---

# 08 — Deploy

Diretório:

```text
docs/08-deploy/
```

Documentação de infraestrutura, implantação, configuração e sincronização.

---

# 09 — Testes

Diretório:

```text
docs/09-testes/
```

Documentação da estratégia de qualidade e validação do sistema.

| Documento                                             | Descrição                       | Versão | Responsável | Atualizado | Status |
| ----------------------------------------------------- | ------------------------------- | :----: | ----------- | :--------: | :----: |
| [TEST-001](./09-testes/TEST-001-estrategia-testes.md) | Estratégia geral de testes      |   —    | —           |     —      |   ⏳   |
| [TEST-002](./09-testes/TEST-002-casos-teste.md)       | Casos de teste do sistema       |   —    | —           |     —      |   ⏳   |
| [TEST-003](./09-testes/TEST-003-plano-validacao.md)   | Plano de validação da aplicação |   —    | —           |     —      |   ⏳   |

---

# Status Geral da Documentação

| Área                       |     Status      |
| -------------------------- | :-------------: |
| Documentação Institucional | 🟡 Em andamento |
| Governança                 | ⏳ Não iniciada |
| Arquitetura                | ⏳ Não iniciada |
| Decisões Arquiteturais     | ⏳ Não iniciada |
| Domínio                    | ⏳ Não iniciado |
| Modelagem                  | ⏳ Não iniciada |
| Backend                    | ⏳ Não iniciado |
| Frontend                   | ⏳ Não iniciado |
| API                        | ⏳ Não iniciada |
| Deploy                     | ⏳ Não iniciado |
| Testes                     | ⏳ Não iniciado |
