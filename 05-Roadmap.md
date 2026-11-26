# Projeto MoveFit — Roadmap

**Referências:** Aulas 24 e 25 — Product Backlog e Roadmap
**Dependências:** Escopo, Premissas e Restrições; Product Backlog (PB-01 a PB-34)

> **Atenção:** os arquivos do grupo não trazem a lista dos "marcos comerciais" do contrato. As entregas e datas abaixo são uma **proposta** montada a partir das restrições (RE-01, RE-02, RE-06, RE-08). Conferir com o handoff e ajustar se houver marcos contratuais diferentes.

## 1. Objetivo

Distribuir os 34 itens do Product Backlog em entregas homologáveis, sem assumir que tudo cabe na primeira, respeitando dependências, o pico de janeiro e fevereiro e o piloto em 08/03/2027.

## 2. Princípios usados

1. Cada entrega é homologada pelo cliente em até 5 dias úteis (RE-08).
2. Uma entrega só começa a ser usada depois de homologada.
3. Itens **Must** entram antes dos **Should**; **Could** e itens condicionais não são compromisso.
4. Riscos de integração (Pagar.me, catraca) e de migração começam cedo.
5. Se a capacidade não bastar, os itens **Should** saem da entrega do piloto antes de qualquer item **Must**.

## 3. Entregas

| Entrega | Tema | Janela de desenvolvimento | Entrega para homologação | Homologação (até) |
|---|---|---|---|---|
| E1 | Fundação | 30/11/2026 a 18/12/2026 | 18/12/2026 | 28/12/2026 |
| E2 | Núcleo operacional e financeiro | 21/12/2026 a 29/01/2027 | 29/01/2027 | 05/02/2027 |
| E3 | Agenda, reservas e portal | 04/01/2027 a 19/02/2027 | 19/02/2027 | 26/02/2027 |
| E4 | Prontidão do piloto | 01/02/2027 a 26/02/2027 | 26/02/2027 | 05/03/2027 |
| Piloto | Go-live Unidade Centro | — | Go/No-Go em 05/03/2027 | Go-live 08/03/2027 |
| E5 | Expansão e encerramento | 15/03/2027 a 25/03/2027 | 25/03/2027 | Aceite final até 25/03/2027 |

## 4. Itens do Backlog por entrega

### E1 — Fundação

| ID | Item | Prioridade | Tam. |
|---|---|---|---|
| PB-01 | Unidades e parâmetros gerais | Must | M |
| PB-02 | Perfis e permissões por função e unidade | Must | G |
| PB-03 | Cadastro de alunos, responsáveis e contatos | Must | M |
| PB-04 | Cadastro de colaboradores, professores, modalidades e turmas | Must | M |
| PB-05 | Planos e regras | Must | M |

### E2 — Núcleo operacional e financeiro

| ID | Item | Prioridade | Tam. |
|---|---|---|---|
| PB-06 | Matrícula (aluno, plano, unidade) | Must | G |
| PB-07 | Congelamento e cancelamento | Must | M |
| PB-08 | Cobranças e saldos em aberto | Must | G |
| PB-09 | Integração com o Pagar.me | Must | G |
| PB-10 | Dashboard de inadimplência | Must | M |
| PB-27 | Trilhas de auditoria | Must | M |

### E3 — Agenda, reservas e portal

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

### E4 — Prontidão do piloto

| ID | Item | Prioridade | Tam. |
|---|---|---|---|
| PB-11 | Migração (ativos, planos vigentes, saldos) | Must | G |
| PB-20 | Validação da situação do aluno na recepção | Must | M |
| PB-21 | Integração com a catraca da Unidade Centro | Must | G |
| PB-22 | Registro de avaliação física | Must | G |
| PB-23 | Evolução e registros anteriores | Must | M |
| PB-25 | Painel gerencial por unidade e consolidado | Must | G |
| PB-28 | Treinamento dos usuários-chave | Must | M |
| PB-29 | Checklist, contingência e suporte assistido | Must | G |
| PB-24 | Histórico recente de avaliações no portal | Should | M |
| PB-26 | E-mails operacionais | Should | M |

> **PB-24 e PB-26 são os primeiros a sair da E4** se a capacidade não fechar. Nesse caso passam para a E5, sem afetar o piloto.

### E5 — Expansão e encerramento

| ID | Item | Prioridade | Situação |
|---|---|---|---|
| PB-30 | Expansão para as demais unidades | Must | Comprometido, mas só **planejamento e preparação** cabem em 2 semanas (ver ponto 5.1) |
| PB-31 | Catracas das demais unidades | Should | Condicional à compatibilidade (PR-05) |
| PB-32 | Histórico legado adicional | Could | Condicional a layout e compatibilidade |
| PB-33 | SMS operacional | Could | Condicional a contrato e créditos do cliente |
| PB-34 | SSO Microsoft 365 | Could | Condicional a validação técnica; se houver impacto, vira mudança |

### Fora do Roadmap (Won't nesta baseline)

QR Code ou carteira digital, aplicativo nativo, folha e ponto, emissão fiscal, conciliação bancária completa, saneamento manual e troca física de catracas. O QR Code é o exemplo do fluxo de mudanças.

## 5. Pontos para o grupo decidir

1. **Expansão (PB-30).** O Escopo (ES-10) diz "expansão planejada", mas o Backlog diz "expandir". Em duas semanas depois do piloto, só cabe planejar e preparar as demais unidades, e não implantá-las. Combinar com a Pessoa 1 qual redação vale.
2. **E4 está pesada.** São 8 itens Must, 4 deles de tamanho G. Veja o risco R-15 e a folga zero no Cronograma.
3. **Marcos comerciais.** Se existirem datas contratuais diferentes das propostas, as entregas E1 a E4 devem ser realinhadas.

## 6. Rastreabilidade

| Origem | Uso neste Roadmap |
|---|---|
| Backlog PB-01 a PB-34 | Todos os itens aparecem em uma entrega ou em "Fora do Roadmap" |
| RE-02, RE-08 | Datas do piloto e janela de homologação |
| RE-06, PR-09 | E3 e E4 atravessam janeiro e fevereiro; piloto só depois do pico |
| Escopo condicional | PB-31 a PB-34 ficam na E5 como não comprometidos |
