# Projeto MoveFit — Cronograma

**Referências:** Aula 08 — Cronograma
**Dependências:** Roadmap (05); Backlog; Premissas e Restrições

> **Atenção:** as datas abaixo são uma **proposta**. A capacidade semanal real da equipe vem do handoff, que não estava nos arquivos do grupo. Conferir antes de entregar.

## 1. Janela do projeto

| Referência | Data |
|---|---|
| Kick-off | quinta, 26/11/2026 |
| Piloto da Unidade Centro | segunda, 08/03/2027 |
| Operação assistida (5 dias úteis) | 08/03 a 12/03/2027 |
| Encerramento contratual (120 dias corridos) | 26/03/2027 |

**Calendário.** 25/12 e 01/01 são feriados. Carnaval cai em 08 e 09/02/2027. **26/03/2027 é Sexta-feira Santa (feriado nacional).** O aceite final deve ser feito até **25/03/2027**. Confirmar essas datas no calendário oficial.

## 2. Marcos

| Marco | Data | Critério |
|---|---|---|
| M1 — Kick-off e baseline aprovada | 26/11/2026 | Ata com aprovação de Henrique; ponto focal formalizado |
| M2 — E1 homologada | 28/12/2026 | Aceite de Juliana |
| M3 — E2 homologada | 05/02/2027 | Aceite de Juliana e Fernanda (financeiro) |
| M4 — E3 homologada | 26/02/2027 | Aceite de Juliana e Patrícia (agenda) |
| M5 — E4 homologada e Go/No-Go | 05/03/2027 | Parecer de TI, QA, implantação e negócio registrado |
| M6 — Go-live do piloto | 08/03/2027 | Unidade Centro operando no MoveFit |
| M7 — Fim da operação assistida | 12/03/2027 | Registro de incidentes e aceite de Thiago |
| M8 — Aceite final e transição | 25/03/2027 | Aceite de Henrique |

## 3. Atividades

| ID | Atividade | Itens | Início | Fim | Responsável |
|---|---|---|---|---|---|
| **Iniciação** | | | | | |
| C-01 | Kick-off e aprovação da baseline | — | 26/11 | 26/11 | Camila, Henrique |
| C-02 | Confirmar ponto focal, usuários-chave e contatos dos fornecedores | — | 26/11 | 04/12 | Camila, Juliana |
| C-03 | Pedir credenciais Pagar.me, modelo da catraca, layout de migração e identidade visual | — | 26/11 | 04/12 | Lucas, Marina |
| C-04 | Provisionar ambientes DEV e HML | ES-12 | 30/11 | 04/12 | Marina, Igor |
| **E1 — Fundação** | | | | | |
| C-05 | Descoberta e refinamento de requisitos | — | 30/11 | 11/12 | Lucas, Renata |
| C-06 | Unidades e parâmetros | PB-01 | 30/11 | 04/12 | Diego |
| C-07 | Perfis e permissões | PB-02 | 30/11 | 16/12 | Marina, Diego |
| C-08 | Cadastros e planos | PB-03, 04, 05 | 07/12 | 18/12 | Bruna, Caio |
| C-09 | Testes técnicos da E1 | — | 14/12 | 18/12 | Larissa |
| C-10 | **Homologação E1** | — | 21/12 | 28/12 | Juliana, usuários-chave |
| **E2 — Núcleo operacional e financeiro** | | | | | |
| C-11 | Matrícula | PB-06 | 21/12 | 08/01 | Diego |
| C-12 | Cobranças e saldos | PB-08 | 04/01 | 15/01 | Bruna |
| C-13 | Congelamento e cancelamento | PB-07 | 11/01 | 15/01 | Diego |
| C-14 | Integração Pagar.me | PB-09 | 11/01 | 29/01 | Bruna, Marina |
| C-15 | Auditoria | PB-27 | 18/01 | 29/01 | Caio |
| C-16 | Dashboard de inadimplência | PB-10 | 25/01 | 29/01 | Caio |
| C-17 | Testes técnicos da E2 | — | 25/01 | 29/01 | Larissa |
| C-18 | **Homologação E2** | — | 01/02 | 05/02 | Juliana, Fernanda |
| **E3 — Agenda, reservas e portal** | | | | | |
| C-19 | Grade, professor e capacidade | PB-12 | 04/01 | 22/01 | Caio |
| C-20 | Consulta, reserva, cancelamento e participantes | PB-13, 14, 15, 16 | 18/01 | 05/02 | Caio, Igor |
| C-21 | Autenticação e dados do portal | PB-17, 18 | 25/01 | 05/02 | Igor, Renata |
| C-22 | Agenda e reservas no portal | PB-19 | 01/02 | 19/02 | Igor, Renata |
| C-23 | Testes técnicos da E3 | — | 15/02 | 19/02 | Larissa |
| C-24 | **Homologação E3** | — | 22/02 | 26/02 | Juliana, Patrícia |
| **E4 — Prontidão do piloto** | | | | | |
| C-25 | Migração: carga de validação 1 | PB-11 | 08/02 | 12/02 | Diego, Paulo |
| C-26 | Migração: carga de validação 2 | PB-11 | 22/02 | 24/02 | Diego, Paulo |
| C-27 | Validação da situação do aluno | PB-20 | 08/02 | 19/02 | Bruna |
| C-28 | Integração com a catraca da Unidade Centro | PB-21 | 15/02 | 26/02 | Marina, Bruna |
| C-29 | Avaliação física e evolução | PB-22, 23 | 01/02 | 26/02 | Igor, Renata |
| C-30 | Painel gerencial | PB-25 | 15/02 | 26/02 | Caio |
| C-31 | Histórico no portal e e-mails (se couber) | PB-24, 26 | 22/02 | 03/03 | Igor, Caio |
| C-32 | Treinamento remoto (4 sessões de 2 h) | PB-28 | 23/02 | 03/03 | Paulo |
| C-33 | Checklist, contingência e ensaio de rollback | PB-29 | 22/02 | 03/03 | Paulo, Larissa |
| C-34 | **Homologação E4** | — | 01/03 | 05/03 | Juliana, Thiago, Carla |
| C-35 | **Go/No-Go do piloto** | — | 05/03 | 05/03 | Juliana, Camila |
| C-36 | Carga final de migração e cutover (fim de semana) | PB-11 | 06/03 | 07/03 | Diego, Paulo |
| **Piloto e encerramento** | | | | | |
| C-37 | **Go-live e operação assistida** | PB-29 | 08/03 | 12/03 | Paulo, Larissa, EQT |
| C-38 | Lições aprendidas do piloto | PB-30 | 15/03 | 17/03 | Camila, Lucas |
| C-39 | Plano de expansão das demais unidades | PB-30 | 15/03 | 25/03 | Camila, Marina |
| C-40 | Catracas das demais unidades (condicional) | PB-31 | 15/03 | 25/03 | Marina |
| C-41 | Aceite final e transição | — | 22/03 | 25/03 | Camila, Henrique |
| **Contínuas** | | | | | |
| C-42 | Status semanal com Juliana; quinzenal com Henrique | — | 26/11 | 25/03 | Camila |
| C-43 | Reunião técnica com Marcelo (semanal em integrações) | — | 26/11 | 25/03 | Marina |

## 4. Prazos que dependem do cliente

| O que | Prazo | Atividade que bloqueia | Premissa |
|---|---|---|---|
| Ponto focal e usuários-chave | 04/12/2026 | C-05 | PR-01, PR-02 |
| Identidade visual do Marketing | 11/01/2027 | C-21, C-22 | PR-10 |
| Credenciais sandbox do Pagar.me | 04/01/2027 | C-14 | PR-04 |
| Modelo, versão e acesso da catraca | 29/01/2027 | C-28 | PR-05 |
| Layout de migração aprovado e dados entregues | 29/01/2027 | C-25 | PR-06 |
| Janela de rede e conectividade na Unidade Centro | 12/02/2027 | C-28, C-36 | PR-07 |
| Homologações em até 5 dias úteis | por entrega | C-10, 18, 24, 34 | PR-03 |

## 5. Caminho crítico

Perfis (C-07) → Matrícula (C-11) → Cobranças (C-12) → Migração (C-25, C-26) → Homologação E4 (C-34) → Go/No-Go (C-35) → Cutover (C-36) → Go-live (C-37).

**Folga do piloto: zero.** A homologação da E4 termina em 05/03 e a carga final acontece em 06/03. Qualquer atraso em C-28 (catraca) ou C-25 (dados do cliente) empurra o piloto, que é uma data contratual.

## 6. Verificação pedida na Integração

| Pergunta | Resposta |
|---|---|
| Todos os itens comprometidos têm atividade? | Sim: PB-01 a PB-30 estão entre C-06 e C-39. PB-31 a PB-34 são condicionais. |
| As dependências do Backlog foram respeitadas? | Sim. Ex.: PB-14 depende de PB-06 e PB-13; PB-21 depende de PB-20. |
| Cada módulo cabe na entrega do Roadmap? | A E4 está no limite (ver Custos e R-15). |
| A capacidade semanal é suficiente? | A confirmar com o handoff. Em média são cerca de 108 h por semana (ver Custos). |
| Homologação, integração, migração e treinamento têm tempo? | Sim, mas com folga zero na virada para o piloto. |
| Piloto e encerramento continuam viáveis? | Sim, desde que as dependências do cliente cheguem nos prazos da seção 4. |

## 7. Se o trabalho não couber

Não basta mover datas. A ordem de resposta é: (1) tirar PB-24 e PB-26 da E4; (2) rever o Roadmap e os riscos; (3) se ainda não couber, abrir solicitação de mudança com Henrique.
