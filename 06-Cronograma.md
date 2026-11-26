# Projeto MoveFit — Cronograma

**Referências:** Aula 08 — Cronograma; Bloco F do handoff
**Dependências:** Roadmap (05); Backlog; Premissas e Restrições; Custos (07)
**Decisões de planejamento:** ver `11-Decisoes-Kickoff-Pessoa2.md`

## 1. Janela do projeto

| Referência | Data |
|---|---|
| Kick-off | quinta, 26/11/2026 |
| 16 semanas (proposta comercial) | 18/03/2027 |
| Piloto da Unidade Centro | segunda, 08/03/2027 |
| Operação assistida (5 dias úteis) | 08/03 a 12/03/2027 |
| 120 dias corridos (OS) e expansão/encerramento | 26/03/2027 |

**Calendário.** 25/12 e 01/01 são feriados; Carnaval cai em 08 e 09/02/2027. **26/03/2027 é Sexta-feira Santa** (confirmar no calendário oficial), então o aceite final deve ser feito até **25/03/2027**. O cliente também espera apresentar a plataforma na reunião de gestores no fim de março (Bloco A).

## 2. Marcos e faturamento

| Marco | Data | Critério | Parcela (Bloco B) |
|---|---|---|---|
| M1 — Kick-off | 26/11/2026 | Baseline aprovada por Henrique; ponto focal formalizado | Parcela 1 (20%) na assinatura da OS |
| M2 — Especificação funcional aprovada | 18/12/2026 | Aceite de Juliana | Parcela 2: R$ 57.200 (20%) |
| M3 — Ambiente de homologação disponível | 18/12/2026* | HML no ar | Parcela 3: R$ 71.500 (25%) |
| M4 — 1ª entrega em homologação | 22/01/2027 | E1 entregue; aceite até 29/01 | — |
| M5a — Entrega parcial da 2ª entrega | 05/02/2027 | Agenda, reservas e avaliação física; aceite até 16/02 | — |
| M5 — 2ª entrega em homologação | 19/02/2027 | E2 completa; aceite até 26/02 | — |
| M6 — Prontidão do piloto e Go/No-Go | 05/03/2027 | Parecer de TI, QA, implantação e negócio | — |
| M7 — Go-live do piloto | 08/03/2027 | Unidade Centro operando | — |
| M8 — Aceite do piloto | até 19/03/2027 | Fim da operação assistida (12/03) e aceite de Thiago e Juliana | Parcela 4: R$ 71.500 (25%) |
| M9 — Aceite final e encerramento | 25/03/2027 | Aceite de Henrique | Parcela 5: R$ 28.600 (10%) |

\* Confirmar com o Comercial se "disponibilização do ambiente de homologação" é o ambiente vazio ou com a 1ª entrega (22/01). Isso muda quando a parcela 3 é faturada.

## 3. Atividades

Ajustes de planejamento aplicados nesta versão estão marcados com **(ajuste)**.

| ID | Atividade | Itens | Início | Fim | Responsável |
|---|---|---|---|---|---|
| **Iniciação e descoberta** | | | | | |
| C-01 | Kick-off e aprovação da baseline | — | 26/11 | 26/11 | Camila, Henrique |
| C-02 | Formalizar ponto focal, usuários-chave (P-04) e calendário de indisponibilidade do cliente (P-07) | — | 26/11 | 04/12 | Camila, Juliana |
| C-03 | Cobrar pendências: catracas (P-01), sandbox (P-02), amostra da base (P-03), política de cancelamento (P-05), SSO (P-06), identidade visual (P-08) | — | 26/11 | 04/12 | Lucas, Marina |
| C-04 | Provisionar DEV e HML, automatizar a implantação e fechar as decisões de arquitetura (Pagar.me, catraca, segurança) **(ajuste)** | ES-12 | 30/11 | 18/12 | Igor, Marina |
| C-05 | Descoberta e especificação funcional (workshops, protótipos) | — | 26/11 | 18/12 | Lucas, Renata, Marina |
| C-05a | Analisar a amostra da base (P-03) e propor o layout de migração **(ajuste)** | PB-11 | 04/01 | 15/01 | Lucas, Diego |
| **E1 — 1ª entrega (22/01)** | | | | | |
| C-06 | Unidades e parâmetros | PB-01 | 07/12 | 11/12 | Bruna |
| C-07 | Perfis e permissões | PB-02 | 07/12 | 08/01 | Diego, Marina |
| C-08 | Cadastros e planos | PB-03, 04, 05 | 14/12 | 08/01 | Bruna, Caio |
| C-09 | Matrícula | PB-06 | 04/01 | 15/01 | Diego, Bruna |
| C-10 | Congelamento e cancelamento | PB-07 | 11/01 | 19/01 | Bruna |
| C-11 | Cobranças e saldos | PB-08 | 11/01 | 20/01 | Bruna |
| C-12 | Auditoria | PB-27 | 11/01 | 20/01 | Caio |
| C-13 | Testes técnicos da E1 | — | 18/01 | 21/01 | Larissa |
| C-14 | **Homologação E1** | — | 25/01 | 29/01 | Juliana, usuários-chave |
| **E2 — 2ª entrega (19/02), com entrega parcial em 05/02 (ajuste)** | | | | | |
| C-15 | Grade, professor e capacidade | PB-12 | 04/01 | 22/01 | Caio |
| C-16 | Consulta, reserva, cancelamento e participantes | PB-13, 14, 15, 16 | 18/01 | 05/02 | Caio, Bruna |
| C-19a | Avaliação física e evolução | PB-22, 23 | 25/01 | 05/02 | Bruna, Renata |
| C-22a | Testes técnicos da parte 1 da E2 | — | 01/02 | 05/02 | Larissa |
| C-23a | **Homologação E2, parte 1** (agenda, reservas e avaliação) | — | 08/02 | 16/02 | Juliana, Patrícia |
| C-17 | Autenticação e dados do portal | PB-17, 18 | 25/01 | 05/02 | Bruna, Renata |
| C-18 | Agenda e reservas no portal | PB-19 | 01/02 | 19/02 | Caio, Renata |
| C-19b | Histórico de avaliações no portal | PB-24 | 08/02 | 19/02 | Bruna, Renata |
| C-20 | Integração Pagar.me | PB-09 | 11/01 | 12/02 | Diego, Marina |
| C-21 | Dashboard de inadimplência | PB-10 | 08/02 | 19/02 | Bruna |
| C-22b | Testes técnicos da parte 2 da E2 | — | 15/02 | 19/02 | Larissa |
| C-23b | **Homologação E2, parte 2** (portal, Pagar.me e inadimplência) | — | 22/02 | 26/02 | Juliana, Fernanda |
| **E3 — Integrações e preparação do piloto** | | | | | |
| C-24 | Migração: carga de validação 1 (usa os dados da E1 no HML) **(ajuste)** | PB-11 | 25/01 | 29/01 | Diego, Paulo |
| C-25 | Migração: carga de validação 2 **(ajuste)** | PB-11 | 15/02 | 17/02 | Diego, Paulo |
| C-26 | Validação da situação do aluno | PB-20 | 01/02 | 12/02 | Bruna |
| C-27 | Integração com a catraca da Unidade Centro, com início antecipado **(ajuste)** | PB-21 | 18/01 | 26/02 | Diego, Marina |
| C-28 | Painel gerencial | PB-25 | 15/02 | 26/02 | Caio |
| C-29 | E-mails operacionais (candidato a adiar) | PB-26 | 22/02 | 03/03 | Bruna |
| C-30 | Treinamento remoto (4 sessões de 2 h) | PB-28 | 23/02 | 03/03 | Paulo |
| C-31 | Checklist, contingência e ensaio de rollback | PB-29 | 22/02 | 03/03 | Paulo, Larissa, Igor |
| C-32 | **Homologação E3** | — | 01/03 | 05/03 | Juliana, Thiago, Carla |
| C-33 | **Go/No-Go do piloto** | — | 05/03 | 05/03 | Juliana, Camila |
| C-34 | Carga final e cutover (fim de semana) | PB-11 | 06/03 | 07/03 | Diego, Paulo, Igor |
| **Piloto e encerramento** | | | | | |
| C-35 | **Go-live e operação assistida** | PB-29 | 08/03 | 12/03 | Paulo, Larissa, Diego |
| C-36 | Aceite do piloto | — | 15/03 | 19/03 | Thiago, Juliana |
| C-37 | Lições aprendidas do piloto | PB-30 | 15/03 | 17/03 | Camila, Lucas |
| C-38 | Plano de expansão das demais unidades | PB-30 | 15/03 | 25/03 | Camila, Marina |
| C-39 | Catracas das demais unidades (condicional) | PB-31 | 15/03 | 25/03 | Marina |
| C-40 | Aceite final e encerramento | — | 22/03 | 25/03 | Camila, Henrique |
| **Contínuas** | | | | | |
| C-41 | Status semanal com Juliana; quinzenal com Henrique | — | 26/11 | 25/03 | Camila |
| C-42 | Reunião técnica com Marcelo | — | 26/11 | 25/03 | Marina |
| C-43 | Demonstrações curtas quinzenais aos usuários-chave, para a homologação final ser só confirmação **(ajuste)** | — | 11/01 | 26/02 | Lucas, Juliana |

## 4. Prazos que dependem do cliente

| O que | Prazo | Bloqueia | Pendência / premissa |
|---|---|---|---|
| Ponto focal e usuários-chave | 04/12/2026 | C-05 | P-04, PR-01, PR-02 |
| Calendário de indisponibilidade | 04/12/2026 | Todas as homologações | P-07 |
| Amostra da base de alunos e planos | 18/12/2026 | C-05a | P-03, PR-06 |
| Política de cancelamento e congelamento | 18/12/2026 | C-10 | P-05 |
| Credenciais sandbox do Pagar.me | 04/01/2027 | C-20 | P-02, PR-04 |
| Modelo e versão da catraca do Centro | 08/01/2027 | C-27 (início em 18/01) | P-01, PR-05 |
| Identidade visual do Marketing | 11/01/2027 | C-17, C-18 | P-08, PR-10 |
| Layout de migração aprovado | 22/01/2027 | C-24 | P-03, PR-06 |
| Janela de rede e conectividade na Unidade Centro | 12/02/2027 | C-27, C-34 | PR-07 |
| Homologações em até 5 dias úteis | por entrega | C-14, 23a, 23b, 32 | PR-03 |

Pelo Bloco D, se o cliente não se manifestar em 5 dias úteis, a WEBFLOW pode considerar o marco aceito. Formalizar cada envio para essa regra valer.

## 5. Caminho crítico

Perfis (C-07) → Matrícula (C-09) → Cobranças (C-11) → Migração (C-24, C-25) → Homologação E3 (C-32) → Go/No-Go (C-33) → Cutover (C-34) → Go-live (C-35).

**Folga do piloto: zero.** A homologação da E3 termina em 05/03 e a carga final é em 06/03. A antecipação da catraca (C-27) e da migração (C-24, C-25) reduz a chance de atraso, mas não cria folga.

**Gargalos de pessoa.** Marina (6 h/semana) e Igor (4 h/semana) concentram Pagar.me, catraca, ambientes e cutover. Por isso as decisões de arquitetura e a automação dos ambientes foram para dezembro (C-04). Veja o risco R-21.

## 6. Verificação pedida na Integração

| Pergunta | Resposta |
|---|---|
| Todos os itens comprometidos têm atividade? | Sim: PB-01 a PB-30 estão entre C-05a e C-38. PB-31 a PB-34 são condicionais |
| As dependências do Backlog foram respeitadas? | Sim. Ex.: PB-14 depende de PB-06 e PB-13; PB-21 depende de PB-20 (a prova de conceito começa antes, a entrega fica em 26/02) |
| Cada módulo cabe na entrega do Roadmap? | E2 e E3 estão no limite; a divisão da homologação da E2 alivia a sobreposição |
| A capacidade semanal é suficiente? | Em horas sim (148 h/semana contra 1.840 h), mas **o custo não fecha** (ver Custos) |
| Homologação, integração, migração e treinamento têm tempo? | Sim, mas com folga zero na virada para o piloto |
| Piloto e encerramento continuam viáveis? | Sim, se as dependências do cliente chegarem nos prazos da seção 4 |

## 7. Se o trabalho não couber

Não basta mover datas. A ordem de resposta é: (1) adiar PB-26; (2) mover PB-25 para depois do go-live; (3) rever Roadmap e riscos; (4) se ainda não couber, abrir solicitação de mudança com Henrique. PB-24 e PB-25 fazem parte do escopo contratado e só saem por mudança.
