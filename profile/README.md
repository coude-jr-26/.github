# Coude Jr — 2026

<div align="center">

![Banner](https://capsule-render.vercel.app/api?type=waving&color=0:6C63FF,100:00C9A7&height=200&section=header&text=CRM%20Escola%20Coude&fontSize=42&fontColor=ffffff&animation=fadeIn&fontAlignY=38&desc=Time%20de%20Engenharia%20%7C%20Coude%20Jr%202026.1&descAlignY=55&descSize=18)

[![Organização](https://img.shields.io/badge/GitHub-Organização-6C63FF?style=for-the-badge&logo=github&logoColor=white)](https://github.com/coude-jr-26)
[![Handbook](https://img.shields.io/badge/Docs-Handbook-00C9A7?style=for-the-badge&logo=readthedocs&logoColor=white)](https://github.com/coude-jr-26/docs-engineering-handbook)
[![Jira](https://img.shields.io/badge/Jira-Board-0052CC?style=for-the-badge&logo=jira&logoColor=white)](#)

![Laravel](https://img.shields.io/badge/PHP-Laravel-FF2D20?style=flat-square&logo=laravel&logoColor=white)
![Node](https://img.shields.io/badge/Frontend-Node.js-339933?style=flat-square&logo=node.js&logoColor=white)
![Docker](https://img.shields.io/badge/Infra-Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Postgres](https://img.shields.io/badge/DB-PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Cache-Redis-DC382D?style=flat-square&logo=redis&logoColor=white)

</div>

<br>

> Bem-vindo à organização **Coude Jr 2026** no GitHub.
> Este espaço reúne os repositórios, padrões e fluxo de trabalho do time responsável pelo desenvolvimento do **CRM da Escola Coude**.

---

## Objetivo

Construir e evoluir um **CRM educacional** com foco em:

<table>
<tr>
<td width="50%" valign="top">

### Produto
- Gestão de contatos e funil
- Autenticação e permissões
- Organização de processos internos

</td>
<td width="50%" valign="top">

### Engenharia
- Qualidade técnica
- Colaboração em equipe
- Evolução contínua

</td>
</tr>
</table>

---

## Repositórios principais

<div align="center">

| Repositório | Descrição |
|:---|:---|
| **[crm-backend](https://github.com/coude-jr-26/crm-backend)** | API e regras de negócio |
| **[crm-frontend](https://github.com/coude-jr-26/crm-frontend)** | Interface web |
| **[crm-infra](https://github.com/coude-jr-26/crm-infra)** | Infraestrutura local: Docker Compose, Nginx, banco e cache |
| **[crm-shared-libs](https://github.com/coude-jr-26/crm-shared-libs)** | Bibliotecas compartilhadas |
| **[docs-engineering-handbook](https://github.com/coude-jr-26/docs-engineering-handbook)** | Documentação de engenharia, padrões e guias |
| **[.github](https://github.com/coude-jr-26/.github)** | Templates globais, padrões de issues/PRs, governança |

</div>

---

## Stack

<div align="center">

| Camada | Tecnologia |
|:--:|:--:|
| Backend | ![PHP](https://img.shields.io/badge/-PHP%20%2F%20Laravel-777BB4?style=flat-square&logo=php&logoColor=white) |
| Frontend | ![Node](https://img.shields.io/badge/-Node.js-339933?style=flat-square&logo=node.js&logoColor=white) |
| Infra | ![Docker](https://img.shields.io/badge/-Docker%20Compose%20%2F%20Nginx-2496ED?style=flat-square&logo=docker&logoColor=white) |
| Banco | ![PostgreSQL](https://img.shields.io/badge/-PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white) |
| Cache / Fila / Sessão | ![Redis](https://img.shields.io/badge/-Redis-DC382D?style=flat-square&logo=redis&logoColor=white) |
| Gestão de tarefas | ![Jira](https://img.shields.io/badge/-Jira-0052CC?style=flat-square&logo=jira&logoColor=white) |

</div>

---

## Fluxo de trabalho

<details>
<summary><strong>Clique para expandir o passo a passo</strong></summary>

<br>

```mermaid
graph LR
    A[develop] --> B[criar branch]
    B --> C[commits]
    C --> D[pull request]
    D --> E[revisão]
    E --> F[merge]
```

1. **Criar branch** a partir de `develop`
2. **Nomear branch** com padrão, ex.: `feat/scrum-20-filtro-contatos`
3. **Fazer commits** com Conventional Commits
4. **Abrir pull request** para `develop`
5. **Passar por revisão** e ajustes
6. **Fazer merge** após aprovação

</details>

---

## Convenções de commit

**Padrão:**
```
tipo(escopo): descrição
```

<details>
<summary><strong>Ver exemplos de commits</strong></summary>

<br>

| Tipo | Exemplo |
|:--|:--|
| `feat` | `feat(auth): adiciona login com Google` |
| `fix` | `fix(api): corrige paginação de contatos` |
| `docs` | `docs(readme): atualiza instruções de setup` |
| `chore` | `chore(infra): adiciona docker-compose inicial` |

</details>

---

## Segurança e LGPD

> [!WARNING]
> Atenção redobrada com dados sensíveis.

- Nunca versionar segredos como `.env`, tokens, chaves e credenciais
- Nunca publicar dados reais de alunos ou candidatos
- Usar dados fictícios ou sanitizados em exemplos e evidências

---

## Como contribuir

- Consulte o repositório **docs-engineering-handbook**
- Use os **templates** de issue e pull request
- Mantenha pull requests **pequenos, claros e rastreáveis via Jira**

---

## Links úteis

<div align="center">

[![Organização](https://img.shields.io/badge/Organização-coude--jr--26-6C63FF?style=for-the-badge)](https://github.com/coude-jr-26)
[![Handbook](https://img.shields.io/badge/Handbook-Engineering-00C9A7?style=for-the-badge)](https://github.com/coude-jr-26/docs-engineering-handbook)
[![Jira](https://img.shields.io/badge/Jira-Board%20interno-0052CC?style=for-the-badge)](#)

</div>

<div align="center">

![footer](https://capsule-render.vercel.app/api?type=waving&color=0:00C9A7,100:6C63FF&height=100&section=footer)

**Time Coude Jr 2026.1**

</div>
