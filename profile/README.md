# Coude Jr 2026

Bem vindo à organização Coude Jr 2026 no GitHub.

Este espaço reúne os repositórios, padrões e fluxo de trabalho do time responsável pelo desenvolvimento do CRM da Escola Coude.

## Objetivo

Construir e evoluir um CRM educacional com foco em:
- gestão de contatos e funil
- autenticação e permissões
- organização de processos internos
- qualidade técnica e colaboração em equipe

## Repositórios principais

- crm-backend: API e regras de negócio
- crm-frontend: Interface web
- crm-infra: Infraestrutura local com Docker Compose, Nginx, banco e cache
- crm-shared-libs: Bibliotecas compartilhadas
- docs-engineering-handbook: Documentação de engenharia, padrões e guias
- .github: Templates globais, padrões de issues e pull requests, governança

## Stack

- Backend: PHP e Laravel
- Frontend: Node.js
- Infra: Docker Compose e Nginx
- Banco: PostgreSQL
- Cache, fila e sessão: Redis
- Gestão de tarefas: Jira

## Fluxo de trabalho

1. Criar branch a partir de develop
2. Nomear branch com padrão, por exemplo feat/scrum-20-filtro-contatos
3. Fazer commits com Conventional Commits
4. Abrir pull request para develop
5. Passar por revisão e ajustes
6. Fazer merge após aprovação

## Convenções de commit

Padrão:
tipo(escopo): descrição

Exemplos:
- feat(auth): adiciona login com Google
- fix(api): corrige paginação de contatos
- docs(readme): atualiza instruções de setup
- chore(infra): adiciona docker-compose inicial

## Segurança e LGPD

- Nunca versionar segredos como .env, tokens, chaves e credenciais
- Nunca publicar dados reais de alunos ou candidatos
- Usar dados fictícios ou sanitizados em exemplos e evidências

## Como contribuir

- Consultar o repositório docs-engineering-handbook
- Usar os templates de issue e pull request
- Manter pull requests pequenos, claros e rastreáveis via Jira

## Links úteis

- Organização: https://github.com/coude-jr-26
- Handbook: https://github.com/coude-jr-26/docs-engineering-handbook
- Jira: link interno do time
