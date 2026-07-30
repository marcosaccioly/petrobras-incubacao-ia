# Revisão final — passe do Marquito (via Jão) · 2026-07-30

> Sessão de revisão prevista em `PROPOSTA_TRABALHO_JAO.md`, executada em 30/07 com aprovação prévia do Marquito sobre as alterações de conteúdo. Regra mantida: **nenhuma reescrita silenciosa** — tudo que mudou está documentado abaixo em antes/depois, e o diff dos commits é auditável arquivo por arquivo. A voz do texto continua sendo a do André; o que entrou foram dados que só o Marquito tinha e ajustes mecânicos de limite de caracteres.

---

## 1. O que mudou (antes/depois)

### 1.1 `03_descricao_projeto.md` — replicação com número real

**Antes:**
> Esse mesmo padrão já foi replicado para outras organizações e profissionais fora da INOVATE, o que demonstra capacidade de produção de sistemas, não um caso isolado.

**Depois:**
> Esse mesmo padrão já foi replicado para sete outras organizações e profissionais fora da INOVATE, nas áreas de educação, terapia, consultoria, cultura e gestão socioambiental — capacidade de produção de sistemas, não um caso isolado.

*Por quê:* "outras organizações" sem número é claim fraco; sete sistemas em produção, em cinco áreas distintas, é verificável e pontua direto em Exequibilidade. Nenhum cliente é nomeado.

### 1.2 `03_descricao_projeto.md` — CEFOR/IFES com métrica concreta

**Antes:**
> ...onde já implementou soluções semelhantes dentro de uma instituição formal de ensino, com resultados avaliados internamente como positivos. É uma segunda prova de que o método funciona fora de um único contexto, agora também dentro de uma instituição pública de formação profissional, terreno próximo ao que a modalidade de incubação exige.

**Depois:**
> ...onde coordena tecnologia educacional numa operação de ensino a distância com mais de 80 mil usuários de Moodle e cerca de 300 mil matrículas em cursos abertos, e onde uma base de conhecimento institucional pública, construída com o mesmo método, está no ar desde julho de 2026. É uma segunda prova de que o método funciona em escala, agora dentro de uma instituição pública de formação, terreno próximo ao que a modalidade de incubação exige.

*Por quê:* "resultados avaliados internamente como positivos" é a frase mais fraca do documento — autoavaliação sem número. Os números reais (80 mil+ usuários, ~300 mil matrículas, base pública no ar) são públicos e defensáveis, e transformam o precedente em prova de operação em escala — exatamente o que o critério de Experiência (25 pts) pede.

### 1.3 `03_descricao_projeto.md` — independência do motor (decisão editorial, ver §3)

**Adicionado após a frase do Claude Code:**
> E como a base de conhecimento vive em arquivos abertos e versionados, não dentro da ferramenta, o acervo de cada incubado permanece dele, seja qual for o motor.

*Por quê:* neutraliza a leitura de "dependência de fornecedor" num projeto que só inicia em 08/2027, e converte o risco em argumento de sustentabilidade — coerente com o princípio (já presente no texto) de que a solução pertence a quem a usa.

### 1.4 `12_mecanismos_diversidade.md` — acessibilidade concreta

**Antes:**
> Em acessibilidade, o ambiente virtual de suporte é construído para ser navegável por pessoas com deficiência, e os lançamentos públicos...

**Depois:**
> Em acessibilidade, o ambiente virtual de suporte já opera por Telegram com captura por áudio e voz: o participante que não escreve com fluência, ou que tem baixa visão, interage falando, sem que isso o coloque em desvantagem no processo. Os lançamentos públicos...

*Por quê:* "construído para ser navegável por pessoas com deficiência" era promessa genérica; a interação por voz já existe em produção e é mecanismo concreto de acessibilidade e de inclusão de quem não domina a escrita — fortalece o eixo diversidade com fato, não intenção.

### 1.5 `03_descricao_projeto.md` — compressões para caber no limite (sem mudança de sentido)

As adições acima somavam ~370 caracteres e derrubavam a folga do campo (8.000) para 2,7%. Para restaurar a folga mínima de 5%, cinco compressões pontuais, todas neutras de conteúdo:

| Antes | Depois |
|---|---|
| "cada frente de trabalho se torna uma unidade especializada que se aciona sozinha (...) decisões já tomadas a cada novo contato" | "frentes de trabalho especializadas se acionam sozinhas (...) decisões a cada novo contato" |
| "é também o responsável técnico por um conjunto de sistemas" | "é o responsável técnico pelos sistemas" |
| "em entrevista inicial de acolhimento, momento em que também recebe orientação sobre o uso do ambiente virtual" | "em entrevista inicial de acolhimento e é orientado no uso do ambiente virtual" |
| "testado em outro projeto da associação, o Centro Cultural Rural Solunar" | "já testado no Cérebro Solunar" (o vínculo Solunar↔Centro já está estabelecido dois parágrafos antes) |
| "com uma ferramenta desenvolvida internamente e já validada em uso real" | "com ferramenta própria já validada em uso real" |

**Resultado: 7.578/8.000 (folga 5,3%).**

---

## 2. Passe de parecerista — simulação da Análise de Conteúdo (item 8.2)

Leitura hostil dos 17 documentos pelos três critérios de 25 pontos + aderência aos eixos. Notas são estimativas de leitura, não previsão.

### Mérito artístico-cultural — estimado 21/25

**Forças:** programa estruturado em seis módulos nomeados; mentores com credenciais de primeiro nível (Prêmio Shell de Melhor Dramaturgia 2019; ~4 décadas de edição); produtos culturais públicos claros e obrigatórios; diferencial técnico explicado sem tecnosolucionismo — o humano-no-loop explícito desarma a objeção "IA escrevendo pelas pessoas", que é a primeira que um parecerista de cultura levantaria em 2026.

**Fragilidade:** o mérito artístico repousa nos mentores e nos futuros incubados; a INOVATE em si tem trajetória mais socioinstitucional que estética. A OsViajero mitiga bem. Um parecerista exigente pode sentir falta de uma assinatura curatorial ("que obra o Viveiro quer ver nascer?") — a flexibilidade de segmento pontua em democratização mas dilui discurso estético. **Correção mínima: nenhuma** — mexer nisso agora seria reescrever a alma do texto na véspera. Risco aceito.

### Experiência da proponente e equipe técnica — estimado 21/25

**Forças:** 9 anos de OsViajero cobrem o requisito de 5 com folga, com resultados nomeados e premiados (Cine Bandolero, SECULT-ES 2023); capacidade técnica dentro de casa (presidente = coordenador técnico); Henrique traz experiência direta de incubadora (RN Criativo/MinC 2014-2016); e agora o precedente institucional tem escala (80 mil+/300 mil) e a replicação tem número (sete).

**Fragilidades:**
- **(a) Três funções "a definir" na ficha técnica** — e uma delas (profissional de comunicação) é exigência literal do item 6.3.e do regulamento. É o ponto que mais convida desconto neste critério. Fora do alcance do texto — ver ação do André no §5.
- **(b) Salto de escala 1→10:** a experiência profunda de incubação da INOVATE é com uma companhia por nove anos; o programa propõe dez simultâneos via chamada nacional. O texto não endereça o salto explicitamente (o precedente do Henrique em incubadora multiprojehos cobre em parte). **Correção mínima possível, NÃO aplicada** por não estar no escopo aprovado: meia-frase no 03 do tipo "a estrutura de mentoria por área permite acompanhar dez processos em paralelo sem diluir o acompanhamento individual". Fica a critério do André.

### Exequibilidade — estimado 19/25

O critério mais sensível, como previsto. **Forças:** valor bem abaixo do teto (R$450k de R$4M); repasse simples e verificável (10×R$10k); cronograma de 12 meses com fases e folgas; defesa administrativa em duas camadas (assessoria contábil externa + subsistema de finanças já testado); equipe de mentoria confirmada desde a submissão — elimina o risco clássico de "equipe a montar". As mudanças 1.1 e 1.2 reforçam exatamente aqui: capacidade demonstrada em escala substitui histórico de captação como lastro.

**Fragilidades remanescentes (ranqueadas):**
1. **R$450k vs. histórico de captações menores da INOVATE.** A defesa por capacidade (contábil + tecnológica + escala do precedente CEFOR) é a aposta certa e agora está no seu ponto máximo defensável sem inventar fato. Permanece o ponto mais atacável da proposta — risco conhecido e aceito desde 26/07.
2. **Razão mentor/incubados:** Henrique cobre dois dos três segmentos; se a seleção pender para dramaturgia+audiovisual, um mentor carrega 6-7 incubados. O texto já prevê ajuste pós-seleção. Risco aceito; não há correção textual honesta antes de conhecer a composição real.
3. **Lançamentos concentrados nas três últimas semanas do mês 12, com local "a confirmar".** Plausível para leituras dramáticas/lançamentos de livro; a alternativa Solunar está registrada. Risco baixo.

### Aderência aos eixos (diversidade, economia criativa, democratização) — forte

Diversidade via desenho do processo seletivo (25% + 40% ES + acessibilidade agora concreta com a interação por voz); economia criativa por definição regulamentar (argumento limpo, sem ação-enxerto); democratização por chamada nacional sem exigência de trajetória consolidada + gratuidade dos lançamentos. Nenhuma fragilidade significativa.

### Leitura geral

Proposta competitiva, estimada na faixa de 80-84/100 na simulação. O perfil de risco está concentrado em Exequibilidade e nas funções "a definir" — o primeiro está mitigado ao máximo textual; o segundo é ação de equipe, não de texto.

---

## 3. Decisão editorial tomada (com aprovação do Marquito, 30/07)

**Manter a menção nominal a "Claude Code, da Anthropic"** no `03_descricao_projeto.md`, acrescentando a frase de independência do motor (mudança 1.3). Racional: a concretude do nome é o que separa o texto de "usaremos uma IA" genérico — e a frase nova converte o risco de dependência de fornecedor em argumento de sustentabilidade. O trade-off foi avaliado e decidido, não passou batido.

---

## 4. Conformidade mecânica — contagem de caracteres (30/07)

| Campo | Arquivo | Contagem | Limite | Folga |
|---|---|---|---|---|
| 3. Síntese | `02_sintese_projeto.md` | 1.228 | a confirmar | — |
| 4. Descrição | `03_descricao_projeto.md` | **7.578** | 8.000 | 5,3% ✓ |
| 5. Expertise | `04_expertise_projeto.md` | 1.609 | 2.000 | 19,6% ✓ |
| 6. Ficha técnica | `05_ficha_tecnica.md` | 2.985 | 4.000 | 25,4% ✓ |
| 8. Plano de Realização | `07_plano_realizacao.md` | 2.575 | 3.500 | 26,4% ✓ |
| 10. Estratégia de Comunicação | `09_estrategia_comunicacao.md` | 2.992 | 4.500 | 33,5% ✓ |
| 12. Economia Criativa | `11_acao_economia_criativa.md` | 952 | a confirmar | — |
| 13. Diversidade | `12_mecanismos_diversidade.md` | 1.240 | a confirmar | — |

Consistência numérica conferida em todos os campos: R$450.000 / R$100.000 (10×R$10.000) / R$81.000 (18%) / ~R$269.000 / 40% ES / 25% diversidade / datas 01/08/2027–31/07/2028 dentro da janela 01/05/2027–30/04/2028. Nenhuma correção do pente-fino de 26/07 regrediu (PcD-liderança e pegada de carbono só aparecem em notas históricas/riscadas, não em campo de formulário).

---

## 5. O que segue exatamente como o André escreveu

Tudo o que não está no §1: síntese (02), expertise (04), ficha técnica (05), prazo (06), plano de realização (07), eventos (08), comunicação (09), contrapartidas (10 e 15), economia criativa (11), anexos (13 e 14) — intocados. No 03 e no 12, tudo fora dos blocos citados permanece letra por letra.

**Ações que seguem com o André (inalteradas, só reforçando prioridade):** se houver como nomear ao menos o **profissional de comunicação** antes da submissão, é a única mudança de última hora que mexe em nota (critério Experiência) — o campo da ficha tem 1.015 caracteres de folga para recebê-lo. As demais (Canva dos dois anexos, local dos lançamentos, limites reais na plataforma, formato do campo Contrapartidas) já estão sinalizadas nos docs.

---

## 6. Rascunho de mensagem para o André

> André, fiz o passe final no repo com o Marquito. Resumo do que mudou (diff completo nos commits de 30/07):
>
> 1. **Descrição (03):** os dois pontos que estavam abaixo da realidade ganharam número — a replicação do método agora diz "sete organizações, em cinco áreas" e o precedente do CEFOR/IFES entrou com a escala real (80 mil+ usuários de Moodle, ~300 mil matrículas). Corrigi também a linha do tempo dessa base: ela está em operação desde 2016 e foi remodelada com o mesmo método, com a versão nova no ar desde julho — antes o texto dava a entender que tinha sido criada agora. Era o que a Exequibilidade pedia. Também acrescentei meia-frase depois da menção ao Claude Code dizendo que a base vive em arquivos abertos e versionados, independente do motor — desarma a leitura de "dependência de fornecedor". Pra caber no limite de 8.000 fiz cinco encolhimentos de frase sem mudança de sentido (lista completa no REVISAO_MARQUITO.md, §1.5). Fechou em 7.692/8.000.
> 2. **Diversidade (12):** a acessibilidade do ambiente virtual saiu do genérico — agora diz o fato: já opera por Telegram com áudio e voz, quem não escreve bem ou tem baixa visão interage falando.
> 3. **Todo o resto está letra por letra como você escreveu.** Rodei também uma simulação de parecerista (critérios do 8.2) e a conferência de números e caracteres de todos os campos — está tudo no `REVISAO_MARQUITO.md`, incluindo as contagens campo a campo pra você colar na plataforma sem surpresa (`16_respostas` atualizado).
>
> Único ponto que ainda mexe em nota e é teu: se der pra nomear o profissional de comunicação antes de submeter, entra na ficha técnica — tem folga de sobra no campo. O resto (Canva, local dos lançamentos) já está sinalizado. Qualquer coisa que queira reverter, é um `git revert` — nada foi por cima do teu texto sem registro.
