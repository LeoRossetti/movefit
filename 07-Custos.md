# Projeto MoveFit — Custos e Capacidade

**Referências:** Aula de Gestão de Custos; Bloco E do handoff
**Dependências:** Cronograma (06); Restrições RE-03 e RE-04

> **Regra deste documento:** todos os números vêm do Bloco E do handoff (horas, valor-hora, capacidade, teto e meta) ou de contas feitas só com eles. Onde há uma suposição, ela está marcada como **PP** e explicada na seção 8.

## 1. Limites do handoff

| Item | Valor |
|---|---|
| Receita comercial do projeto | R$ 286.000 |
| Teto de custo direto | R$ 168.000 |
| Meta de custo direto | R$ 156.000 |
| Reserva gerencial interna (teto − meta) | R$ 12.000 |
| Margem bruta alvo | mínimo 40% antes de despesas corporativas |
| Horas de referência | 1.840 h |

O teto inclui horas da equipe e contratação pontual aprovada. DEV e HML são absorvidos pela área de plataforma e **não entram como hora do projeto**; consumo extraordinário deve ser sinalizado.

## 2. Equipe e capacidade (handoff)

| Profissional | Função | h/semana | Custo/h | Capacidade em 16 semanas |
|---|---|---:|---:|---:|
| Camila Nogueira | Gerente de Projetos | 12 | R$ 145 | 192 h |
| Lucas Ferraz | Analista de Negócios / PO | 20 | R$ 105 | 320 h |
| Marina Salles | Arquiteta de Soluções | 6 | R$ 165 | 96 h |
| Diego Azevedo | Dev Backend | 24 | R$ 135 | 384 h |
| Bruna Teles | Dev Full Stack | 30 | R$ 105 | 480 h |
| Caio Mendes | Dev Frontend | 20 | R$ 100 | 320 h |
| Larissa Furtado | QA | 16 | R$ 90 | 256 h |
| Igor Matos | DevOps / Cloud | 4 | R$ 150 | 64 h |
| Renata Paiva | UX/UI | 8 | R$ 95 | 128 h |
| Paulo Reis | Implantação / Treinamento | 8 | R$ 85 | 128 h |
| **Total** | | **148** | | **2.368 h** |

As 16 semanas são o prazo da proposta comercial (Bloco B). As 1.840 h de referência usam **78%** da capacidade total (2.368 h). Em horas, o projeto cabe.

## 3. Horas de referência por frente × capacidade da função

As horas por frente vêm do handoff. A coluna de capacidade soma as pessoas cuja função corresponde à frente.

| Frente | Horas | Funções que a atendem | Capacidade (16 sem.) | Uso |
|---|---:|---|---:|---:|
| Gestão e governança | 180 | Gerente de Projetos | 192 h | 94% |
| Descoberta, requisitos e UX | 320 | Analista de Negócios, UX/UI | 448 h | 71% |
| Arquitetura e DevOps | 120 | Arquiteta, DevOps | 160 h | 75% |
| Desenvolvimento | 780 | Dev Backend, Full Stack, Frontend | 1.184 h | 66% |
| QA e apoio à homologação | 260 | QA | 256 h | **102%** |
| Migração, implantação e treinamento | 180 | Implantação | 128 h | **141%** |

**O que isso mostra:**
- QA e implantação passam da capacidade da própria função. O restante precisa vir de outras pessoas (o handoff chama a frente de QA de "QA e apoio à homologação"), o que vai para o PP-02.
- A gestão fica em 94%, sem margem para a Camila.
- Desenvolvimento tem folga (66%), então há espaço para mover tarefas entre os devs.

## 4. Custo estimado

O handoff não diz quantas horas cada pessoa faz. A estimativa usa a única base disponível: **as horas se distribuem na proporção da disponibilidade semanal** (PP-02).

| Conta | Valor |
|---|---|
| Custo da equipe por semana (soma de h/semana × custo/h) | R$ 16.700 |
| Média ponderada por hora (R$ 16.700 ÷ 148 h) | **R$ 112,84/h** |
| **Custo estimado (1.840 h × R$ 112,84)** | **R$ 207.622 (cerca de R$ 207,6 mil)** |
| Piso teórico (1.840 h, todas na menor tarifa, R$ 85/h) | R$ 156.400 |

### Comparação com os limites

| Cenário | Custo | Diferença | Margem bruta |
|---|---:|---:|---:|
| Meta | R$ 156.000 | — | 45,5% |
| Teto | R$ 168.000 | — | 41,3% |
| **Estimado** | **R$ 207.622** | **+ R$ 39.622 sobre o teto** | **27,4%** |

**Três fatos que não dependem de suposição:**
1. A menor tarifa da equipe é R$ 85/h. Mesmo com as 1.840 h todas nessa tarifa, o custo (R$ 156.400) seria maior que a meta de R$ 156.000. A meta equivale a R$ 84,78/h, abaixo de qualquer tarifa. **A meta não é atingível.**
2. Com a média ponderada da equipe, o projeto só cabe no teto com cerca de **1.489 h**, ou seja 351 h (19%) a menos que a referência.
3. A reserva de R$ 12.000 já está consumida pela estimativa.

## 5. Alavancas para reduzir o custo (sem inventar quantidades)

O kit não diz quantas horas cada ajuste economizaria, então aqui só aparece **quanto vale uma hora**, calculado com os valores-hora do handoff.

| Alavanca | Valor por hora | Base |
|---|---:|---|
| Eliminar 1 h do projeto | R$ 112,84 | Média ponderada |
| Passar 1 h de Camila (R$ 145) para Lucas (R$ 105) | R$ 40 | Valores-hora do handoff |
| Passar 1 h de Diego (R$ 135) para Caio (R$ 100) | R$ 35 | Idem |
| Passar 1 h de Diego (R$ 135) para Bruna (R$ 105) | R$ 30 | Idem |
| Passar 1 h de Marina (R$ 165) para Diego (R$ 135) | R$ 30 | Idem |

**O que dá para concluir só com esses dados:**
- Para fechar os R$ 39.622 só trocando de perfil a R$ 40 por hora, seria preciso mover cerca de 990 h. A R$ 30 por hora, cerca de 1.320 h. Isso é de 54% a 72% de todas as horas do projeto, o que não é viável.
- **Só trocar o mix não resolve.** É preciso reduzir horas (cerca de 351 h) ou rever o teto.
- O handoff diz que as horas são referência comercial e que o mix pode ser revisto, então a troca de perfil é permitida, mas só reduz uma parte.

### Ação registrada

O custo **não foi corrigido no papel**, porque o kit não traz dados para isso. A ação é única: antes do kick-off, a Camila leva à gestão de operações a pergunta **"as 1.840 h e o teto de R$ 168 mil são compatíveis com as tarifas da equipe? Qual é o plano de alocação real?"**. Enquanto não houver resposta, o risco R-20 permanece aberto.

### Opções que dependem de decisão externa

Estas são opções para o grupo e a gestão decidirem. Eu não escolho entre elas.

| Opção | Efeito | Observação |
|---|---|---|
| A. Reduzir horas em cerca de 351 h | Cabe no teto | O handoff cita componentes já usados pela WEBFLOW (PP-01), que poderiam reduzir o desenvolvimento, mas não diz quanto |
| B. Rever o mix de perfis | Reduz o custo médio por hora | Limitado pela capacidade de cada função (seção 3) e só cobre uma parte do gap |
| C. Pedir exceção do teto ou da margem | Mantém o escopo | Decisão da gestão de operações (Eduardo Viana), fora do projeto |
| D. Mudança de escopo com o cliente | Reduz esforço | Exige Henrique (RACI). O escopo já está assinado |

## 6. Reserva de R$ 12.000

| Situação | Uso |
|---|---|
| Retrabalho por rejeição de homologação | Reserva gerencial, com registro |
| Atraso de dependência do cliente (PR-03 a PR-07) | Reserva, com registro da causa; avaliar prorrogação (OS permite) |
| Catracas das outras unidades, SSO ou histórico legado | **Não usar a reserva.** Seguem o fluxo de mudanças |
| Qualquer estouro acima do teto | Decisão da gestão |

Com o custo estimado em R$ 207.622, a reserva já está **consumida**. É preciso tratar a seção 5 antes de falar em reserva.

## 7. Custos fora das horas

| Item | Quem paga | Observação |
|---|---|---|
| DEV e HML | Plataforma da WEBFLOW | Não lançar como hora; sinalizar consumo extraordinário |
| Ambiente produtivo (PRD) | WEBFLOW durante o projeto | O handoff não traz valor; confirmar se entra no teto |
| Licenças de terceiros, SMS, tarifas do Pagar.me, nuvem extraordinária | VivaForma | Fora do escopo |
| Catracas, controladoras e rede | VivaForma | Fora do escopo |
| Deslocamento fora da Região Metropolitana de Campinas | VivaForma (reembolso, se aprovado) | Bloco B |

## 8. Premissas de planejamento (suposições nossas)

| ID | Premissa | De onde vem | Se falhar |
|---|---|---|---|
| PP-01 | O desenvolvimento pode reaproveitar componentes existentes da WEBFLOW | Uma frase do resumo comercial (Bloco A): solução "com base em componentes já utilizados pela WEBFLOW". **Não quantificada** | Sem redução de esforço; o gap de custo permanece |
| PP-02 | As 1.840 h se distribuem na proporção da disponibilidade semanal de cada pessoa | Escolha neutra, porque o handoff não divide as horas. Ele diz que o mix pode ser revisto | O custo muda para mais ou para menos, mas continua acima da meta (fato 1 da seção 4) |
| PP-03 | O projeto tem 16 semanas de trabalho | Prazo da proposta comercial (Bloco B). A OS fala em 120 dias, cerca de 17 semanas | A capacidade total muda proporcionalmente |

## 9. Faturamento

| Parcela | Gatilho | Valor |
|---|---|---:|
| 1 | Assinatura / OS (20%) | R$ 57.200 |
| 2 | Especificação funcional concluída (20%) | R$ 57.200 |
| 3 | Ambiente de homologação disponível (25%) | R$ 71.500 |
| 4 | Aceite do piloto (25%) | R$ 71.500 |
| 5 | Encerramento da implantação (10%) | R$ 28.600 |
| | **Total** | **R$ 286.000** |

## 10. Controle

- Acompanhar horas realizadas × previstas por frente a cada 15 dias, junto com o status para Henrique.
- Alerta amarelo ao passar de 90% do previsto em uma frente; vermelho ao tocar a reserva.
- Mudanças com impacto de custo seguem a RACI (aprovação de Henrique).
