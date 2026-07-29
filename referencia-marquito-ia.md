---
note_type: reference_document
origin: pedido_andre
domain: [solunar, edital, ia, sistemas, marquito]
document_type: referencia
status: active
gerado_por: Jão (DA do Marquito) a pedido do André, 2026-07-19
---

# O trabalho de IA do Marquito — atribuições, para uso no edital

> Documento de referência gerado sob demanda, antes do link do edital chegar. Objetivo: dar a você (André) contexto suficiente do que o Marquito vem construindo, pra entender como se encaixa no seu próprio ambiente de trabalho e pra avaliar depois, com o edital em mãos, que frentes fazem sentido escrever. Quando o edital chegar, este documento pode ser refinado.

## Uma frase

O Marquito projeta e constrói **sistemas de IA sob medida** — assistentes digitais personalizados que capturam conhecimento disperso, organizam com fidelidade a uma fonte (não inventam) e produzem artefatos navegáveis que crescem junto com quem os usa. Não é "chatbot genérico plugado numa API" — é arquitetura, com humano sempre na malha de decisão.

## O padrão-mestre (repete em todo projeto)

Todo sistema que ele constrói segue o mesmo fluxo, independente do domínio:

```
captura → curadoria → base de conhecimento → produção
 (bruto)   (triagem)     (consultável)        (documentos, respostas, ações)
```

- **Captura**: material vivo entra sem fricção — texto, áudio transcrito, documento colado, mensagem de bot (Telegram, geralmente).
- **Curadoria**: alguém (ou uma IA supervisionada) decide o que aquele material vira e onde mora.
- **Base de conhecimento**: fica organizada, versionada em git, auditável — a verdade do sistema vive em arquivos, não em caixa-preta.
- **Produção**: o sistema devolve valor — um documento pronto, uma resposta a uma pergunta, uma ação.

Esse é exatamente o desenho do **Cérebro Solunar**, que você já conhece por dentro: `inbox/raw` → `inbox/suggested` → `knowledge-base/` → `producao/`. Não é coincidência — é o mesmo padrão aplicado a outras organizações e profissionais.

## Princípio que atravessa tudo: humano-no-loop

Em nenhum desses sistemas a IA decide sozinha algo que importa. Ela prepara a decisão — organiza, resume, sugere — e devolve o controle pra pessoa ou pro coletivo. No Cérebro Solunar isso aparece explícito: "o cérebro não decide no lugar das pessoas; dá clareza para a decisão coletiva" (silêncio nunca vira consentimento). Esse não é um detalhe de implementação — é posição ética: a solução tem que continuar sendo **da pessoa/organização**, não uma dependência de fornecedor.

## A arquitetura técnica (o motor por trás)

- **Motor de execução:** Claude Code (Anthropic) — um agente de IA com acesso real a arquivos, terminal e ferramentas, não um chat de perguntas-e-respostas.
- **Skills:** unidades de domínio auto-ativáveis — cada uma sabe fazer uma coisa bem (pesquisar, gerar relatório, deployar site, escrever memória) e se aciona sozinha quando o contexto pede.
- **Memória:** cada assistente acumula conhecimento entre sessões — o que aprendeu sobre a organização, decisões passadas, convenções — sem precisar reexplicar tudo toda vez.
- **Hooks:** pontos de automação no ciclo de vida da conversa (início, fim, cada ferramenta usada) — é o que garante coisas como "sempre checar o estado real antes de dizer que algo foi resolvido".
- **Assistente digital (DA) próprio:** cada organização/pessoa tem o seu, com nome, voz e personalidade — não é um bot genérico compartilhado. O da Solunar é o **@SolunarBot**; o do Marquito (pessoal) é o **Jão**.

Toda essa engenharia é replicável por design — é template, não trabalho artesanal do zero a cada cliente.

## Caso vivo mais próximo de você: o Cérebro Solunar

Já está em produção, com uso real:
- Bot **@SolunarBot** no Telegram capturando material bruto e conduzindo deliberações por consentimento (🟢/🔴/💬), com rastreamento determinístico (sem IA, por hash — garante que nada se perde nem duplica).
- Base de conhecimento organizada por **container de papéis** (2 círculos, 9 papéis da holacracia da Solunar), cada um como um "workspace-especialista".
- Subsistema de **Finanças** — dashboard read-only + conciliador multiusuário — sobre o livro-caixa real da cooperativa.
- Tudo versionado em git, auditável, com confidencialidade respeitada (dado sensível não vaza pra fora do que a governança decidiu tornar público).

Isso é a prova mais concreta que existe: não é conceito de pitch, é sistema rodando com gente real usando.

## O padrão replicável (multi-tenant)

O mesmo desenho — cérebro de pastas + bot próprio + memória própria — já foi replicado para outras organizações e profissionais fora da Solunar (educação, terapia, consultoria, cultura), cada um com seu próprio assistente, sua própria base, seu próprio domínio de confidencialidade. A arquitetura é a mesma; o conteúdo e a voz são exclusivos de cada um. Isso é relevante pra edital porque mostra **produção de sistemas**, no plural — não é um projeto único, é um método de produção.

## Por que isso se encaixa em edital de "produção de sistemas com IA"

- Sistemas **reais em produção**, não provas de conceito — Solunar é o exemplo mais fácil de mostrar porque você tem acesso direto.
- **Metodologia própria e nomeada** (ICM — Interpreted-Context Methodology), não uso improvisado de ferramenta de mercado.
- **Human-in-the-loop como princípio de design**, alinhado com qualquer critério de uso responsável de IA que edital costuma pedir.
- **Conhecimento versionado e auditável** (git como infraestrutura, não só ferramenta de dev) — responde bem a critérios de transparência/governança de dados.
- **Replicabilidade** — não é sistema único e fechado, é padrão que se estende a outras organizações.

## Em aberto

Sem o link do edital ainda não dá pra saber categoria, valor, contrapartida exigida ou prazo — isso muda qual frente vale mais a pena puxar (ex.: só o caso Solunar vs. o padrão multi-tenant como um todo vs. algo focado em governança/consentimento assistido por IA). Assim que o link chegar, este documento serve de base pra filtrar o que escrever.

---

*Nota: link do edital chegou depois — é a Seleção Petrobras Cultural 2026 (ver `01_analise_aderencia.md` nesta pasta). A modalidade que melhor recebe esse trabalho é a 9, "Incubação e Desenvolvimento Cultural".*
