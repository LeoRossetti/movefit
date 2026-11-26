# Decisões da Pessoa 2 — para defender no kick-off

Cada item tem a decisão, o motivo, a fonte e uma resposta curta caso alguém pergunte. Cobre os arquivos 05 a 08.

> **Atenção:** a seção de custos usa números **internos da WEBFLOW** (valor-hora, teto, margem). Pode ser usada na apresentação da escola, mas não deve ser mostrada a um cliente real.

**Regra de ouro para responder:** os números de custo vêm do Bloco E do handoff. As datas das atividades são **propostas nossas**, ancoradas nos marcos comerciais do Bloco F. O que é suposição está listado na seção 9.

## 1. Datas e entregas

**Decisão:** as entregas seguem os marcos comerciais vendidos: 1ª entrega em 22/01, 2ª em 19/02, preparação do piloto de 22/02 a 05/03, piloto em 08/03 e encerramento até 26/03.
**Motivo:** são os marcos que o cliente já viu na proposta. Mudá-los exigiria renegociação.
**Fonte:** Bloco F do handoff (cronograma comercial).
**Se perguntarem:** "Por que não antecipar o piloto?" → O cliente pediu que o piloto rode depois do pico de janeiro e fevereiro (notas da negociação, 17/09).

## 2. Aceite final em 25/03, e não em 26/03

**Decisão:** o aceite final é planejado para 25/03/2027.
**Motivo:** 26/03/2027 parece ser Sexta-feira Santa, feriado nacional (a confirmar no calendário oficial; essa informação não vem do kit). A OS fixa o término em 26/03.
**Se perguntarem:** "E se for dia útil?" → Nada muda, só ganhamos um dia de folga.

## 3. Divergência entre 16 semanas e 120 dias

**Decisão:** registrar a divergência e decidir a data de encerramento no kick-off (risco R-22).
**Motivo:** a proposta comercial fala em 16 semanas (18/03/2027) e a OS em 120 dias corridos (26/03/2027). O handoff manda não presumir a interpretação sem validação formal.
**Fonte:** Blocos B e D; pontos para validação do GP.
**Se perguntarem:** "Qual vale?" → O contrato assinado é a OS (120 dias), mas queremos a confirmação do cliente por escrito.

## 4. Homologação da 2ª entrega dividida em duas partes

**Decisão:** parte 1 (agenda, reservas e avaliação) entregue em 05/02 e homologada até 16/02; parte 2 (portal, Pagar.me e inadimplência) entregue em 19/02 e homologada até 26/02. O marco comercial continua sendo 19/02.
**Motivo:** sem a divisão, toda a homologação da 2ª entrega cairia em 22 a 26/02, junto com o fim da preparação do piloto, e os mesmos usuários-chave estariam sobrecarregados no pico de janeiro e fevereiro (Bloco F: pico de matrículas em janeiro e fevereiro).
**Riscos que reduz:** R-02, R-03 e R-15.
**Ponto fraco a admitir:** a homologação da parte 1 cai na semana do Carnaval (08 e 09/02, também fora do kit), então os 5 dias úteis terminam em 16/02.

## 5. Catraca começando em janeiro

**Decisão:** começar a prova de conceito da integração com a catraca do Centro em 18/01, e não em fevereiro.
**Motivo:** o Centro já foi informado como Control iD iDBlock (Bloco G, pendência P-01 com situação "parcial"). Começar cedo tira a integração do caminho crítico final.
**Condição:** o cliente confirma modelo e versão até 08/01 (prazo proposto por nós).
**Se perguntarem:** "E se o modelo não for confirmado?" → Contingência: acesso manual na recepção no piloto (risco R-05).

## 6. Migração: amostra em dezembro e primeira carga em janeiro

**Decisão:** pedir a amostra da base até 18/12, analisar em janeiro, aprovar o layout até 22/01 e rodar a carga de validação 1 em 25 a 29/01. A carga 2 fica em 15 a 17/02.
**Motivo:** as bases do cliente são distribuídas e têm campos não padronizados (Bloco G). Descobrir problemas cedo deixa tempo para o cliente corrigir; a WEBFLOW não faz saneamento manual (exclusão do escopo).
**Limite:** a proposta técnica prevê no máximo duas cargas de validação e uma final.

## 7. Arquitetura e ambientes fechados em dezembro

**Decisão:** concentrar em dezembro as decisões de arquitetura e a automação da implantação.
**Motivo:** a Marina tem 6 h/semana e o Igor 4 h/semana (Bloco E). Se as decisões ficassem para janeiro e fevereiro, os dois virariam gargalo de Pagar.me, catraca e cutover (risco R-21).

## 8. O custo não fecha, e o plano não esconde isso

**Fato:** com os valores-hora e as 1.840 horas do handoff, o custo estimado é de cerca de **R$ 207,6 mil**. O teto é R$ 168.000 e a meta é R$ 156.000.
**Como foi calculado (só com dados do kit):** o custo da equipe por semana é R$ 16.700 para 148 h, ou seja R$ 112,84 por hora em média. Multiplicado por 1.840 h dá R$ 207.622. A única suposição é que as horas se dividem na proporção da disponibilidade de cada pessoa (PP-02), porque o kit não divide as horas.
**Três contas que sustentam isso:**
- A menor tarifa da equipe é R$ 85/h. Mesmo com as 1.840 h todas nessa tarifa, o custo seria R$ 156.400, acima da meta. A meta equivale a R$ 84,78/h, abaixo de qualquer tarifa.
- Para caber no teto, o projeto teria cerca de 1.489 h, ou seja 351 h a menos.
- Trocar o mix de perfis não resolve: a economia por hora trocada é de R$ 30 a R$ 40, então seriam necessárias de 990 a 1.320 h trocadas, mais da metade do projeto.
**Decisão:** não reduzir o custo no papel. Mostrar o problema e escalar. O que dá para reduzir (horas ou teto) é decisão da gestão de operações ou de mudança de escopo.
**Ação única:** antes do kick-off, a Camila pergunta à gestão se as 1.840 h e o teto são compatíveis com as tarifas e qual é o plano de alocação real. O risco R-20 fica aberto até a resposta.
**Frase para a apresentação:** "Identificamos que, com as tarifas do kit, o custo ultrapassa o teto. Não corrigimos no papel: abrimos o risco R-20 e a decisão está com a gestão." Observação: o kit diz que as horas são só referência comercial, então a conta é uma estimativa nossa, e não um erro do handoff.
**Fonte:** Bloco E do handoff.
**Se perguntarem:** "Por que não mostrou um custo dentro do teto?" → Porque os dados do kit não permitem. Um custo no papel sem base esconderia o problema, e o risco R-20 existe para ele ser tratado.

## 9. Premissas de planejamento da Pessoa 2

Estas são **suposições nossas**, separadas das premissas PR-01 a PR-10 do Escopo. Cada uma diz de onde vem, o que acontece se falhar e quando validar.

| ID | Premissa | De onde vem | Se falhar | Quando validar |
|---|---|---|---|---|
| PP-01 | O desenvolvimento pode reaproveitar componentes existentes da WEBFLOW | Uma frase do resumo comercial (Bloco A). Não quantificada | Sem redução de esforço; o gap permanece | Fase de arquitetura (dezembro), com a Marina |
| PP-02 | As 1.840 h se distribuem na proporção da disponibilidade semanal de cada pessoa | Escolha neutra: o handoff não divide as horas e diz que o mix pode ser revisto | O custo muda, mas continua acima da meta | Planejamento detalhado, com os líderes funcionais |
| PP-03 | O projeto tem 16 semanas de trabalho | Prazo da proposta comercial (Bloco B) | A capacidade total muda proporcionalmente | Decisão sobre 16 semanas ou 120 dias (risco R-22) |

**O que NÃO é suposição:** horas por frente, valor-hora, disponibilidade semanal, teto, meta, receita e parcelas. Todos vêm do Bloco E ou B.

## 10. Por que PB-24 e PB-25 não foram cortados, mas PB-26 pode ser adiado

- **PB-24** (histórico recente de avaliações no portal) está em ES-07 e na proposta técnica. **PB-25** (painel) está em ES-08. São escopo contratado: cortar exige mudança com Henrique, e adiar só muda a data, não o custo.
- **PB-26** (e-mails) não está na lista ES-01 a ES-12 do Escopo. Só aparece como integração prevista na proposta técnica. Por isso é o candidato a adiar, com aprovação da Juliana. O kit não permite dizer quantas horas isso economiza.

## 11. Perguntas prováveis, em uma linha

| Pergunta | Resposta |
|---|---|
| O piloto tem folga? | Não. A homologação termina em 05/03 e a carga final é em 06/03. Reduzimos a chance de atraso antecipando a catraca e a migração |
| O que acontece se o cliente atrasar um dado? | O prazo é reavaliado e registrado como dependência do cliente; a OS permite prorrogar por atraso do cliente |
| E se o cliente não homologar em 5 dias? | Pelo contrato (Bloco D), a WEBFLOW pode considerar o marco aceito, desde que o envio seja formal |
| Por que tantas entregas parciais? | Para validar cedo com os usuários-chave e não concentrar tudo na semana do piloto |
| A equipe dá conta em horas? | Sim: as 1.840 h usam 78% da capacidade de 16 semanas. Mas QA (102%) e implantação (141%) passam da capacidade da própria função e precisam de apoio |
| Qual o maior risco? | Custo acima do teto (R-20), seguido de usuários-chave indisponíveis (R-02), migração (R-06) e E2/E3 sem folga (R-15) |
