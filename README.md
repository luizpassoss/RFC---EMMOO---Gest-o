# Sistema de Gestão de Agenda, Mensalidades e Presença — Escola de Música EMMO

Projeto de Portfólio (PAC Extensionista VII) — Engenharia de Software, Católica SC.
Linha: **Web App**. Parceiro externo: **Escola de Música EMMO**.

## Sobre o projeto

Aplicação web para substituir a gestão manual (planilhas e WhatsApp) da Escola de Música EMMO,
centralizando **agenda de aulas, reposições, presença, diário de aula e mensalidades**, com
histórico consolidado e alertas de pagamento.

## Funcionalidades principais

- Autenticação por papel (coordenação, professor e responsável/aluno)
- Cadastro de alunos, planos e instrumentos
- Agenda de horários do professor, visível aos alunos
- Aviso de falta e solicitação de reposição pelo próprio aluno
- Registro de presença e diário de aula (conteúdo + plano da próxima)
- Geração e baixa de mensalidades, com alertas de pagamento
- Dashboard de indicadores e histórico consolidado por aluno
- Relatórios e recibos em PDF

## Tecnologias

- **Front-end:** React (SPA)
- **Back-end:** Node.js + Express (API REST)
- **Banco de dados:** MySQL
- **Autenticação:** JWT + bcrypt
- **Deploy:** VPS Linux com Docker e Nginx

## Como executar (rascunho)

```bash
# back-end
cd api
npm install
npm run dev

# front-end
cd web
npm install
npm run dev
```

> As instruções definitivas de execução e variáveis de ambiente serão detalhadas durante o desenvolvimento.

## Estrutura prevista

```
/api    -> API REST (Node.js + Express)
/web    -> Aplicação web (React)
/docs   -> RFC, diagramas e documentação
```

## Documentação

A RFC completa (problema, requisitos, arquitetura C4, DER, casos de uso e mockups) está em `/docs`.

## Licença

A definir com o parceiro (repositório público durante todo o ciclo de desenvolvimento).

## Autor

Luiz Fernando Passos de Oliveira — Engenharia de Software, Católica SC.
