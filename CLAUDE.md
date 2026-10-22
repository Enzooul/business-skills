# Business Skills

Este repositório é a oficina de **negócios e estratégia**. As skills ficam em `.claude/skills/`.

## Como responder

- O usuário escreve em **português do Brasil**: responda sempre em português, mesmo que a skill esteja escrita em inglês. Termos técnicos podem ficar em inglês quando não houver tradução comum, com uma explicação curta na primeira vez.
- O usuário tem conhecimento **intermediário**: comece com uma explicação curta do que vai ser feito e por quê, depois entregue o trabalho principal. Textos claros, completos e didáticos.
- Em estratégias e planos, seja o mais avançado e completo possível.
- **Não invente informações.** Se um dado não puder ser verificado (preço, número, fato, fonte), diga que não sabe ou que está no limite do seu conhecimento.

## Como escolher a skill

- Os pedidos chegam em português; as descrições das skills estão em inglês. Use o mapa abaixo para traduzir o pedido na skill certa.
- Se o pedido não bater claramente com uma skill, comece pelo **roteador** indicado no mapa: ele escolhe a especialista.
- Diga ao usuário, em uma linha, qual skill está usando e por quê.

## Arquivos gerados

Sessões na nuvem são apagadas ao terminar. Quando uma skill gerar um arquivo que valha guardar (relatório, plano, contexto), salve-o dentro deste repositório e ofereça fazer commit.

## Mapa de pedidos

Roteadores: `chief-of-staff` (encaminha para o conselheiro certo ou convoca reunião de diretoria), `c-level-skills` (índice), `commercial-skills`, `business-growth-skills`. Na primeira vez, rode `cs-onboard` para registrar o contexto da empresa e salve o arquivo gerado dentro deste repositório.

| Pedido em português | Skill |
|---|---|
| "minha ideia de negócio é boa?", "detona essa ideia" | `roast` |
| "tem mercado?", "chegamos no product-market fit?" | `andreessen` |
| "e se o plano der errado?", "pré-mortem" | `challenge` |
| "testa minhas premissas" | `stress-test` |
| "decisão difícil, nenhuma opção é boa" | `hard-call` |
| "o que deu errado?", "retrospectiva" | `postmortem` |
| "e se X e Y acontecerem juntos?", "cenários" | `scenario-war-room` |
| "estratégia da empresa", "decisão de CEO" | `ceo-advisor` |
| "finanças da empresa", "caixa/runway", "captação" | `cfo-advisor` |
| "marketing em nível de diretoria" | `cmo-advisor` |
| "vendas/receita", "metas" | `cro-advisor` |
| "operações", "processos", "OKRs" | `coo-advisor` |
| "produto" | `cpo-advisor` |
| "tecnologia", "dívida técnica" | `cto-advisor` |
| "contratar", "salários", "pessoas" | `chro-advisor` |
| "segurança da empresa" | `ciso-advisor` |
| "contrato", "jurídico", "term sheet" | `general-counsel-advisor` (não substitui advogado) |
| "escreve contrato/proposta/NDA" | `contract-and-proposal-writer` |
| "preço do produto", "modelo de cobrança" | `pricing-strategist` |
| "cliente pediu desconto", "revisar negociação" | `deal-desk` |
| "parceria", "revenda" | `partnerships-architect` |
| "licitação", "RFP", "questionário de fornecedor" | `rfp-responder` |
| "previsão de vendas" | `commercial-forecaster` |
| "concorrência" | `competitive-intel` |
| "montar a empresa do zero" | `arquiteto-de-empresa` |
| "expandir para outro país" | `intl-expansion` |
| "comprar/vender empresa", "M&A" | `ma-playbook` |
| "reunião com investidores/conselho" | `board-prep`, `board-deck-builder` |
| "cultura", "valores" | `culture-architect` |
| "estou sobrecarregado como fundador", "delegar" | `founder-coach` |

Muitas skills foram pensadas para startups de software (SaaS B2B); adapte números e exemplos ao negócio do usuário.
