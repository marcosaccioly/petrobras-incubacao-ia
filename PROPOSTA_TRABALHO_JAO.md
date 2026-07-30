# Proposta de trabalho — passe final do "Viveiro do Amanhã" (rodar com Fable na VPS)

> Preparada pelo Jão em 2026-07-29 a pedido do Marquito. Este arquivo é um prompt de sessão: abrir Claude Code (Fable) em `~/dev/petrobras-incubacao-ia` e colar/apontar este documento.
> **Prazo real: submissão até 31/07/2026, 18h (Brasília).** Tudo aqui é cirúrgico — o texto está pronto e revisado (pente-fino de 26/07); a missão é reforçar, não reescrever.

## Contexto em três linhas

O André (Solunar) escreveu os 17 documentos desta pasta para a Seleção Petrobras Cultural 2026, modalidade 9 (Incubação), proponente INOVATE, R$ 450 mil. O Marquito não é revisor externo: é o presidente e representante legal da INOVATE e o coordenador técnico do "ambiente virtual de suporte" — o diferencial central da proposta descreve o método DELE (ICM, Cérebro Solunar, Claude Code). A contribuição dele é legítima e esperada; o cuidado é autoral: a voz do texto é do André, e ele dá a palavra final.

## Regras da sessão

1. **Nenhuma reescrita silenciosa.** Toda mudança proposta vai para `REVISAO_MARQUITO.md` (criar na raiz) em blocos antes/depois com justificativa de uma linha. Só aplicar nos arquivos o que o Marquito aprovar na conversa; commits atômicos, mensagens claras. Push só com ok explícito — o André precisa conseguir auditar o diff.
2. **Voz existente:** sóbria, densa, sem marketing, números colados nas afirmações. Manter.
3. **Não tocar** no projeto-irmão (`petrobras-cultural-2026-capixaba-eu`) nem inventar fato novo: todo claim adicionado precisa ser verdadeiro e verificável — na dúvida, perguntar ao Marquito na hora.
4. Ler antes de tudo: `00_status.md`, `01_analise_aderencia.md`, `16_respostas_completas_formulario.md`.

## Frente 1 — Passe de parecerista (prioridade máxima)

Simular a Análise de Conteúdo do Regulamento (item 8.2): **Mérito artístico-cultural (25) · Experiência da proponente e equipe técnica (25) · Exequibilidade (25) · aderência aos eixos (diversidade, economia criativa, democratização)**. Ler os 17 documentos como parecerista hostil e produzir nota por critério + lista ranqueada de fragilidades, cada uma com correção mínima proposta. Atenção especial a Exequibilidade: é onde R$ 450 mil vs. histórico de captações menores da INOVATE mais dói (a defesa atual é assessoria contábil + subsistema de finanças do Cérebro Solunar — checar se está convincente e consistente entre os campos 4, 5 e 16).

## Frente 2 — Dados que só o Marquito tem (o motivo de ele entrar na escrita)

Três pontos do texto atual estão abaixo do que a realidade permite afirmar:

- **CEFOR/Ifes vago:** `03_descricao_projeto.md` diz "resultados avaliados internamente como positivos". O Marquito coordena tecnologia educacional no Cefor/Ifes com **80 mil+ usuários de Moodle e ~300 mil matrículas em MOOCs**, e uma base de conhecimento institucional pública (v1.0 no ar desde 07/2026) construída com o mesmo método. Propor substituição com métrica concreta — validar com ele quais números podem ir a documento público de edital.
- **Replicação sem número:** o texto diz "já replicado para outras organizações". São **pelo menos 7 organizações/profissionais** com assistente próprio em produção (Solunar, e tenants nas áreas de educação, terapia, consultoria, cultura e gestão socioambiental). Confirmar com o Marquito o número e a forma anônima de citar ("já replicado para sete organizações e profissionais de quatro áreas distintas"). Exequibilidade agradece.
- **Acessibilidade do ambiente virtual genérica:** `12_mecanismos_diversidade.md` promete acessibilidade do ambiente sem dizer como. Fato real: os assistentes já operam por **Telegram com captura por áudio/voz** — participante que não escreve bem ou tem baixa visão interage falando. Concretizar em uma frase.

## Frente 3 — Decisão editorial a tomar COM o Marquito (não decidir sozinho)

`03_descricao_projeto.md` nomeia "Claude Code, da Anthropic" como motor. Trade-off: concretude (força) vs. parecerista apontar dependência de fornecedor num projeto que só começa em 08/2027 (risco). Recomendação do Jão: **manter a menção**, acrescentando meia-frase de que a base de conhecimento vive em arquivos abertos e versionados, independente do motor — alinha com o princípio "é seu de verdade" e transforma o risco em argumento de sustentabilidade. Decidir na sessão.

## Frente 4 — Conformidade mecânica

- Contar caracteres reais de cada campo vs. limite declarado (síntese ~1350/?, descrição ~7700/8000, expertise 2000, ficha 4000, plano 3500, comunicação 4500) — folga mínima de 5% para ajustes na plataforma.
- Conferir consistência de todos os números entre campos (450k / 100k / 81k / 269k / 10×10k / 40% / 18%) e datas (01/08/2027–31/07/2028 dentro da janela 01/05/2027–30/04/2028).
- Checar que nenhuma correção do pente-fino de 26/07 regrediu.

## Saída esperada da sessão — otimizada pro ANDRÉ, que é quem submete

O critério de pronto não é "Marquito revisou", é "**André abre o repo e consegue copiar e colar na plataforma sem retrabalho**". Portanto:

1. `REVISAO_MARQUITO.md` com: notas de parecerista por critério, fragilidades ranqueadas, blocos antes/depois propostos, decisões tomadas — escrito pra ser legível pelo André, não jargão interno.
2. Arquivos de campo (`02`–`16`) alterados só com o aprovado, commitados — e `16_respostas_completas_formulario.md` atualizado por último, refletindo o texto FINAL de cada campo, porque é dali que o André copia.
3. Contagem de caracteres de cada campo anotada no próprio `16_respostas` (ex.: "7.812/8.000"), pra ele não ter surpresa na plataforma.
4. Mensagem curta pro André (rascunho no fim do REVISAO): o que mudou, por quê, e o que segue exatamente como ele escreveu — meia página no máximo, tom de par, sem tratado.
5. Push só depois do ok do Marquito, pra chegar no André pelo GitHub já consolidado num diff limpo.

## Fora de escopo desta sessão

Pendências que são do André, não de texto: nomes de comunicação/acessibilidade/gestão financeira, Canva dos dois anexos, local dos lançamentos, limites reais na plataforma. Não gastar tempo nelas além de conferir que seguem sinalizadas.
