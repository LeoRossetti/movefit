# Projeto MoveFit — Registro de Riscos

**Referências:** Aula de Gestão de Riscos; Bloco G do handoff
**Dependências:** Premissas PR-01 a PR-10; Escopo condicional; Cronograma (06); Custos (07)

## 1. Escala

- **Probabilidade (P):** 1 baixa, 2 média, 3 alta.
- **Impacto (I):** 1 baixo, 2 médio, 3 alto (3 = afeta o piloto, o prazo contratual ou o teto de custo).
- **Severidade:** P × I. De 1 a 2 baixa, 3 a 4 média, 6 a 9 alta.

## 2. Riscos vindos das premissas

| ID | Premissa | Risco | P | I | Sev. | Resposta | Dono | Gatilho |
|---|---|---|:-:|:-:|:-:|---|---|---|
| R-01 | PR-01 | Ponto focal sem autonomia formal; decisões atrasam | 2 | 2 | 4 | **Mitigar:** formalizar Juliana e um substituto no kick-off (C-01) | Camila | Ata sem ponto focal |
| R-02 | PR-02 | Usuários-chave indisponíveis no pico de janeiro e fevereiro | 3 | 3 | 9 | **Mitigar:** obter o calendário de indisponibilidade (P-07); agendar homologações desde dezembro; ter suplentes | Juliana | Faltar 2 sessões seguidas |
| R-03 | PR-03 | Homologação passa de 5 dias úteis | 3 | 2 | 6 | **Mitigar:** cenários prontos; lembrete no 3º dia; formalizar o envio (a OS permite considerar aceito após 5 dias úteis) | Lucas | Dia 4 sem retorno |
| R-04 | PR-04 | Sandbox do Pagar.me atrasa (P-02) | 2 | 3 | 6 | **Mitigar:** pedir em C-03; usar simulador interno; prazo-limite 04/01 | Marina | Sem credencial em 04/01 |
| R-05 | PR-05 | Modelo ou documentação da catraca chega tarde (P-01). O Centro foi informado como Control iD iDBlock, mas a Unidade Norte tem equipamentos antigos | 2 | 3 | 6 | **Mitigar:** confirmar o modelo do Centro; contato direto com Marcelo e Control iD; prazo-limite 22/01. **Contingência:** acesso manual na recepção no piloto | Marina | Sem confirmação em 22/01 |
| R-06 | PR-06 | Dados de migração fora do layout ou atrasados (P-03); as bases têm campos não padronizados | 3 | 3 | 9 | **Mitigar:** receber a amostra em dezembro e analisá-la em janeiro (C-05a); aprovar o layout até 22/01; carga de validação 1 já em janeiro (C-24) e carga 2 em fevereiro (C-25). **Contingência:** reduzir a carga ou abrir mudança | Lucas | Sem dados em 22/01 |
| R-07 | PR-07 | Fornecedor de rede sem janela nas unidades | 2 | 2 | 4 | **Mitigar:** combinar janelas por escrito; cutover no fim de semana | Marcelo | Janela não confirmada em 12/02 |
| R-08 | PR-08 | Capacidade da WEBFLOW menor que a reservada (outros projetos) | 2 | 3 | 6 | **Mitigar:** acompanhar horas a cada 15 dias; reordenar o Backlog | Camila | Realizado abaixo de 85% do previsto |
| R-09 | PR-09 | Piloto empurrado para dentro do pico operacional | 1 | 3 | 3 | **Aceitar com monitoramento:** o piloto é depois do pico (08/03) | Thiago | Cliente pede antecipação |
| R-10 | PR-10 | Identidade visual do Marketing atrasa (P-08) | 2 | 1 | 2 | **Aceitar:** identidade provisória; ajuste com retrabalho | Renata | Sem material em 11/01 |

## 3. Riscos dos itens condicionais

| ID | Item | Risco | P | I | Sev. | Resposta | Dono | Gatilho |
|---|---|---|:-:|:-:|:-:|---|---|---|
| R-11 | Catracas das demais unidades | Equipamento incompatível (Norte com modelos antigos) | 3 | 2 | 6 | **Evitar:** levantar modelos em janeiro; incompatível = troca pelo cliente ou mudança | Marina | Modelo sem API ou documentação |
| R-12 | Histórico legado | Cliente espera histórico completo (foi dito na negociação que a WEBFLOW faria a carga); dados fora do layout | 3 | 2 | 6 | **Transferir:** alinhar no kick-off que só entra histórico no layout e compatível; saneamento é do cliente | Lucas | Pedido de histórico completo |
| R-13 | SMS | Provedor não contratado ou sem créditos | 2 | 1 | 2 | **Aceitar:** não entra no Roadmap comprometido | Juliana | Sem contrato até a E3 |
| R-14 | SSO Microsoft 365 | Pedido de última hora com impacto em prazo e custo (P-06) | 2 | 2 | 4 | **Evitar:** manter usuário e senha na baseline; SSO só por mudança | Camila | Pedido do cliente |

## 4. Riscos do projeto

| ID | Risco | P | I | Sev. | Resposta | Dono | Gatilho |
|---|---|:-:|:-:|:-:|---|---|---|
| R-15 | E2 e E3 não cabem no prazo (13 e 7 itens, folga zero até o piloto) | 3 | 3 | 9 | **Mitigar:** iniciar a catraca em janeiro (C-27); dividir a homologação da E2 em duas partes (C-23a e C-23b); adiar PB-26 e, se preciso, PB-25; rever Roadmap. **Escalar:** mudança com Henrique | Camila | C-24 ou C-27 atrasar 3 dias |
| R-16 | A recepção para na virada do piloto | 2 | 3 | 6 | **Mitigar:** cutover no fim de semana; ensaio de rollback (C-31); acesso manual como contingência | Paulo | Ensaio de rollback reprovado |
| R-17 | Defeitos críticos descobertos só no Go/No-Go | 2 | 3 | 6 | **Mitigar:** testes por entrega; homologação da E3 completa antes do Go/No-Go | Larissa | Defeito crítico aberto em 03/03 |
| R-18 | Feriados e recesso (25/12, 01/01, Carnaval, 26/03) reduzem a capacidade | 3 | 2 | 6 | **Mitigar:** considerar nos prazos; aceite final em 25/03 | Camila | Equipe indisponível nessas semanas |
| R-19 | Pedido de mudança informal (QR Code, app) fora da baseline | 2 | 2 | 4 | **Evitar:** fluxo formal; nenhum pedido verbal altera a baseline | Camila | Pedido fora da baseline |
| R-20 | **Custo estimado de R$ 207,6 mil passa o teto de R$ 168.000 e a margem alvo de 40%** | 3 | 3 | 9 | **Mitigar:** trocar o mix de perfis onde a capacidade permitir (Custos, seção 5), o que só cobre parte do gap. **Escalar:** antes do kick-off, a Camila pergunta à gestão de operações se as 1.840 h e o teto de R$ 168 mil são compatíveis com as tarifas da equipe e qual é o plano de alocação real; as saídas possíveis são reduzir cerca de 351 h, rever o teto ou mudar o escopo; controle quinzenal de horas | Camila | Já materializado na estimativa |
| R-21 | Gargalo de arquitetura e DevOps: Marina (6 h/semana) e Igor (4 h/semana) concentram Pagar.me, catraca, ambientes e cutover | 3 | 2 | 6 | **Mitigar:** fechar as decisões de arquitetura e automatizar a implantação em dezembro (C-04); agendar as horas dos dois nas semanas críticas (jan a fev); pedir ampliação de horas ao gestor de operações | Camila | Fila de decisões técnicas com mais de 3 dias |
| R-22 | Divergência de prazo: proposta fala em 16 semanas (18/03), OS em 120 dias (26/03) | 2 | 2 | 4 | **Mitigar:** registrar a divergência e decidir a data de encerramento no kick-off | Camila | Cliente cobrar 18/03 |
| R-23 | Recorrência em cartão é processada por rotina separada do Pagar.me e pode ser exigida | 2 | 2 | 4 | **Evitar:** confirmar com Fernanda na descoberta se está fora do PB-09; se não, mudança | Lucas | Pedido de recorrência |
| R-24 | A premissa PP-01 (reaproveitamento de componentes da WEBFLOW) não se confirma e o desenvolvimento não diminui | 2 | 2 | 4 | **Aceitar com validação:** a Marina avalia o que dá para reaproveitar na fase de arquitetura (C-04). O custo estimado já não conta com essa economia, que o kit não quantifica; o gap de custo continua sendo escalado (R-20) | Marina | Sem componentes reaproveitáveis até 18/12 |

## 5. Riscos prioritários

| Ordem | Risco | Severidade |
|---|---|:-:|
| 1 | R-20 Custo acima do teto | 9 |
| 2 | R-02 Usuários-chave indisponíveis | 9 |
| 3 | R-06 Dados de migração | 9 |
| 4 | R-15 E2 e E3 sem folga | 9 |
| 5 | R-03, R-04, R-05, R-08, R-11, R-12, R-16, R-17, R-18, R-21 | 6 |

## 6. Rastreabilidade

- PR-01 a PR-10 → R-01 a R-10.
- Escopo condicional (catracas, histórico, SMS, SSO) → R-11 a R-14.
- Restrições RE-02, RE-03, RE-05 e RE-06 → R-09, R-20, R-16 e R-18.
- Pendências P-01 a P-08 do handoff → R-02, R-04, R-05, R-06, R-10, R-14.

## 7. Revisão

O registro deve ser revisado a cada entrega e antes do Go/No-Go, com Henrique informado de qualquer risco de severidade 9 que afete o cliente. O R-20 é interno da WEBFLOW e vai para a gestão de operações.
