# Business Skills

Repositório-oficina para **negócios e estratégia** com o Claude Code. Abra uma sessão (claude.ai/code ou local) com este repositório selecionado e o Claude descobre automaticamente as skills em `.claude/skills/`.

Curadoria de [alirezarezvani/claude-skills](https://github.com/alirezarezvani/claude-skills) (licença MIT, ver `LICENSE-claude-skills`), copiada do commit `27cfcd0`.

## O que tem aqui (55 skills)

| Área | Skills |
|---|---|
| Roteadores | `c-level-skills` (índice dos conselheiros), `chief-of-staff` (encaminha sua pergunta ao conselheiro certo ou convoca uma "reunião de diretoria"), `commercial-skills`, `business-growth-skills` |
| Conselheiros executivos | `ceo-advisor`, `cfo-advisor`, `cmo-advisor`, `cro-advisor`, `coo-advisor`, `cpo-advisor`, `cto-advisor`, `chro-advisor`, `ciso-advisor`, `vpe-advisor`, `general-counsel-advisor` (jurídico), `chief-ai-officer-advisor`, `chief-data-officer-advisor`, `chief-customer-officer-advisor` |
| Testar ideias e decisões | `roast` (painel crítico de 5 ângulos sobre uma ideia de negócio), `andreessen` (avaliação direta, focada em mercado), `executive-mentor`, `challenge` (pré-mortem: imagina que o plano falhou e acha os pontos fracos), `stress-test` (testa premissas), `hard-call` (decisões sem opção boa), `postmortem` (o que deu errado), `scenario-war-room` (cenários "e se" combinados) |
| Diretoria e investidores | `board-meeting`, `board-prep`, `board-deck-builder`, `decision-logger` |
| Comercial e preços | `pricing-strategist`, `deal-desk` (revisão de descontos e negociações), `commercial-policy`, `commercial-forecaster`, `channel-economics`, `partnerships-architect`, `rfp-responder` (responder licitações/RFPs) |
| Vendas e clientes | `sales-engineer`, `revenue-operations`, `customer-success-manager`, `contract-and-proposal-writer` (contratos, propostas, NDAs) |
| Empresa e organização | `arquiteto-de-empresa` (monta uma empresa do zero como conjunto de documentos), `company-os`, `strategic-alignment`, `org-health-diagnostic`, `change-management`, `culture-architect`, `internal-narrative`, `founder-coach`, `competitive-intel`, `intl-expansion`, `ma-playbook` (fusões e aquisições) |
| Infraestrutura dos conselheiros | `context-engine` e `cs-onboard` (guardam o contexto da sua empresa), `agent-protocol` |

## Observações

- `context-engine` guarda o contexto da empresa em `~/.claude/company-context.md`. Em sessões na nuvem essa pasta é apagada ao fim da sessão; se quiser que o contexto persista, salve-o neste repositório e faça commit.
- Várias skills são pensadas para startups de software (SaaS B2B); adapte os parâmetros a outros tipos de negócio.

## Como atualizar

Copie de novo as pastas `c-level-advisor/skills/*`, `c-level-advisor/executive-mentor/skills/*`, `commercial/skills/*`, `business-growth/skills/*`, `productivity/roast/skills/roast` e `productivity/andreessen/skills/andreessen` do repositório de origem para `.claude/skills/`.

Só as skills foram copiadas; agentes e slash commands dos plugins originais não fazem parte deste repositório, e algumas skills citam skills "irmãs" que não estão aqui — isso não impede o funcionamento.
