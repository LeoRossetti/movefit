# Projeto MoveFit — Roadmap

**Referências:** Aulas 24 e 25 — Product Backlog e Roadmap; Bloco F do handoff (cronograma comercial vendido)
**Dependências:** Escopo, Premissas e Restrições; Product Backlog (PB-01 a PB-34)

## 1. Objetivo

Distribuir os 34 itens do Product Backlog em entregas homologáveis alinhadas aos marcos comerciais vendidos, sem assumir que tudo cabe na primeira entrega, respeitando dependências, o pico de janeiro e fevereiro e o piloto em 08/03/2027.

## 2. Marcos comerciais (Bloco F do handoff)

| Marco comercial | Previsão | Resultado esperado |
|---|---|---|
| Kick-off | 26/11/2026 | Alinhamento de objetivos, governança, escopo e plano |
| Descoberta e especificação | 26/11 a 18/12/2026 | Fluxos prioritários e especificação funcional aprovados |
| 1ª entrega em homologação | 22/01/2027 | Cadastros, planos/matrículas e base do financeiro |
| 2ª entrega em homologação | 19/02/2027 | Agenda/reservas, avaliação física e portal do aluno |
| Integrações e preparação do piloto | 22/02 a 05/03/2027 | Integrações do piloto, migração final e treinamento |
| Piloto — Unidade Centro | 08/03/2027 | Operação real assistida |
| Expansão e encerramento | até 26/03/2027 | Demais unidades e aceite final |

## 3. Princípios usados

1. Cada entrega é homologada em até 5 dias úteis (RE-08).
2. Uma entrega só é usada em produção depois de homologada.
3. Itens **Must** entram antes dos **Should**; **Could** e condicionais não são compromisso.
4. Riscos de integração (Pagar.me, catraca) e migração começam cedo, em paralelo às entregas anteriores.
5. Se a capacidade não bastar, os itens **Should** saem primeiro, antes de qualquer **Must**.

## 4. Entregas

| Entrega | Marco comercial | Desenvolvimento | Entrega p/ homologação | Homologação (até) |
|---|---|---|---|---|
| Descoberta | Descoberta e especificação | 26/11 a 18/12/2026 | 18/12/2026 (spec aprovada) | — |
| E1 | 1ª entrega | 07/12/2026 a 22/01/2027 | 22/01/2027 | 29/01/2027 |
| E2 (parte 1: agenda, reservas e avaliação) | 2ª entrega | 04/01 a 05/02/2027 | 05/02/2027 (entrega parcial) | 16/02/2027 |
| E2 (parte 2: portal, Pagar.me e inadimplência) | 2ª entrega | 25/01 a 19/02/2027 | 19/02/2027 | 26/02/2027 |
| E3 | Prep. do piloto | 25/01 a 26/02/2027 | 26/02/2027 | 05/03/2027 |
| Piloto | Piloto | Go/No-Go 05/03, cutover 06 e 07/03 | — | Go-live 08/03/2027 |
| E4 | Expansão e encerramento | 15/03 a 25/03/2027 | — | Aceite final 25/03/2027 |

## 5. Itens do Backlog por entrega

### E1 — Cadastros, planos/matrículas e base do financeiro

| ID | Item | Prioridade | Tam. |
|---|---|---|---|
| PB-01 | Unidades e parâmetros gerais | Must | M |
| PB-02 | Perfis e permissões por função e unidade | Must | G |
| PB-03 | Cadastro de alunos, responsáveis e contatos | Must | M |
| PB-04 | Colaboradores, professores, modalidades e turmas | Must | M |
| PB-05 | Planos e regras | Must | M |
| PB-06 | Matrícula (aluno, plano, unidade) | Must | G |
| PB-07 | Congelamento e cancelamento (depende da regra P-05) | Must | M |
| PB-08 | Cobranças e saldos em aberto | Must | G |
| PB-27 | Trilhas de auditoria | Must | M |

### E2 — Agenda/reservas, avaliação física e portal

A E2 tem duas entregas internas: a **parte 1** (PB-12 a PB-16, PB-22 e PB-23) em 05/02 e a **parte 2** (PB-09, PB-10, PB-17 a PB-19 e PB-24) em 19/02. O marco comercial continua sendo 19/02. A divisão evita que a homologação inteira caia na semana de 22 a 26/02, junto com o fim da E3.

| ID | Item | Prioridade | Tam. |
|---|---|---|---|
| PB-12 | Grade, professor, capacidade e antecedência | Must | G |
| PB-13 | Consulta de aulas e vagas | Must | M |
| PB-14 | Reserva de vaga | Must | G |
| PB-15 | Cancelamento de reserva | Must | M |
| PB-16 | Lista de participantes | Must | P |
| PB-17 | Autenticação do aluno | Must | M |
| PB-18 | Dados, plano e situação no portal | Must | M |
| PB-19 | Agenda e reservas pelo portal responsivo | Must | G |
| PB-22 | Registro de avaliação física | Must | G |
| PB-23 | Evolução e registros anteriores | Must | M |
| PB-09 | Integração com o Pagar.me (depende de P-02) | Must | G |
| PB-10 | Dashboard de inadimplência (expectativa do patrocinador) | Must | M |
| PB-24 | Histórico recente de avaliações no portal | Should | M |

### E3 — Integrações e preparação do piloto

| ID | Item | Prioridade | Tam. |
|---|---|---|---|
| PB-11 | Migração (ativos, planos vigentes, saldos) | Must | G |
| PB-20 | Validação da situação do aluno na recepção | Must | M |
| PB-21 | Integração com a catraca da Unidade Centro (depende de P-01; a prova de conceito começa em 18/01) | Must | G |
| PB-25 | Painel gerencial por unidade e consolidado | Must | G |
| PB-28 | Treinamento dos usuários-chave | Must | M |
| PB-29 | Checklist, contingência e suporte assistido | Must | G |
| PB-26 | E-mails operacionais (candidato a adiar: não está na lista ES-01 a ES-12) | Should | M |

### E4 — Expansão e encerramento

| ID | Item | Prioridade | Situação |
|---|---|---|---|
| PB-30 | Expansão para as demais unidades | Must | Comprometido, mas só **planejamento e preparação** cabem em duas semanas (ponto 6.1) |
| PB-31 | Catracas das demais unidades | Should | Condicional à compatibilidade (PR-05) |
| PB-32 | Histórico legado adicional | Could | Condicional a layout e compatibilidade |
| PB-33 | SMS operacional | Could | Condicional a contrato e créditos do cliente |
| PB-34 | SSO Microsoft 365 | Could | Condicional a validação técnica; se houver impacto, vira mudança |

### Fora do Roadmap (Won't nesta baseline)

QR Code ou carteira digital, aplicativo nativo, folha e ponto, emissão fiscal, conciliação bancária completa, saneamento manual e troca física de catracas. O QR Code é o exemplo do fluxo de mudanças.

## 6. Pontos para o grupo decidir

1. **Expansão (PB-30).** O Escopo (ES-10) diz "expansão planejada", o Backlog diz "expandir" e o cronograma comercial diz "demais unidades" até 26/03. Em duas semanas após o piloto só cabe planejar e preparar. Alinhar a redação com a Pessoa 1.
2. **Prazo.** A proposta comercial fala em **16 semanas** (terminaria em 18/03/2027), a OS em **120 dias corridos** (26/03/2027). O Escopo (RE-01) adota só os 120 dias. Registrar a divergência.
3. **E2 e E3 estão pesadas.** E2 tem 13 itens e E3 tem 7, quatro deles de tamanho G, e as homologações se sobrepõem (22 a 26/02 e 01 a 05/03). Os Should (PB-24, PB-26) e, se necessário, PB-25 são os primeiros a sair.
4. **Painel (PB-25).** O piloto não depende dele. Se a capacidade falhar, pode passar para depois do go-live, antes do encerramento.
5. **Recorrência em cartão.** O handoff diz que ela é processada por rotina separada do Pagar.me. Confirmar se está fora do PB-09.

## 7. Rastreabilidade

| Origem | Uso neste Roadmap |
|---|---|
| Backlog PB-01 a PB-34 | Todos os itens aparecem em uma entrega ou em "Fora do Roadmap" |
| Bloco F (cronograma comercial) | Datas das entregas E1, E2 e E3 e do piloto |
| RE-02, RE-08 | Piloto em 08/03 e homologação em 5 dias úteis |
| RE-06, PR-09 | E1 e E2 atravessam janeiro e fevereiro; piloto depois do pico |
| Escopo condicional | PB-31 a PB-34 ficam na E4 como não comprometidos |
