# BACKLOG GTM — Pinha / Ping Hai

> **O que este documento é.** A lista de **tudo o que falta fazer** na linha
> comercial da Pinha, destilada da reunião de sprint de 2026-10-24: doutrina dos
> quatro livros-fonte × estado real do projeto. É o artefato de execução — cada
> item é uma ação que fecha, com critério de pronto verificável.
>
> **Origem.** Cada tarefa nasce de um veredito **✘ falta** ou **◐ parcial** do
> [`CATALOGO-ESTRATEGIAS-PINHA.md`](CATALOGO-ESTRATEGIAS-PINHA.md), que por sua
> vez aponta o capítulo-fonte. Nenhuma tarefa aqui é opinião solta: todas têm
> linhagem rastreável até um livro.
>
> **Relação com o roadmap de engenharia.** Este backlog é **comercial/GTM**. O
> roadmap de engenharia continua sendo
> [`../ai-factory-task-pack/README.md`](../ai-factory-task-pack/README.md)
> (M0–M15b) e as pendências técnicas, [`open-work.md`](open-work.md). **Nenhum
> item daqui substitui item de lá.**
>
> **Status: NÃO VALIDADO.** Zero conversas de venda nesta linha — é o estado
> registrado em `GTM-dev.md`, `POSICIONAMENTO.md` e `DIAGNOSTICO.md`. Trate tudo
> como hipótese até a primeira conversa.

---

## Como ler este backlog

Cada tarefa tem ID, **fonte** (livro + estratégia), **pronto quando**, **bloqueia**,
**dono** e **bloqueador**. Os IDs `Bxx` são os mesmos citados no catálogo.

**Bloqueadores transversais** (aparecem em várias tarefas):

| Código | Bloqueador | Onde está registrado |
|---|---|---|
| **[NOME]** | Autorização para nomear o CTNI em peça que circula com terceiros | `CASE-CTNI.md` §6, `POSICIONAMENTO.md` §1, `COERENCIA.md` §7 |
| **[DOCS]** | As decisões abertas do `COERENCIA.md` §8 (nome, marca de camada, preço, ICP 2) | `COERENCIA.md` §8 |
| **[REAL]** | Falta de conversa com um comprador real — o insumo que valida ou derruba tudo | `GTM-dev.md` §"Status" |

**A regra de ouro deste backlog:** a métrica única continua sendo a do
`GTM-dev.md` — **conversas de diagnóstico realizadas**. Hoje: **0**. Toda tarefa
abaixo ou leva a essa conversa, ou prepara a peça que a conversa exige, ou
remove um bloqueio para ela.

---

## Visão de sprint — o que atacar agora

**Já está feito e não se mexe:** as 4 leituras, os 4 catálogos-fonte, o
`CATALOGO-ESTRATEGIAS-PINHA.md`, o roteiro v2 do vídeo de canal, a landing
reaberta pelo mecanismo, o post-isca e o post de apresentação (escritos), a
mensagem ao Laudezir (escrita, não enviada).

**As 3 tarefas que destravam o sprint inteiro** (nesta ordem):

1. **B01 + B02** — fixar o estágio de Awareness/Sophistication. São decisões de
   uma sessão que governam *todas* as peças seguintes. Sem isso, cada peça nova
   recomeça a discussão "o que a Pinha deve dizer".
2. **B24** — ter **uma** conversa com um comprador real. É o único insumo que
   substitui hipótese por fato.
3. **B07** — **publicar**, com cadência. A Pinha tem as peças e não publica; sem
   repetição (Williams C4) não existe memória nem marca.

> **Nota de sequência:** o `COERENCIA.md` §8 tem 5 decisões abertas que bloqueiam
> B10 (nome), B21 (preço/objeção) e B16 (ICP 2). Elas são decisão do fundador,
> não pesquisa — cabem numa sessão de 1 hora.

---

## ÉPICO E1 — Fundação doutrinária: o que dizer

*Por que existe:* Schwartz exige que se responda "que estágio é este mercado?"
antes de escrever. Hoje a resposta existe na prática em 2 peças e em nenhum
documento. Este épico fecha isso.

### B01 — Fixar o estágio de Awareness por ICP
- **Fonte:** Schwartz B1 (5 estágios de Awareness) / catálogo §1.2
- **O que fazer:** escrever qual estado de consciência cada ICP do
  `GTM-dev.md` está: ICP primário (empresa com IA em produção) e ICP
  secundário (agência/freelancer). Para cada um, o headline estruturalmente
  exigido.
- **Pronto quando:** existe um mapa `ICP → estágio → tipo de headline` em
  `POSICIONAMENTO.md` (nova §).
- **Bloqueia:** B18, B26, B28, B30, todas as peças futuras.
- **Dono:** fundador. **Bloqueador:** nenhum.

### B02 — Escrever o diagnóstico de Sophistication do mercado
- **Fonte:** Schwartz B2 (5 estágios de Sophistication) / catálogo §1.3
- **O que fazer:** documentar que "plataforma privada de IA na sua infra" já foi
  dita por Azure/AWS/OpenAI Enterprise (fonte: `ROTEIRO-VIDEO-CANAL.md`, Defeito
  1), e portanto o mercado está no **3º estágio** — o mecanismo manda. Registrar
  a escolha já feita na prática (roteiro v2 e landing).
- **Pronto quando:** seção curta em `POSICIONAMENTO.md` com a prova documental e
  a consequência ("o mecanismo é o headline").
- **Bloqueia:** B19, B22, B23, B25.
- **Dono:** fundador. **Bloqueador:** nenhum.

---

## ÉPICO E2 — Publicar: presença e cadência

*Por que existe:* Williams (C4, D-W12#2) e Ogilvy (C-O6): sem repetição não há
memória. A Pinha tem peças escritas e nenhuma publicada. Ogilvy: *"an advertisement
which pleases you because of its style… or one which sells the most?"*

### B07 — Publicar a primeira peça e fixar a cadência
- **Fonte:** Hormozi A-G7 (conteúdo) + Williams D-W12#2 + Ogilvy C-O6
- **O que fazer:** publicar **1** das peças já escritas
  (`campo/post-isca-custo-llm.md` no LinkedIn, dia útil de manhã) e definir a
  cadência mínima (ex.: 1 post/semana, o mesmo tema reforçado — Williams D-W11).
- **Pronto quando:** a peça está publicada, com data e link registrados, e existe
  um calendário de 4 semanas escrito.
- **Bloqueia:** B11, B12, B33.
- **Dono:** fundador. **Bloqueador:** nenhum (a isca não depende do [NOME]).
- **Nota:** o post de apresentação (`POSICIONAMENTO.md` §8.2) **não** nomeia o
  cliente — também pode sair. Fica atrás só pelo [NOME] a versão que **usa** o
  case.

### B33 — Transformar peças isoladas em campanha
- **Fonte:** Williams D-W12 #6 ("criar anúncios em vez de campanhas") e #2
  ("alcançar mais gente sem repetição")
- **O que fazer:** agrupar as peças existentes num tema único repetido
  (ex.: "privacidade é arquitetura, não política"), em vez de peças soltas.
  Aplicar o alerta #10: não tratar lançamento como evento isolado.
- **Pronto quando:** o calendário de B07 nomeia o tema único e as 4 peças que o
  reforçam por ângulos diferentes.
- **Bloqueia:** —. **Depende de:** B07.
- **Dono:** fundador. **Bloqueador:** nenhum.

### B32 — Decidir som/áudio (reticular activator)
- **Fonte:** Williams D-W10 (caps. 13 e 16: memória ecoica ~5s vs. icônica <1s;
  +29% para entender palavra escrita)
- **O que fazer:** decidir se os vídeos já roteirizados (CTNI e canal) são
  gravados — é o único canal que "gruda" segundo o Williams. Verificar antes se
  dependem do [NOME].
- **Pronto quando:** decisão escrita (gravar agora / gravar depois do [NOME] /
  descartar) com o motivo.
- **Bloqueia:** —. **Depende de:** [NOME] para o vídeo de canal.
- **Dono:** fundador. **Bloqueador:** **[NOME]** (para a versão de canal).

---

## ÉPICO E3 — Prospectar: os canais que não existem

*Por que existe:* o `GTM-dev.md` lista warm outreach, conteúdo, prospecção direta
e ads pagos — e **nenhum tem lista, cadência ou volume**. O Core Four é o "how to"
do Hormozi e está a zero.

### B06 — Lista de warm outreach + cadência
- **Fonte:** Hormozi B1 (#1 Warm Outreach; 10 passos, A-C-A, pergunta-âncora)
- **O que fazer:** escrever a lista dos primeiros 10–20 nomes (rede pessoal,
  NeoTek, quem já viu o trabalho), com a mensagem A-C-A por segmento. É o canal
  mais barato e o único que não depende de audiência.
- **Pronto quando:** lista com ≥10 nomes e a mensagem pronta; primeira mensagem
  enviada.
- **Bloqueia:** a métrica única (a primeira conversa de diagnóstico sai daqui).
- **Dono:** fundador. **Bloqueador:** nenhum.
- **⚠️ Memória relevante:** quando uma primeira venda trava, ele **amplia a
  coleta em vez de enviar a mensagem** — esta tarefa existe para forçar o envio.

### B08 — Lista fria + mensagem fria + volume
- **Fonte:** Hormozi B3 (#3 Cold Outreach; lista → personalização + big fast
  value → volume; ~3% convertem)
- **O que fazer:** montar a lista fria a partir dos canais já achados na
  sondagem de 2026-10-20 (Slack da Data Hackers é o único canal BR com massa;
  Programathor; LinkedIn BR), a mensagem com **big fast value** (entregar algo
  grande e rápido no 1º contato) e o volume mínimo.
- **Pronto quando:** lista de ≥30 alvos + mensagem fria escrita + volume diário
  definido.
- **Bloqueia:** —. **Depende de:** nada (usa a sondagem existente).
- **Dono:** fundador. **Bloqueador:** nenhum.

### B09 — Decidir (explicitamente) sobre ads pagos
- **Fonte:** Hormozi B4 (#4 Anúncios Pagos; LTGP:CAC ≥ 3:1, Client Financed
  Acquisition)
- **O que fazer:** registrar a **decisão** de não rodar ads pagos agora (o
  `GTM-dev.md` já sugere isso), com o gatilho de quando reconsiderar — em vez de
  deixar implícito.
- **Pronto quando:** uma linha de decisão escrita no `GTM-dev.md` com o gatilho.
- **Bloqueia:** —. **Dono:** fundador. **Bloqueador:** nenhum.

### B11 — Comprometer Open To Goal (ou Regra dos 100)
- **Fonte:** Hormozi D1 (Open To Goal) + A-G11 (Regra dos 100) + A-G17
- **O que fazer:** escolher **um** dos dois (o livro oferece os dois) e escrever
  o bloco diário de advertising. Sem isso, B06/B07/B08 não têm onde acontecer.
- **Pronto quando:** a rotina diária está escrita e existe o registro do 1º dia
  feito.
- **Bloqueia:** B12. **Depende de:** B06/B07/B08 definirem as ações.
- **Dono:** fundador. **Bloqueador:** nenhum.
- **⚠️ Memória relevante:** ele tem ADHD — a ação precisa ser minúscula e
  inequívoca ("abrir a lista, mandar 3 mensagens"), não "fazer advertising".

### B12 — Instrumentar o funil para achar a restrição
- **Fonte:** Hormozi A-G12 (Constraint: testar onde mais leads caem)
- **O que fazer:** só faz sentido depois de B07/B08 rodarem. Instrumentar as
  etapas (mensagem → resposta → conversa → diagnóstico) e identificar a etapa de
  maior queda.
- **Pronto quando:** existe um funil de 4 etapas com número em cada uma.
- **Bloqueia:** —. **Depende de:** B07, B08, B11.
- **Dono:** fundador. **Bloqueador:** nenhum.

### B17 — Posicionar a Pinha no roadmap dos 7 níveis
- **Fonte:** Hormozi D3 (roadmap dos 7 níveis)
- **O que fazer:** registrar em qual nível a Pinha está (pela leitura do livro:
  nível 1–2 — os amigos sabem, e ainda não há aviso consistente a todos).
- **Pronto quando:** uma linha no `GTM-dev.md` com o nível atual e o próximo.
- **Bloqueia:** —. **Dono:** fundador. **Bloqueador:** nenhum.

---

## ÉPICO E4 — Oferta e lead magnet

*Por que existe:* o diagnóstico é o lead magnet da Pinha (`DIAGNOSTICO.md`) e
cumpre o padrão do Hormozi — mas faltam os passos 4 e 5 dos 7 passos.

### B04 — Múltiplos formatos do diagnóstico + teste de nome
- **Fonte:** Hormozi A-G3 (7 passos do lead magnet: passo 4 = teste de nome;
  passo 5 = múltiplos veículos)
- **O que fazer:** (a) testar o **nome** do produto ("Relatório de Exposição e
  Custo" × alternativas); (b) gerar o mesmo conteúdo em **mais de um formato**
  (relatório + cálculo automatizado + vídeo curto de 5 min), porque o passo 5 dá
  2–4× de alcance pelo mesmo trabalho.
- **Pronto quando:** nome testado com ≥10 respostas da rede e ≥2 formatos
  definidos para o primeiro diagnóstico real.
- **Bloqueia:** a eficácia do diagnóstico no degrau 1.
- **Dono:** fundador. **Bloqueador:** nenhum.
- **Nota:** o passo 5 do `DIAGNOSTICO.md` §8 já lista "planilha/script de
  cálculo" — esta tarefa é a versão de advertising da mesma peça.

### B05 — Usar a escassez real da Pinha
- **Fonte:** Hormozi A-G4 (escassez real — "if you can't handle more than five
  new customers per week, say so")
- **O que fazer:** escrever a escassez **verdadeira** (uma pessoa operando, número
  limitado de implantações por trimestre) no Anexo B do template do diagnóstico.
- **Pronto quando:** o `DIAGNOSTICO-TEMPLATE.md` Anexo B declara o limite real.
- **Bloqueia:** —. **Dono:** fundador. **Bloqueador:** nenhum.
- **⚠️ Cuidado:** `POSICIONAMENTO.md` §6 proíbe over-claim — a escassez tem de ser
  real, não inventada.

---

## ÉPICO E5 — As pessoas que anunciam por você (Lead Getters)

*Por que existe:* o Hormozi diz que a alavancagem está em fazer **outros** fazerem
o Core Four. A Pinha tem um cliente-âncora em produção e nunca pediu indicação.

### B13 — Pedir indicação ao cliente-âncora
- **Fonte:** Hormozi C1 (#1 Clientes → indicações; goodwill = valor − preço; 7
  formas de pedir)
- **O que fazer:** aplicar **uma** das 7 formas de pedir (a forma 3 — pedir na
  hora em que o valor está sendo reconhecido — é a mais natural aqui, já que o
  CTNI acabou de receber a entrega). Antes, aplicar as 6 formas de dar valor para
  garantir que o goodwill existe.
- **Pronto quando:** um pedido de indicação feito ao cliente-âncora.
- **Bloqueia:** o caminho mais barato para a próxima conversa.
- **Dono:** fundador. **Bloqueador:** **[NOME]** apenas se o pedido mencionar
  publicamente o nome.
- **⚠️ Membria relevante:** o CTNI é o cliente-âncora e ele já disse que pode
  nomeá-lo — mas a **autorização registrada** é o que falta ([NOME]).

### B14 — Checklist de advertising treinável (3Ds)
- **Fonte:** Hormozi C2 (Funcionários; 3Ds: document/demonstrate/duplicate)
- **O que fazer:** documentar o processo de advertising (a lista, a mensagem, o
  follow-up) como checklist que **outra pessoa** possa executar — prerequisito
  para delegar quando houver receita. Os runbooks operacionais já existem; falta
  o de advertising.
- **Pronto quando:** checklist de 1 página que um terceiro executa sem você.
- **Bloqueia:** crescer além de uma pessoa.
- **Dono:** fundador. **Bloqueador:** nenhum (mas só faz sentido depois de
  B06/B07/B08 terem um processo).

### B15 — Decidir se contrata quem ensina canal (agências)
- **Fonte:** Hormozi C3 (Agências: contratar para aprender, com prazo)
- **O que fazer:** decisão explícita sobre contratar alguém/agência para aprender
  um canal novo (ex.: social/GTM), com o roteiro do livro ("quero fazer o que
  você faz em 6 meses, pago a mais para aprender, depois passo a consultoria").
- **Pronto quando:** decisão escrita com gatilho (quando a receita permitir).
- **Bloqueia:** —. **Dono:** fundador. **Bloqueador:** nenhum.

### B16 — Desenhar (ou descartar) a oferta do ICP secundário / afiliados
- **Fonte:** Hormozi C4 (#4 Afiliados; 6 passos) + `COERENCIA.md` §6
- **O que fazer:** as agências/freelancers que entregam IA (ICP secundário,
  `POSICIONAMENTO.md` §3) são os afiliados naturais da Pinha. O `COERENCIA.md` §6
  registra que a oferta deles **não existe** (sem preço, canal nem entrega).
- **Pronto quando:** decisão escrita: oferta desenhada (com % de comissão) **ou**
  descarte formal com motivo.
- **Bloqueia:** —. **Dono:** fundador. **Bloqueador:** **[DOCS]** (decisão de
  escopo aberta no `COERENCIA.md` §6).

---

## ÉPICO E6 — Copy e mensagem: aplicar o que os livros ensinam

*Por que existe:* Schwartz, Ogilvy e Williams dão o "como escrever" — e há lacunas
concretas: objeção não redefinida, mecanismo sem nome, brechas abertas.

### B18 — Checklist de headline e revisão de peças
- **Fonte:** Schwartz B-S4 (headline só força a 2ª frase) + B-S14 (momentum) +
  Ogilvy C-O11 (regras de headline)
- **O que fazer:** escrever um checklist curto de headline (marca visível? benefit
  claro? força a leitura da 2ª frase? tem momentum?) para revisar toda peça antes
  de publicar.
- **Pronto quando:** checklist de ≤10 itens anexado ao processo de B07.
- **Bloqueia:** qualidade das peças futuras. **Depende de:** B01.
- **Dono:** fundador. **Bloqueador:** nenhum.

### B19 — Lista de claims ordenada por força
- **Fonte:** Schwartz B-S5 (Intensification; *não repita, reforce*)
- **O que fazer:** listar as provas/claims da Pinha (do `CASE-CTNI.md` §3 e
  `OWUI-PRODUTO.md`) e ordená-las por força, para cada peça escolher a mais forte
  e **reforçar** em ângulos novos em vez de repetir.
- **Pronto quando:** tabela `claim → força → ângulo` em `POSICIONAMENTO.md`.
- **Bloqueia:** B21, B22. **Depende de:** B02.
- **Dono:** fundador. **Bloqueador:** nenhum.

### B20 — Nomear o papel de identificação do comprador
- **Fonte:** Schwartz B-S6 (Identification: character/achievement roles, ponte de
  credibilidade)
- **O que fazer:** definir **com quem** o material quer que o leitor se
  identifique (achievement role: "o CTO que colocou IA com documento interno sem
  virar caso de compliance") e a ponte de credibilidade (a prova é o caso —
  `SONDAGEM-MERCADO` §2.3: "a credencial é o caso, não o certificado").
- **Pronto quando:** o papel nomeado em `POSICIONAMENTO.md` §3.
- **Bloqueia:** —. **Dono:** fundador. **Bloqueador:** nenhum.

### B21 — Redefinir a objeção "é caro / por que não o Azure?"
- **Fonte:** Schwartz B-S8 (Redefinition: simplificação, escalada, redução de
  preço)
- **O que fazer:** a objeção que mata a venda não tem resposta escrita. Usar as
  três técnicas: **simplificação** (o preço de tabela é implementação, não
  assinatura eterna), **escalada** (o custo real é o risco de compliance e a
  fatura que dobra — `DIAGNOSTICO.md` mapa 2), **redução de preço** (o abatimento
  de 30 dias).
- **Pronto quando:** parágrafo de redefinição + onde ele aparece em cada peça.
- **Bloqueia:** —. **Depende de:** B19, [DOCS] (decisão de preço do `COERENCIA`
  §8).
- **Dono:** fundador. **Bloqueador:** **[DOCS]**.

### B22 — Dar nome próprio ao mecanismo
- **Fonte:** Schwartz B-S9 (Mechanization: nomear, descrever, destacar)
- **O que fazer:** o mecanismo *"o dado é removido antes de virar consulta"* está
  descrito e destacado, mas é anônimo. Nomeá-lo (o "Platformate" do Schwartz;
  Ogilvy também usa o exemplo). Cuidado: nome de mecanismo **não** é nome de
  componente interno (`POSICIONAMENTO.md` §6).
- **Pronto quando:** o mecanismo tem nome, usado consistentemente na landing, no
  roteiro e na isca.
- **Bloqueia:** —. **Depende de:** B02, B19.
- **Dono:** fundador. **Bloqueador:** nenhum.

### B23 — Destruir as alternativas do comprador (com a solução)
- **Fonte:** Schwartz B-S10 (Concentration: nunca atacar sem trazer a solução) +
  Williams D-W8 (a clareza que custa insulto)
- **O que fazer:** o `POSICIONAMENTO.md` §4 lista as 4 alternativas (fazer
  interno, agência, gateway SaaS, dev genérico). Transformar em peça que **as
  desmonta trazendo a solução** — nunca atacando seco.
- **Pronto quando:** a desmontagem das 4 alternativas escrita, respeitando a regra
  do Schwartz.
- **Bloqueia:** —. **Depende de:** B02.
- **Dono:** fundador. **Bloqueador:** nenhum.

### B25 — Passar a marca pela Grande Ideia e pela doutrina "positively good"
- **Fonte:** Ogilvy C-O4 (teste das 5 perguntas da Grande Ideia) + C-O5 (produto
  de paridade → "positively good")
- **O que fazer:** a Pinha vende um produto de **paridade** (Azure/AWS dizem o
  mesmo) — é o caso exato da doutrina. Testar a metáfora da pinha pelas 5
  perguntas e escrever a peça com "positively good" em vez de "superior".
- **Pronto quando:** as 5 respostas registradas e uma peça reescrita nessa linha.
- **Bloqueia:** —. **Depende de:** B02.
- **Dono:** fundador. **Bloqueador:** nenhum.

### B26 — Copy longa e factual para o CTO
- **Fonte:** Ogilvy C-O10 (copy longa, factual) + C-O8 (observar a resposta
  direta: 2 min, long copy)
- **O que fazer:** para o comprador técnico (CTO), escrever a **versão longa e
  factual** (como o `CASE-CTNI.md` e o `OWUI-PRODUTO.md`, que já são longos) —
  a landing atual usa copy curta e é o registo do dono de empresa, não do CTO.
- **Pronto quando:** existe uma peça longa factual para o CTO, distinta da
  landing curta.
- **Bloqueia:** —. **Depende de:** B01.
- **Dono:** fundador. **Bloqueador:** nenhum.

### B27 — Escrever o princípio do Velcro no guia de copy
- **Fonte:** Williams D-W3 (Velcro da mente; loops aleatórios vs. arrumadinhos)
- **O que fazer:** registrar como princípio de copy da linha: informação
  previsível é esquecida; a mensagem memorável é a não-óbvia. Aplicado na isca,
  não é princípio escrito.
- **Pronto quando:** o princípio está no checklist de B18.
- **Bloqueia:** —. **Dono:** fundador. **Bloqueador:** nenhum.

### B28 — Reescrever a landing com o "you" (Home Movies)
- **Fonte:** Williams D-W4 (a palavra "you") + D-W5 (Home Movies: nunca aponte a
  câmera para você)
- **O que fazer:** a landing atual fala do **sistema** ("o portal devolve 503")
  mais que do **leitor**. Reescrever os blocos para pôr o leitor dentro (o
  anúncio-modelo da Rolex: a posse já transferida), sem perder a prova.
- **Pronto quando:** a landing tem o "you" como sujeito da cena, revisada contra
  B01.
- **Bloqueia:** —. **Depende de:** B01.
- **Dono:** fundador. **Bloqueador:** nenhum.

### B29 — Conversor feature → benefício
- **Fonte:** Williams D-W6 (". . . which means . . .")
- **O que fazer:** criar o par transformador para as features técnicas (pgvector,
  fail-closed, owner-scoped) → benefício de negócio. É o conversor barato de
  especificação em valor.
- **Pronto quando:** tabela `feature → . . . which means . . . → benefício`.
- **Bloqueia:** B30, B26.
- **Dono:** fundador. **Bloqueador:** nenhum.

### B30 — Fechar as brechas do anúncio (técnica do parênteses)
- **Fonte:** Williams D-W7 (cap. 11: o pensamento do cliente entre parênteses)
- **O que fazer:** passar **cada** peça-chave (landing, mensagem de outreach,
  Anexo B do diagnóstico) pela técnica, escrevendo a objeção que o CTO faria em
  cada frase e fechando-a ali. O leitor da Pinha é cético por profissão.
- **Pronto quando:** as 3 peças-chave passaram e as brechas estão fechadas.
- **Bloqueia:** —. **Depende de:** B01, B29.
- **Dono:** fundador. **Bloqueador:** nenhum.

### B31 — Descrever o que espera o cliente depois do clique
- **Fonte:** Williams D-W9 (Walking into darkness: nunca peça que o cliente entre
  num quarto escuro)
- **O que fazer:** as peças públicas não descrevem o **que acontece depois** de a
  pessoa responder. Descrever, passo a passo, o que espera o cliente (a conversa
  de descoberta → o diagnóstico → o relatório) — o diagnóstico interno já faz
  isso no template, o público não.
- **Pronto quando:** o "depois do clique" está descrito numa peça pública.
- **Bloqueia:** —. **Depende de:** B05.
- **Dono:** fundador. **Bloqueador:** nenhum.

---

## ÉPICO E7 — Mercado e validação

### B24 — Ter uma conversa com um comprador real
- **Fonte:** Ogilvy C-O1 (faça o dever de casa, inclusive o consumidor) +
  Hormozi (a pergunta de diagnóstico) + a regra de ouro do `GTM-dev.md`
- **O que fazer:** conduzir **uma** conversa de 30 min com alguém do ICP,
  usando o roteiro de `DIAGNOSTICO-REUNIAO.md` adaptado a descoberta (não a
  venda). O objetivo não é vender: é ouvir se a dor existe e corrigir o
  posicionamento.
- **Pronto quando:** uma conversa realizada e as 3 frases do Bloco 4.1 escritas.
- **Bloqueia:** valida (ou derruba) todos os outros épicos.
- **Dono:** fundador. **Bloqueador:** nenhum.
- **⚠️ Memória relevante:** a métrica única do `GTM-dev.md` é exatamente esta —
  e está em 0.

### B10 — Fechar as decisões abertas do `COERENCIA` §8
- **Fonte:** Hormozi A-G10 (More Better New: "posicionamento novo" exige
  posicionamento fechado) + `COERENCIA.md` §8
- **O que fazer:** decidir, numa sessão: (1) o nome público descreve a
  capacidade ou o motor; (2) aplicar a marca `[ENTREGUE]/[PARCIAL]/[TESE]`;
  (3) qual price sheet é a porta; (4) ICP secundário (ver B16); (5) o bloco de
  tese no vídeo.
- **Pronto quando:** as 5 caixas `[ ]` do `COERENCIA.md` §8 estão marcadas com a
  decisão.
- **Bloqueia:** B21 (preço), B16 (ICP 2), B25/B22 (marca).
- **Dono:** fundador. **Bloqueador:** nenhum.

---

## ÉPICO E8 — Pré-requisitos administrativos

### B34 — Endereço próprio do Ping Hai (domínio + e-mail)
- **Fonte:** `GTM-dev.md` §"Quem fala com o cliente" (pendência já registrada)
- **O que fazer:** decidir e criar o endereço da Ping Hai; trocar o CTA provisório
  (LinkedIn do sócio) pelo endereço do domínio — **nunca** o Gmail pessoal.
- **Pronto quando:** o CTA da landing aponta para o endereço da empresa.
- **Bloqueia:** credibilidade de qualquer peça pública.
- **Dono:** fundador. **Bloqueador:** nenhum.

### B35 — Resolver a autorização de nomear o CTNI por escrito
- **Fonte:** `CASE-CTNI.md` §6, `POSICIONAMENTO.md` §1, `COERENCIA.md` §7 —
  **[NOME]**
- **O que fazer:** obter a autorização (de preferência por escrito) para nomear o
  cliente em peça que circula com terceiros — o caso mais exigente, que cobre o
  vídeo de canal, o site e o case.
- **Pronto quando:** a autorização existe e está registrada em
  `CASE-CTNI.md` §6.
- **Bloqueia:** B32 (vídeo de canal), B13 (indicação nomeada), o caso público, a
  mensagem ao Laudezir.
- **Dono:** fundador. **Bloqueador:** o próprio contato com o cliente.
- **⚠️ Memória relevante:** em 2026-10-19 ele **já disse que pode nomear**. O que
  falta é o **registro da autorização na peça**, não a permissão de fato. Não
  tratar o próprio documento como fato jurídico.

---

## Anexo 1 — Rastreabilidade: livro → capítulo → tarefa

| Livro | Estratégia | Tarefas |
|---|---|---|
| Hormozi | A1–A2 engaged lead | B03 |
| Hormozi | A3–A5 lead magnet, 7 passos | B04, B05 |
| Hormozi | B1 warm outreach | B06 |
| Hormozi | B2 conteúdo | B07, B33 |
| Hormozi | B3 cold outreach | B08 |
| Hormozi | B4 anúncios pagos | B09 |
| Hormozi | B7 More Better New / constraint | B10, B12 |
| Hormozi | C1 indicações | B13 |
| Hormozi | C2 funcionários (3Ds) | B14 |
| Hormozi | C3 agências | B15 |
| Hormozi | C4 afiliados | B16 |
| Hormozi | D1–D3 execução / roadmap | B11, B17 |
| Schwartz | B1 awareness | B01, B18, B26, B28, B30 |
| Schwartz | B2 sophistication | B02, B19, B22, B23, B25 |
| Schwartz | D1–D3 intensification/gradualization | B19 |
| Schwartz | D4–D7 redefinition/mechanization/concentration/camouflage | B21, B22, B23 |
| Schwartz | D8 final touches | B18 |
| Ogilvy | A2 dever de casa | B24 |
| Ogilvy | A4 grande ideia / A5 positively good | B25 |
| Ogilvy | B1–B3 resposta direta, testar | B04, B26 |
| Ogilvy | C1–C3 regras de execução | B18 |
| Williams | B1–B2 not who you reach / previsível | (base — sem tarefa) |
| Williams | B3–B4 velcro / "you" | B27, B28 |
| Williams | B7 fechar brechas | B30 |
| Williams | C2 walking into darkness | B31 |
| Williams | C3 reticular activator / som | B32 |
| Williams | C4 hardwood, hammer, nail | (base — governa a disciplina) |
| Williams | C6 doze erros | B33 |

## Anexo 2 — Definição de pronto (o que todas as tarefas herdam)

1. **A frase que sai da peça pode ser dita em voz alta sem virar over-claim**
   (`POSICIONAMENTO.md` §6).
2. **Verbo no que existe** — `[ENTREGUE]` e não `[TESE]` (`COERENCIA.md` §3).
3. **Nenhum nome de componente interno** em peça pública (small-pine,
   small-router, M7/M8/M9) — só na conversa, como prova.
4. **Nenhum nome de cliente** sem [NOME] resolvido.
5. **A peça fecha uma brecha a mais** do que a anterior (Williams C4: afie a
   peça, não troque o prego).

---

## Referências

- Mapa completo com vereditos: [`CATALOGO-ESTRATEGIAS-PINHA.md`](CATALOGO-ESTRATEGIAS-PINHA.md)
- Catálogos-fonte: `/tmp/pinha-books/{leads,schwartz,ogilvy,wizard}/`
- Estratégia comercial: [`GTM-dev.md`](GTM-dev.md), [`POSICIONAMENTO.md`](POSICIONAMENTO.md)
- Produto do degrau 1: [`DIAGNOSTICO.md`](DIAGNOSTICO.md), [`DIAGNOSTICO-TEMPLATE.md`](DIAGNOSTICO-TEMPLATE.md), [`DIAGNOSTICO-REUNIAO.md`](DIAGNOSTICO-REUNIAO.md)
- Decisões abertas: [`COERENCIA.md`](COERENCIA.md) §8
- Roadmap de engenharia (não é este): [`../ai-factory-task-pack/README.md`](../ai-factory-task-pack/README.md)
