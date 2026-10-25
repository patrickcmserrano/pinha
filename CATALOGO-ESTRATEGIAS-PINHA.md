# CATÁLOGO DE ESTRATÉGIAS — Pinha / Ping Hai

> **O que este documento é.** A consolidação dos **quatro livros-fonte** em uma
> única lista de estratégias, processos e metodologias — **cada uma com veredito
> de aplicabilidade à Pinha** (✔ já tem / ◐ parcial / ✘ falta) e o ponteiro para a
> tarefa do backlog que fecha a lacuna.
>
> **O que ele NÃO é.** Não é resumo dos livros (isso é o catálogo-fonte, um por
> livro) e não é plano de engenharia (isso é o `ai-factory-task-pack`). É o mapa
> entre **doutrina de advertising** e **o que a Pinha precisa fazer**.
>
> **Fontes (catálogo-fonte, com texto puro ao lado):**
>
> | Livro | Catálogo | Texto puro | Papel |
> |---|---|---|---|
> | *$100M Leads* — Alex Hormozi, 2023 | `/tmp/pinha-books/leads/catalogo.md` | `/tmp/pinha-books/leads/book.txt` | **o que fazer** — canais, volume, ordem |
> | *Breakthrough Advertising* — Eugene M. Schwartz, 1966 | `/tmp/pinha-books/schwartz/catalogo.md` | `/tmp/pinha-books/schwartz/book.txt` | **o que dizer** — awareness, sofisticação |
> | *Ogilvy on Advertising* — David Ogilvy, 1983 | `/tmp/pinha-books/ogilvy/catalogo.md` | `/tmp/pinha-books/ogilvy/book.txt` | **como escrever** — ofício e pesquisa |
> | *The Wizard of Ads* — Roy H. Williams, 1998 | `/tmp/pinha-books/wizard/catalogo.md` | `/tmp/pinha-books/wizard/book.txt` | **por que gruda** — memória e repetição |
>
> ⚠️ Os catálogos-fonte vivem em `/tmp`, que o sistema pode limpar. **Este
> documento é o artefato durável.**
>
> **Status: NÃO VALIDADO.** Como todos os documentos comerciais da linha, isto é
> o mapa de intenção — zero conversas de venda aconteceram. Substituir pelo que a
> primeira conversa ensinar.

---

## 0. Como ler os vereditos

| Marca | Significado |
|---|---|
| **✔ tem** | A Pinha já aplica/possui isto, com lastro em documento ou código |
| **◐ parcial** | Existe em versão mais fraca, ou existe o insumo mas não o artefato |
| **✘ falta** | Não existe hoje — e a doutrina diz que deveria |

Cada linha fecha com **→ Bxx**, o ID da tarefa no
[`BACKLOG-GTM.md`](BACKLOG-GTM.md). Onde não há tarefa, o veredito é **✔ tem**
(nada a fazer) ou a tarefa já está coberta por outro item.

**A regra que governa tudo** (as três primeiras estratégias são o alicerce; sem
elas o resto não converte):
1. **Mass Desire** (Schwartz A1) — o desejo existe; você canaliza.
2. **O que dizer > quem alcançar** (Williams B1) — a mensagem importa mais que a lista.
3. **Não troque o prego; afie a peça** (Williams C4) — diante de resultado fraco, melhore a peça antes de mudar o posicionamento.

---

## 1. O diagnóstico do mercado da Pinha (Schwartz, aplicado)

Antes de escrever qualquer peça, as três perguntas de Schwartz. Respondê-las é o
que decide **o que a Pinha deve dizer**.

### 1.1 Mass Desire **[Schwartz A1]** — ✔ tem
O desejo que cria o mercado da Pinha **não é "IA"**: é *"usar IA com os meus
documentos sem que o dado saia de casa"*. Está capturado em
`POSICIONAMENTO.md` §2 e §5. O `CASE-CTNI.md` §1 confirma que o cliente pediu
literalmente *"o ChatGPT deles, rodando na infraestrutura deles"*.
→ Sem tarefa (fundamento correto).

### 1.2 State of Awareness **[Schwartz B1]** — ◐ parcial
A Pinha **não fixou em que estágio o seu prospect está**. Pelas peças atuais, o
alvo declarado (`GTM-dev.md` ICP) é **Problem-Aware** (sabe que dado vaza, não sabe
a solução) e **Solution-Aware** (sabe que existe solução, não conhece a Ping Hai).
Mas a landing recente (`index.html`) abre por **mecanismo** — o que é headline de
estágio 3 de *Sophistication*, não de consciência.
→ **B01** (fixar o estágio-alvo por ICP e revisar as peças contra ele).

### 1.3 State of Sophistication **[Schwartz B2]** — ◐ parcial
Este é o **diagnóstico mais importante e ainda não escrito.** A pergunta: quantos
já apresentaram "plataforma privada de IA na sua infraestrutura" a esse comprador
antes da Pinha? A resposta é **muitos** — Azure, AWS, OpenAI Enterprise
(`ROTEIRO-VIDEO-CANAL.md` já nota: *"a promessa é persuasiva e não é única"*).
Isso põe o mercado no **estágio 3 (claims saturados → entra o MECANISMO)**.
A conclusão está **certa e já aplicada** no roteiro v2 (mecanismo virou Bloco 3) e
na landing reaberta — mas não existe como documento diagnóstico que outras peças
possam consultar.
→ **B02** (escrever o diagnóstico de sofisticação como documento; já está
resolvido na prática para 2 peças).

---

## 2. Anexo A — *$100M Leads* (Hormozi): o que fazer

### 2.1 Fundamentos

| # | Estratégia | Veredito | Estado hoje / o que falta | Tarefa |
|---|---|---|---|---|
| A-G1 | *Lead ≠ **engaged lead*** — a métrica não é mão levantada, é consumo | ◐ | `GTM-dev.md` define a métrica única como **"conversas de diagnóstico realizadas"** — que é um *lead*, não um engaged lead consumido. Não há definição escrita de engaged lead para a Pinha | **B03** |
| A-G2 | Oferta ≠ **lead magnet** (solução completa de problema estreito, que revela o próximo) | ✔ | O **diagnóstico de 1 semana** (`DIAGNOSTICO.md`) é exatamente isto: solução completa de um problema estreito (a intuição sem número) que revela o problema seguinte (a implementação) | — |
| A-G3 | Os **7 passos do lead magnet** | ◐ | O diagnóstico cobre os passos 1–3, 6, 7. **Falta o passo 4 (teste de nome/headline)** e o **passo 5 (múltiplos formatos/veículos)** — hoje é um relatório só | **B04** |
| A-G4 | **Escassez** real | ✘ | `DIAGNOSTICO.md` §6/§7 proíbe over-claim, mas nenhuma peça usa a escassez **real** que a Ping Hai tem: uma pessoa operando, número limitado de implantações | **B05** |
| A-G5 | **Urgência** + o "motivo inventado" (*because*) | ✔ | O abatimento do diagnóstico **em até 30 dias** (`DIAGNOSTICO-TEMPLATE.md` Anexo B) é urgência com data real | — |

### 2.2 O Core Four

| # | Estratégia | Veredito | Estado hoje / o que falta | Tarefa |
|---|---|---|---|---|
| A-G6 | **Warm outreach** (10 passos, A-C-A, pergunta-âncora, cinco primeiros grátis) | ◐ | Existe a **rede pessoal** (`GTM-dev.md` canal "Rede pessoal / NeoTek") e a mensagem ao Laudezir tem A-C-A. **Falta a lista de warm outreach** e a cadência | **B06** |
| A-G7 | **Postar conteúdo** (hook–retain–reward, give:ask, *give until they ask*) | ◐ | Existem **2 peças escritas** (`post-isca-custo-llm.md` e o post de apresentação `POSICIONAMENTO.md` §8.2) — mas **zero publicadas** e **sem cadência**. O `ROTEIRO-VIDEO-CANAL.md` é peça de canal, não de conteúdo aberto | **B07** |
| A-G8 | **Cold outreach** (lista → personalização + big fast value → volume; 3% converte) | ✘ | O `GTM-dev.md` prevê **"prospecção direta"** como canal, mas **não existe lista, nem mensagem fria, nem volume**. A sondagem de 2026-10-20 achou os canais (Data Hackers, Programathor) — falta o pipeline | **B08** |
| A-G9 | **Anúncios pagos** (call out + value + CTA, What-Who-When, LTGP:CAC) | ✘ | Nenhuma verba, nenhum criativo, nenhum teste. `GTM-dev.md` registra que ads pagos não estão no plano atual — **provavelmente correto para o estágio**, mas precisa ser decisão explícita | **B09** |
| A-G10 | **More Better New** — a ordem (posicionamento → plataforma → Core Four) | ◐ | O `COERENCIA.md` §2 ainda tem **decisão aberta** sobre o nome público (capacidade × motor) — e "New: posicionamento novo" exige posicionamento **fechado** primeiro | **B10** |
| A-G11 | **Regra dos 100** (100 ações/dia, 100 dias) | ✘ | Não há compromisso de volume diário em nenhum canal | **B11** |
| A-G12 | **Constraint** — testar onde mais leads caem | ✘ | Sem funil instrumentado, não há como achar a restrição. Depende de A-G7/A-G8 existirem | **B12** |

### 2.3 Os Lead Getters

| # | Estratégia | Veredito | Estado hoje / o que falta | Tarefa |
|---|---|---|---|---|
| A-G13 | **Clientes → indicações** (goodwill = valor − preço; 6 formas de dar valor; 7 de pedir) | ✘ | O CTNI é o cliente-âncora e **nunca foi pedida indicação** a ele. As 6 formas de dar valor estão parcialmente cobertas pelo `DIAGNOSTICO.md` §6 (armar o CTO para levar adiante), mas não como sistema | **B13** |
| A-G14 | **Funcionários** (3Ds: document/demonstrate/duplicate) | ◐ | Há sócios (Ping Hai é sociedade) e a operação é de uma pessoa. Os **checklists operacionais existem** nos runbooks (`runbook-prod-chatsubo.md`), mas não há checklist de advertising para treinar alguém | **B14** |
| A-G15 | **Agências** (contratar para aprender, com prazo e deadline) | ✘ | Não considerado. Para a Pinha, o análogo é **contratar quem ensine canal** (ex.: alguém que faça social/Go-to-market) — decisão não tomada | **B15** |
| A-G16 | **Afiliados** (6 passos; whisper–tease–shout; integração) | ◐ | O **ICP secundário** (agências/freelancers que entregam IA, `POSICIONAMENTO.md` §3) é o afiliado natural — e o `COERENCIA.md` §6 marca a oferta dele como **não desenhada** | **B16** |

### 2.4 Execução

| # | Estratégia | Veredito | Estado hoje / o que falta | Tarefa |
|---|---|---|---|---|
| A-G17 | **Open To Goal** (bloco aberto diário) | ✘ | Sem rotina de advertising alocada | **B11** (junto da Regra dos 100) |
| A-G18 | **Checklist de 1 página** | ✔ | O `GTM-dev.md` §"Próximo passo" **é** quase isto: 3 ações, 1 métrica. Falta virar o formato de 5 passos explícito | — (coberto por **B07**) |
| A-G19 | **Roadmap dos 7 níveis** | ◐ | `GTM-dev.md` descreve o estágio atual em prosa, mas não posiciona a Pinha **no nível** (o livro diria: nível 1–2 — amigos sabem, e você ainda não avisa todos de forma consistente) | **B17** |

---

## 3. Anexo B — *Breakthrough Advertising* (Schwartz): o que dizer

| # | Estratégia | Veredito | Estado hoje / o que falta | Tarefa |
|---|---|---|---|---|
| B-S1 | **Mass Desire** (canalizar, não criar) | ✔ | `POSICIONAMENTO.md` §5 ("ideia → prova → convite") parte do desejo, não do produto | — |
| B-S2 | **Os 5 estágios de Awareness** | ◐ | Ver §1.2. Falta fixar o estágio por ICP | **B01** |
| B-S3 | **Os 5 estágios de Sophistication** (no 3º, o mecanismo vira headline) | ✔ | **Aplicado** no `ROTEIRO-VIDEO-CANAL.md` v2 (Bloco 3 = mecanismo) e na landing reaberta (`landing-pinha-reaberta-pelo-mecanismo-2026-10-24`) | **B02** (documentar) |
| B-S4 | **O headline só precisa forçar a 2ª frase** | ◐ | As peças atuais ainda tentam vender no headline em alguns pontos; a regra não está escrita como guia de revisão | **B18** |
| B-S5 | **Intensification** (13 formas) + *não repita, reforce* | ◐ | O roteiro v2 **aplica** (2B × 3.1 desduplicados). Falta a **lista de claims** ordenada por força, para as outras peças usarem | **B19** |
| B-S6 | **Identification** (character/achievement roles, ponte de credibilidade) | ◐ | O `CASE-CTNI.md` §6 diz como usar por público; o `SONDAGEM-MERCADO` diz que a credencial é o **caso**. Não há role de identificação **nomeado** para o material | **B20** |
| B-S7 | **Gradualization** (arquitetura da crença, inclusion question) | ✔ | **Aplicado exemplarmente**: o roteiro v2 abre sem claim (Defeito 1 corrigido). A landing reaberta também | — |
| B-S8 | **Redefinition** (simplificação, escalada, redução de preço) | ✘ | A objeção nº 1 da Pinha é **"é caro / por que não uso o ChatGPT/Azure?"** e nenhuma peça a redefine. O `GTM-dev.md` §"contra o que se posiciona" (`POSICIONAMENTO.md` §4) **tem as alternativas**, mas não a **redefinição** | **B21** |
| B-S9 | **Mechanization** (nomear, descrever, destacar o mecanismo) | ◐ | O mecanismo *"o dado é removido antes de virar consulta"* está **nomeado e destacado** no roteiro e na landing — mas **não tem nome próprio** (o "Platformate" do Schwartz). Nomear é barato e poderoso | **B22** |
| B-S10 | **Concentration** (destruir alternativas; nunca atacar sem trazer solução) | ✘ | O `POSICIONAMENTO.md` §4 responde às alternativas, mas nenhuma peça **as destrói** para o prospect. A regra "nunca atacar sem a solução" precisa ser escrita | **B23** |
| B-S11 | **Camouflage** (emprestar credibilidade do veículo/formato) | ◐ | A isca está escrita **como opinião técnica**, não como venda (notas de execução do `post-isca`) — o que é Camouflage de formato. Não há decisão de **onde publicar** | **B07** (junto de A-G7) |
| B-S12 | **Verification** (prova: lugar importa tanto quanto conteúdo) | ✔ | `CASE-CTNI.md` §3 lista as provas verificáveis; `TVE-E1-E11.md` traduz E1–E11 | — |
| B-S13 | **Reinforcement** (2 claims trabalharem como 4) | ✔ | Aplicado no roteiro v2 (2B mecanismo × 3.1 operação) | — |
| B-S14 | **Momentum / Mood** (frases de momentum, teasers) | ◐ | Aplicado no roteiro v2 (o anexo bloco-por-bloco menciona), não sistematizado para as demais peças | **B18** |

---

## 4. Anexo C — *Ogilvy on Advertising*: como escrever

| # | Estratégia | Veredito | Estado hoje / o que falta | Tarefa |
|---|---|---|---|---|
| C-O1 | **Faça o dever de casa** (estude produto, concorrente, consumidor) | ◐ | O produto e o concorrente estão estudados (`POSICIONAMENTO.md` §1 e §4). **O consumidor não**: não houve uma conversa com comprador. O `SONDAGEM-MERCADO` é dado de mercado, não de cliente | **B24** |
| C-O2 | **Posicionamento = "o que o produto faz, e para quem é"** | ✔ | `POSICIONAMENTO.md` §2 tem a frase central e o ICP | — |
| C-O3 | **Brand image** (personalidade, consistência ano a ano) | ✔ | A narrativa da pinha (fruto que guarda a semente) + "Ping Hai empresa / Pinha produto" está decidida e registrada | — |
| C-O4 | **A Grande Ideia** (teste das 5 perguntas; "30 anos") | ◐ | Existe a metáfora da pinha (grande ideia de marca), mas ela **não passa pelo teste das 5 perguntas** formalmente — e a claim "IA privada na sua infra" reprova em "é única?" | **B25** |
| C-O5 | **O produto é o herói** / doutrina do **"positively good"** | ◐ | A Pinha é um **produto de paridade** (Azure/AWS dizem o mesmo) — é exatamente o caso da doutrina. Não há peça escrita com "positively good" em vez de "superior" | **B25** |
| C-O6 | **Repita os vencedores** (radar varrendo) | ✘ | Sem cadência, não há repetição. Depende de A-G7 | **B07** |
| C-O7 | **Abaixo os comitês** | ✔ | Decisão de uma pessoa (o fundador) — é o oposto de comitê | — |
| C-O8 | **Olhe a resposta direta** (long copy, 2 min, tarde) + **o que testar** | ◐ | O diagnóstico é **instrumentado** (resposta direta de fato). Mas o **material de outreach e a isca não testam variáveis** (headline, oferta, formato) | **B04** |
| C-O9 | **Criatividade ≠ originalidade** ("se não vende, não é criativo") | ✔ | Alinhado com a regra anti-over-claim da Pinha (`POSICIONAMENTO.md` §6) | — |
| C-O10 | **Copy longa, factual, específica** | ◐ | `CASE-CTNI.md` e `OWUI-PRODUTO.md` são longos e factuais. **A landing e o post usam copy curta** — para um comprador técnico (CTO), Ogilvy recomenda a longa | **B26** |
| C-O11 | **Regras de headline** (marca visível, news, benefício) | ✘ | Não há checklist de headline para as peças da Pinha | **B18** |

---

## 5. Anexo D — *The Wizard of Ads* (Williams): por que gruda

| # | Estratégia | Veredito | Estado hoje / o que falta | Tarefa |
|---|---|---|---|---|
| D-W1 | ***"It's not who you reach, it's what you say"*** | ✔ | É a tese que a Pinha já adota: o ICP é estreito e a mensagem é o diferencial | — |
| D-W2 | **A mente desconta o previsível** (não soar como anúncio) | ✔ | A isca é escrita como opinião, o site é editorial | — |
| D-W3 | **Velcro da mente** (loops aleatórios, não arrumadinhos) | ◐ | Aplicado em peça (a isca tem "profundidade" não-padrão), não é princípio escrito no guia de copy | **B27** |
| D-W4 | **O "you"** (a palavra mais poderosa; participante, não espectador) | ◐ | A landing recente fala do *sistema* ("o portal devolve 503") mais que do *leitor*. O "you" está fraco | **B28** |
| D-W5 | **Home Movies** (nunca aponte a câmera para você) | ◐ | O roteiro do CTNI respeita; a landing abre pelo mecanismo do sistema | **B28** |
| D-W6 | **". . . which means . . ."** (feature → benefício) | ✘ | Não há guia para converter as features técnicas (pgvector, fail-closed) em benefício de negócio | **B29** |
| D-W7 | **Fechar as brechas do próprio anúncio** (pensamento do cliente entre parênteses) | ✘ | Técnica **extremamente** aplicável — a Pinha tem um CTO cético como leitor. Nenhuma peça passou por esse teste | **B30** |
| D-W8 | **A clareza que custa insulto** | ◐ | A Pinha é franca ("nem o admin lê o chat"), mas evita o desconforto da comparação direta | **B23** |
| D-W9 | **Walking into darkness** (descreva o que espera o cliente) | ◐ | O diagnóstico **descreve o entregável** (`DIAGNOSTICO-TEMPLATE.md`) — mas nenhuma peça pública descreve o **que acontece depois do clique** | **B31** |
| D-W10 | **Reticular activator + som > visão** (ecoica ~5 s × icônica <1 s; +29%) | ✘ | **Achado de canal forte e ignorado**: a Pinha hoje é 100% texto (site, post, mensagem). O vídeo existe no plano (roteiros) mas não há decisão de som/áudio | **B32** |
| D-W11 | **Hardwood, Hammer and Nail** (não troque o prego; afie a peça) | ✔ | É exatamente a disciplina do `COERENCIA.md` §2 — o nome/mecanismo não muda; afia-se a peça | — |
| D-W12 | **Os 12 erros** — em especial: **#2 (alcançar mais sem repetição)**, **#4 (claims sem substância)**, **#6 (anúncios em vez de campanha)**, **#10 (marketing de evento)** | ◐ | A Pinha cai no **#2** (sem repetição) e no **#6** (peças isoladas, não campanha). O **#10** é um alerta direto contra tratar as duas peças como eventos | **B33** |

---

## 6. As 12 estratégias que a doutrina diz que a Pinha **deveria** estar fazendo e não faz

Ordenadas por **peso de consequência** — não por esforço. São o resumo executivo
da tabela inteira.

| # | Estratégia | Fonte | Por que importa agora | Tarefa |
|---|---|---|---|---|
| 1 | **Publicar com cadência** (a mesma coisa, repetida até cravar) | Williams C4/D-W12#2 · Ogilvy C-O6 | A Pinha tem as peças e **não publica**. Sem repetição não existe memória — e sem memória não existe marca | **B07** |
| 2 | **Falar com um comprador real** | Ogilvy C-O1 · Hormozi A-G13 | Zero conversas. Todo o posicionamento é hipótese não testada | **B24** |
| 3 | **Fixar o estágio de Awareness/Sophistication** | Schwartz B-S2/B-S3 | Decide o que dizer em toda peça futura. Hoje existe na prática em 2 peças e em nenhum documento | **B01, B02** |
| 4 | **Redefinir a objeção "é caro / por que não o Azure?"** | Schwartz B-S8 | É a objeção que mata a venda, e não há resposta escrita | **B21** |
| 5 | **Nomear o mecanismo** | Schwartz B-S9 | Nomear é barato e poderoso; o mecanismo está descrito mas é anônimo | **B22** |
| 6 | **Pedir indicação ao cliente-âncora** | Hormozi A-G13 | O ativo mais subutilizado: um cliente em produção feliz e nenhuma indicação pedida | **B13** |
| 7 | **Lista de warm outreach + cadência** | Hormozi A-G6 | O canal mais rápido e barato, e o único que não depende de audiência | **B06** |
| 8 | **Lista fria + mensagem fria + volume** | Hormozi A-G8 | O `GTM-dev.md` previu o canal e nunca o executou | **B08** |
| 9 | **Fechar as brechas do anúncio** (o CTO cético entre parênteses) | Williams D-W7 | O leitor da Pinha é cético por profissão; cada brecha aberta é uma objeção | **B30** |
| 10 | **Múltiplos formatos do lead magnet** | Hormozi A-G3 | O diagnóstico é um relatório só; 2–4× mais alcance pelo mesmo trabalho | **B04** |
| 11 | **Som/áudio** (reticular activator) | Williams D-W10 | O único canal que gruda de verdade está parado — os vídeos estão roteirizados e não gravados | **B32** |
| 12 | **Escassez real** ("uma pessoa operando") | Hormozi A-G4 | A Pinha tem escassez verdadeira e não a usa | **B05** |

---

## Referências

- Catálogos-fonte (com texto puro): `/tmp/pinha-books/{leads,schwartz,ogilvy,wizard}/`
- Backlog de execução: [`BACKLOG-GTM.md`](BACKLOG-GTM.md)
- Posicionamento e mensagem: [`POSICIONAMENTO.md`](POSICIONAMENTO.md)
- Oferta, preço e canais: [`GTM-dev.md`](GTM-dev.md), [`DIAGNOSTICO.md`](DIAGNOSTICO.md)
- Coerência tese × entrega × marca: [`COERENCIA.md`](COERENCIA.md)
- O que foi entregue: [`CASE-CTNI.md`](CASE-CTNI.md), [`OWUI-PRODUTO.md`](OWUI-PRODUTO.md)
- Peças vivas: [`apresentacao/ROTEIRO-VIDEO-CANAL.md`](apresentacao/ROTEIRO-VIDEO-CANAL.md), [`campo/post-isca-custo-llm.md`](campo/post-isca-custo-llm.md), [`campo/mensagem-laudezir.md`](campo/mensagem-laudezir.md)
