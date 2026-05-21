# Playbook Comercial — Imersão ExponencIA

> Scripts, objeções, abordagens e argumentos extraídos do Playbook ExponencIA.

---

## ABORDAGEM CONSULTIVA — Script de Abertura (Outbound)

**Princípio:** nunca abrir com pitch. Abrir com uma pergunta sobre o cenário de IA da empresa.

```
"Oi [Nome], tudo bem?
Estou mapeando com alguns líderes de software houses como eles estão
estruturando a IA na operação. Posso tirar uma dúvida rápida?"
```

**Quando ele responder:**
```
"[Nome], estou conversando com líderes de software house sobre
produtividade no desenvolvimento com IA.

Hoje na empresa de vocês já existe alguma iniciativa de usar IA
além de geração de código?"
```

**Resposta mais comum:** "Usamos só para auxiliar o desenvolvimento / só o ChatGPT / só o Copilot"

**Resposta certa:**
```
"Perfeito! 95% do mercado está exatamente nessa fase — usando a IA como
um Copilot de código.

O próximo passo das software houses agora é plugar a IA agêntica no
background para rodar testes (QA) e documentar o sistema de forma autônoma.

A grande virada é transformar a IA em um membro da equipe de dev.
Posso te enviar um PDF com um resumo de como estruturar essa esteira?"
```

---

## ARGUMENTOS CENTRAIS (usar em qualquer etapa)

**Argumento 1 — O mercado está mudando agora:**
> "Enquanto algumas software houses usam IA como chat… outras já estão usando como DEV. Essa diferença vai definir quem cresce e quem fica para trás em 2026."

**Argumento 2 — O backlog:**
> "A maior maldição das software houses é o backlog infinito. Funcionalidade atrasada, cliente cobrando, time sobrecarregado. A IA agêntica resolve exatamente isso — não como ferramenta de apoio, como membro autônomo do time."

**Argumento 3 — Caso real do Thulio:**
> "A IA está usando o software sozinha, mapeando todas as telas, entrando menu por menu, tela por tela, botão por botão — para montar o plano de migração ela já está sozinha fazendo isso."

**Argumento 4 — Urgência 2026:**
> "Quem não implementar IA agêntica agora estará fora do jogo no ano que vem. Não é tendência — já está acontecendo nas SH que saíram na frente."

**Argumento 5 — Combo dono + líder técnico:**
> "O ideal é você focar na estratégia de negócio e seu líder técnico focar na implementação prática. Por isso temos um combo especial para 2 inscrições."

---

## PERGUNTAS DE QUALIFICAÇÃO (SPIN adaptado para IA)

### S — Situação
```
"Hoje vocês usam alguma ferramenta de IA no processo de desenvolvimento?"
"Qual linguagem / stack vocês trabalham principalmente?"
"Quantos devs vocês têm no time?"
"Como está estruturado o processo de QA e documentação hoje?"
"Vocês têm backlog acumulado? Como é a situação hoje?"
```

### P — Problema
```
"Qual é a maior dificuldade do time de dev hoje — prazo, bugs, documentação?"
"O time consegue entregar no ritmo que os clientes precisam?"
"A documentação do sistema está em dia ou é um ponto crítico?"
"Já perdeu cliente ou teve problema por atraso em funcionalidade?"
"Como é a rotatividade do time? Quando sai alguém, quanto conhecimento vai junto?"
```

### I — Implicação
```
"Se o backlog continuar crescendo nesse ritmo, o que acontece com os clientes?"
"Se a concorrência de vocês implementar IA agêntica antes, como isso impacta o mercado que vocês atendem?"
"Quanto tempo do dev sênior é gasto em tarefas que poderiam ser automatizadas?"
"O que significaria perder um dev sênior hoje — quanto tempo para repor esse conhecimento?"
```

### N — Necessidade
```
"Se seu time entregasse 2x mais rápido sem contratar ninguém novo, como isso mudaria o negócio?"
"Se a documentação fosse automática, quanto tempo o time recuperaria por semana?"
"Imagina sair da imersão com um protótipo de IA já funcionando integrado ao processo de vocês — o que isso significaria?"
```

---

## OBJEÇÕES — Scripts Completos

### "JÁ USO IA" (ChatGPT / Copilot)
```
"Entendo que você já usa o ChatGPT ou Copilot, [Nome].
Mas a dor que vejo nos donos de SH é que isso resolve só 5% do problema.
O dev continua sobrecarregado, o backlog continua crescendo.

O próximo nível não é usar IA para gerar código —
é ter a IA rodando QA, documentação e code review de forma autônoma,
enquanto seus devs focam no que realmente importa.

Isso é o que chamamos de IA agêntica — e é exatamente o que a imersão ensina."
```

### "JÁ USO CLAUDE CODE / JÁ CRIO MEUS PRÓPRIOS AGENTES" (perfil técnico avançado)

**Contexto:** Lead está além do ChatGPT — cria agentes de IA ativamente com Claude Code. É o perfil mais sofisticado e o que mais comete erros estruturais sem perceber. Tratar como oportunidade de alto valor, nunca como descarte.

**Diagnóstico do mentor (usar como autoridade técnica):**
> "O erro crônico nessa fase é negligenciar o Harness de execução — tratando o agente como gerador de sintaxe em vez de operador autônomo. E ignorar a Engenharia de Contexto profunda, sofrendo com 'poluição de tokens'. O resultado: a IA alucina, perde o foco na arquitetura e o dev continua sendo um digitador de código — só que agora um digitador mais caro e menos eficiente."

**Os dois erros crônicos:**
1. **Harness de Execução ausente** — sem malha de testes e feedback loops, o agente não se autocorrige via logs de erro. O dev vira gargalo humano validando manualmente o que deveria ser ciclo fechado (Extreme Programming 2.0).
2. **Engenharia de Contexto ignorada** — RAG sem curadoria cirúrgica injeta ruído e dependências obsoletas. A "poluição de tokens" faz a IA alucinar e gerar boilerplate inútil no lugar de arquitetura de receita real.

```
"Que ótimo — você já está no grupo dos 5% que foi além do Copilot de código.
Me conta uma coisa: quando você cria esses agentes com Claude Code,
como está estruturado o harness de execução deles?

[Aguardar — se resposta vaga ou "que harness?"]

'Esse é exatamente o ponto.

O erro mais crônico de quem está nessa fase é tratar o agente
como gerador de sintaxe em vez de operador autônomo.
Sem uma malha de testes e feedback loops que permita à IA
rodar o runtime e se autocorrigir via logs de erro —
o dev continua sendo o gargalo humano da operação.

O segundo erro é a Engenharia de Contexto. Sem curadoria cirúrgica
na janela de contexto, você injeta ruído e dependências obsoletas —
a IA começa a alucinar e gera boilerplate inútil no lugar de arquitetura real.

Quem ensina isso na imersão define assim:
"O dev que não domina o manejo do contexto e a infraestrutura de validação
do agente continua sendo um digitador de código —
só que agora um digitador mais caro e menos eficiente."

Você já tem a base. A imersão é o salto de dev que usa IA
para arquiteto de sistemas autônomos reais.'"
```

**Cases para solidificar:**
- *Eduardo — Microrib (SP):* *"Usava até multiagentes, mas sem roles, hooks e guardrails — era como sentar do lado da IA o dia todo. Dois dias mudaram completamente."*
- *Rogério — GR7 (SP):* *"Estava usando só o CLAUDE.md, ignorando toda a estrutura. Abriu muito a visão."*
- *Colaborador — imersão anterior:* *"Implementei harness durante a imersão — subagentes, QA agent, hooks — tudo funcionando. Saí com framework para levar pro time inteiro."*

### "NÃO TENHO TEMPO PARA IR A SP"
```
"Exatamente por não ter tempo que você precisa ir.

Você está preso no operacional porque seu processo de dev é manual.
A IA agêntica vai te devolver esse tempo — mas só funciona quando implementada certo.

Dois dias agora podem economizar meses de retrabalho, contratação e atraso.
E você sai com o protótipo funcionando — não teoria pra aplicar depois."
```

### "MINHA LINGUAGEM É ANTIGA / ESPECÍFICA"
```
"Melhor ainda.

Vamos analisar o seu cenário atual e aplicar a IA dentro da linguagem
que você já usa — criando automação onde hoje você depende de braço humano.

E tem mais: a IA já está mapeando sistemas desktop para planejar
a migração para web automaticamente. Independente da stack."
```

### "POSSO APRENDER ISSO NO YOUTUBE"
```
"No YouTube você vê ferramenta.
Na Imersão você vê implementação e orquestração completa.

A diferença: você vai levar o notebook e construir o protótipo lá com a gente.
Você não sai com teoria — sai com um sistema integrado funcionando,
pronto para rodar na sua software house."
```

### "ESTÁ CARO / R$ 1.497 É MUITO"
```
"Deixa eu te ajudar a pensar nisso.

Quanto custa um dev sênior por mês para a sua empresa?
[Aguardar resposta]

A imersão custa menos do que um mês de salário desse dev.
E o que você aprende lá pode fazer esse dev entregar o dobro — sem contratar ninguém novo.

O custo real é continuar com o backlog crescendo e o time sobrecarregado."
```

### "PRECISO FALAR COM MEU SÓCIO / LIDER TÉCNICO"
```
"Faz todo sentido — na verdade, o ideal é exatamente isso.

Recomendamos que o dono venha para a estratégia de negócio
e o líder técnico venha para a implementação prática.
Temos um combo especial para 2 inscrições.

O que acha de você e seu líder técnico virem juntos?
Assim saem alinhados e com o protótipo funcionando no final."
```

### "NÃO SEI SE É PARA MIM / MINHA EMPRESA É PEQUENA"
```
"Essa é exatamente a empresa que mais se beneficia.

Quando você tem um time pequeno, cada hora do dev é mais preciosa.
Se a IA faz QA, documentação e code review — seu time pequeno entrega
como um time grande.

E o investimento de R$ 1.497 se paga com a primeira funcionalidade
que a IA entregar no lugar de um dev sobrecarregado."
```

---

## CHECKLIST — O que o time comercial deve verificar

- [ ] Qual a maior dificuldade do time de dev hoje (prazo, bugs, documentação)?
- [ ] Já usa alguma IA além de geração de código?
- [ ] Qual a stack/linguagem principal?
- [ ] Tem líder técnico que poderia vir junto (combo)?
- [ ] Explicou o conceito de "IA Agêntica" — o grande diferencial?
- [ ] Reforçou que o Roadmap é para 2026 — quem não implementar agora fica fora?
- [ ] Deixou claro que não é curso — sai com protótipo funcionando?

---

## COPY PARA MENSAGEM ESCRITA (WhatsApp / DM)

**Abertura consultiva:**
```
"Oi [Nome]! Estou mapeando como líderes de software house estão
estruturando a IA na operação.

Não é sobre usar o ChatGPT para gerar código — é sobre ter a IA
trabalhando como membro autônomo do seu time de dev.

Posso te enviar um resumo de como funciona isso na prática?"
```

**Copy de impacto (para leads que já demonstraram interesse):**
```
"Não adianta ter o melhor time de dev do mundo se o backlog nunca
acaba e a documentação está sempre atrasada.

Enquanto algumas software houses usam IA como chat…
outras já estão usando como DEV.

Essa diferença vai definir quem cresce em 2026."
```

---

## GATILHOS DE URGÊNCIA E ESCASSEZ

- **Vagas limitadas:** 35 por turma — perfil da SH validado antes de confirmar — não é um congresso de 200 pessoas
- **Turma 1:** 28 e 29 de Maio de 2026 | **Turma 2:** 30 e 31 de Maio de 2026
- **Janela competitiva:** "Quem não implementar IA agêntica em 2026 estará correndo atrás dos que já implementaram"
- **Combo:** "O desconto do combo é válido até [data limite]"

---

## TRANSIÇÃO PARA APRESENTAÇÃO

```
"[Nome], pelo que você me contou — backlog crescendo, time sobrecarregado,
usando IA só para código — vocês estão exatamente no ponto onde a IA agêntica
faz mais diferença.

Faz sentido eu te mostrar como os 3 pilares da imersão resolvem
cada um desses pontos na prática?"
```

---

## FOLLOW-UP ESTRATIFICADO E FUNIL DE RECUPERAÇÃO

### Temperatura da Lista — Definir SEMPRE antes de estruturar qualquer cadência

🔵 **FRIO** — nunca ligou, primeira tentativa, nunca respondeu nada
- Canal: Ligação + WhatsApp | Frequência: 1x/semana | Meta: Qualificar

🟡 **MORNO** — ligou 1-2x, já conversou mas não confirmou interesse
- Canal: WhatsApp com conteúdo + Ligação | Frequência: 2-3x/semana | Meta: Despertar interesse

🔴 **QUENTE** — combinou retorno mas não seguiu / está em negociação ativa
- Canal: Ligação + WhatsApp diário | Frequência: Diária | Meta: Converter
- **Limite:** 5-8 dias sem resposta → acionar ultimato e despedida obrigatoriamente

---

### Inteligência do Lead — Personalização Obrigatória

Antes de qualquer follow-up, usar tudo que foi coletado:
- Usa IA? Qual? Nível de maturidade (ChatGPT / Copilot / Claude Code / cria agentes)?
- Maior desafio citado (backlog, QA, doc, dev sobrecarregado, etc.)
- Dores e desejos expressos durante a conversa
- Detalhes específicos mencionados (nome de dev, cliente, concorrente, linguagem, stack)
- Objeções levantadas e como foram tratadas

> **Regra de ouro:** cada mensagem de follow-up deve referenciar algo que *aquele* lead disse. Isso é o que separa follow-up que converte de spam.

---

### 5 Elementos da Cadência (definir os 5 antes de começar)

1. **Tentativas** — quantos toques no fluxo total
2. **Canal** — WhatsApp, ligação, e-mail (variar entre os toques)
3. **Duração** — janela total do fluxo (ex: 21 dias)
4. **Espaçamento** — intervalo entre cada toque (conforme temperatura)
5. **Conteúdo** — tipo diferente em cada toque (nunca repetir o mesmo)

---

### 8 Tipos de Conteúdo para Follow-ups

**1. Consultivo + dor** — "Você ainda tem interesse em [benefício central] por meio da Imersão ExponencIA?"
**2. Prova social** — case de cliente com a mesma dor, preferencialmente empresa similar
**3. Vídeo educativo** — pautado no problema que a imersão resolve
**4. Conteúdo de dor** — artigo, podcast ou material alinhado à dor específica, sem mencionar o produto
**5. Questionário interativo** — pergunta de 0-10 ou escolha binária que reabre a conversa
**6. Notícias e tendências de mercado** — urgência competitiva com dados externos
**7. Pessoalidade** — aniversário, conquistas, momentos especiais do time
**8. Ultimato e despedida** — pedir o "não" com sinceridade (libera agenda e frequentemente reativa)

---

### Funil de Recuperação (leads frios / bases antigas)

Princípio: **não vender — agregar valor** até o lead voltar ao funil ativo.

1. Segmentar por histórico: o que foi conversado, qual dor foi citada, qual objeção surgiu
2. Mandar conteúdo alinhado especificamente àquela dor (artigo, case, podcast)
3. Campanhas de reativação com estímulo **diferente** do que foi usado antes — nova oferta, novo ângulo
4. Só voltar ao pitch depois que o lead demonstrar engajamento
