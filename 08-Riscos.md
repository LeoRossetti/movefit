# Projeto MoveFit — Registro de Riscos

**Referências:** Aula de Gestão de Riscos
**Dependências:** Premissas PR-01 a PR-10; Escopo condicional; Cronograma (06)

## 1. Escala

- **Probabilidade (P):** 1 baixa, 2 média, 3 alta.
- **Impacto (I):** 1 baixo, 2 médio, 3 alto (3 = afeta o piloto, o prazo contratual ou o teto de custo).
- **Severidade:** P × I. De 1 a 2 baixa, 3 a 4 média, 6 a 9 alta.

## 2. Riscos vindos das premissas

| ID | Premissa | Risco | P | I | Sev. | Resposta | Dono | Gatilho |
|---|---|---|:-:|:-:|:-:|---|---|---|
| R-01 | PR-01 | Ponto focal sem autonomia formal; decisões atrasam | 2 | 2 | 4 | **Mitigar:** formalizar Juliana e um substituto no kick-off (C-01) | Camila | Ata do kick-off sem ponto focal |
| R-02 | PR-02 | Usuários-chave indisponíveis (pico de janeiro e fevereiro) | 3 | 3 | 9 | **Mitigar:** agendar sessões e homologações desde dezembro; ter suplentes | Juliana | Faltar 2 sessões seguidas |
| R-03 | PR-03 | Homologação passa de 5 dias úteis | 3 | 2 | 6 | **Mitigar:** cenários prontos de antemão; lembrete no 3º dia; registrar atraso como dependência do cliente | Lucas | Dia 4 sem retorno |
| R-04 | PR-04 | Sandbox do Pagar.me atrasa | 2 | 3 | 6 | **Mitigar:** pedir em C-03; usar simulador interno para avançar PB-08; prazo-limite 04/01 | Marina | Sem credencial em 04/01 |
| R-05 | PR-05 | Modelo ou documentação da catraca chega tarde | 2 | 3 | 6 | **Mitigar:** pedir em C-03; contato direto com Marcelo e Control iD; prazo-limite 29/01. **Contingência:** acesso manual na recepção no piloto | Marina | Sem modelo em 29/01 |
| R-06 | PR-06 | Dados de migração fora do layout ou atrasados | 3 | 3 | 9 | **Mitigar:** aprovar layout cedo; validar amostra em dezembro; duas cargas de validação. **Contingência:** reduzir a carga ou abrir mudança | Lucas | Sem dados em 29/01 |
| R-07 | PR-07 | Fornecedor de rede sem janela nas unidades | 2 | 2 | 4 | **Mitigar:** combinar janelas por escrito; uso do fim de semana para cutover | Marcelo | Janela não confirmada em 12/02 |
| R-08 | PR-08 | Capacidade da WEBFLOW menor que a reservada (férias, saídas) | 2 | 3 | 6 | **Mitigar:** acompanhar horas a cada 15 dias; Camila cobre ausências; reordenar o Backlog | Camila | Realizado abaixo de 85% do previsto |
| R-09 | PR-09 | Piloto empurrado para dentro do pico operacional | 1 | 3 | 3 | **Aceitar com monitoramento:** o piloto é depois do pico (08/03); não antecipar | Thiago | Cliente pede antecipação |
| R-10 | PR-10 | Identidade visual do Marketing atrasa | 2 | 1 | 2 | **Aceitar:** usar identidade provisória; custo do ajuste dentro das 100 h de retrabalho | Renata | Sem material em 11/01 |

## 3. Riscos dos itens condicionais

| ID | Item | Risco | P | I | Sev. | Resposta | Dono | Gatilho |
|---|---|---|:-:|:-:|:-:|---|---|---|
| R-11 | Catracas das demais unidades | Equipamento incompatível | 2 | 2 | 4 | **Evitar:** levantar modelos em janeiro; incompatível = troca pelo cliente ou mudança | Marina | Modelo sem API ou documentação |
| R-12 | Histórico legado | Dados fora do layout, sem saneamento | 3 | 1 | 3 | **Transferir:** saneamento é do cliente; sem layout, o item fica fora | Lucas | Arquivo fora do layout |
| R-13 | SMS | Provedor não contratado ou sem créditos | 2 | 1 | 2 | **Aceitar:** não entra no Roadmap comprometido | Juliana | Sem contrato até a E4 |
| R-14 | SSO Microsoft 365 | Pedido de última hora com impacto em prazo e custo | 2 | 2 | 4 | **Evitar:** manter usuário e senha na baseline; qualquer SSO por solicitação de mudança | Camila | Pedido do cliente |

## 4. Riscos do projeto

| ID | Risco | P | I | Sev. | Resposta | Dono | Gatilho |
|---|---|:-:|:-:|:-:|---|---|---|
| R-15 | A E4 não cabe na capacidade e no prazo (folga zero até o piloto) | 3 | 3 | 9 | **Mitigar:** tirar PB-24 e PB-26; adiantar PB-22 e PB-25; rever Roadmap. **Escalar:** mudança com Henrique | Camila | C-28 ou C-25 atrasar 3 dias |
| R-16 | A recepção para na virada do piloto | 2 | 3 | 6 | **Mitigar:** cutover no fim de semana; ensaio de rollback (C-33); acesso manual como contingência | Paulo | Ensaio de rollback reprovado |
| R-17 | Defeitos críticos descobertos só no Go/No-Go | 2 | 3 | 6 | **Mitigar:** testes por entrega; homologação da E4 completa antes do Go/No-Go | Larissa | Defeito crítico aberto em 03/03 |
| R-18 | Feriados e recesso (25/12, 01/01, Carnaval, Sexta-feira Santa em 26/03) reduzem a capacidade | 3 | 2 | 6 | **Mitigar:** considerar nos prazos; aceite final em 25/03 | Camila | Equipe indisponível nessas semanas |
| R-19 | Pedido de mudança informal (QR Code, app) fora da baseline | 2 | 2 | 4 | **Evitar:** fluxo formal de mudanças; nenhum pedido verbal altera a baseline | Camila | Pedido fora da baseline |
| R-20 | Custo passa do teto de R$ 168.000 | 1 | 3 | 3 | **Mitigar:** controle quinzenal; reserva de R$ 12.000 só com registro | Camila | Realizado acima de 90% antes do piloto |

## 5. Riscos prioritários

| Ordem | Risco | Severidade |
|---|---|:-:|
| 1 | R-02 Usuários-chave indisponíveis | 9 |
| 2 | R-06 Dados de migração | 9 |
| 3 | R-15 E4 sem folga | 9 |
| 4 | R-03, R-04, R-05, R-08, R-16, R-17, R-18 | 6 |

## 6. Rastreabilidade

- PR-01 a PR-10 → R-01 a R-10.
- Escopo condicional (catracas, histórico, SMS, SSO) → R-11 a R-14.
- Restrições RE-02, RE-05 e RE-06 → R-09, R-16 e R-18.

## 7. Revisão

O registro deve ser revisado a cada entrega e antes do Go/No-Go, com Henrique informado de qualquer risco de severidade 9.
