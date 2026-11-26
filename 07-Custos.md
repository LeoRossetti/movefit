# Projeto MoveFit — Custos e Capacidade

**Referências:** Aula de Gestão de Custos
**Dependências:** Cronograma (06); Restrições RE-03 e RE-04

> **Atenção:** os arquivos do grupo informam só os totais (10 profissionais, 1.840 horas, meta de R$ 156.000 e teto de R$ 168.000). **Não há valor-hora por papel nem a divisão das horas.** Por isso:
> - o valor-hora é a **média implícita**: R$ 156.000 ÷ 1.840 h = **R$ 84,78/h**;
> - a distribuição das horas por papel e por entrega é uma **estimativa nossa** e deve ser substituída pelos números do handoff.

## 1. Limites de custo

| Item | Valor |
|---|---|
| Meta de custo direto | R$ 156.000,00 |
| Teto interno | R$ 168.000,00 |
| Reserva gerencial (teto − meta) | R$ 12.000,00 |
| Horas de referência | 1.840 h |
| Equivalência da reserva | cerca de 141 h |

## 2. Horas e custo por papel (estimativa)

| Profissional | Papel | Horas | Custo (R$ 84,78/h) |
|---|---|---:|---:|
| Camila Nogueira | Gerente do projeto | 200 | 16.956,52 |
| Lucas Ferraz | Product Owner | 240 | 20.347,83 |
| Marina Salles | Arquitetura | 200 | 16.956,52 |
| Diego | Execução técnica | 220 | 18.652,17 |
| Bruna | Execução técnica | 220 | 18.652,17 |
| Caio | Execução técnica | 200 | 16.956,52 |
| Igor | Execução técnica | 200 | 16.956,52 |
| Larissa Furtado | Qualidade | 200 | 16.956,52 |
| Renata Paiva | UX | 100 | 8.478,26 |
| Paulo Reis | Implantação | 60 | 5.086,96 |
| **Total** | | **1.840** | **156.000,00** |

## 3. Horas e custo por fase (estimativa)

| Fase | Período | Horas | Custo |
|---|---|---:|---:|
| Iniciação e E1 | 26/11 a 28/12 | 280 | 23.739,13 |
| E2 | 21/12 a 05/02 | 400 | 33.913,04 |
| E3 | 04/01 a 26/02 | 380 | 32.217,39 |
| E4 e piloto | 01/02 a 12/03 | 520 | 44.086,96 |
| Expansão e encerramento | 15/03 a 25/03 | 160 | 13.565,22 |
| Retrabalho de homologação e contingência | todo o projeto | 100 | 8.478,26 |
| **Total** | | **1.840** | **156.000,00** |

## 4. Capacidade

- Projeto de 26/11/2026 a 25/03/2027: cerca de **17 semanas**.
- 1.840 h ÷ 17 semanas = **cerca de 108 h por semana** para a equipe toda, ou aproximadamente 11 h por pessoa.
- A E4 concentra 520 h em cerca de 6 semanas (**87 h por semana** só nela, somadas às horas de E3 em paralelo). É o ponto de maior pressão.
- Se a disponibilidade semanal do handoff for menor que isso, o Cronograma não fecha (premissa PR-08).

## 5. Uso da reserva de R$ 12.000

| Situação | Uso |
|---|---|
| Retrabalho por rejeição de homologação | Primeiro, as 100 h já previstas na tabela da seção 3 |
| Atraso de dependência do cliente (PR-03 a PR-07) | Reserva gerencial, com registro da causa |
| Catracas de outras unidades, SSO ou histórico legado | **Não usar a reserva.** Seguem o fluxo de mudanças |
| Qualquer estouro acima do teto de R$ 168.000 | Decisão de Henrique |

## 6. Custos fora das horas

| Item | Quem paga | Observação |
|---|---|---|
| Licenças de terceiros, créditos de SMS, tarifas do Pagar.me | VivaForma | Fora do escopo |
| Catracas, controladoras e rede | VivaForma | Fora do escopo |
| Nuvem dos ambientes DEV, HML e PRD | WEBFLOW | **Valor não consta nos arquivos.** Confirmar se está dentro dos R$ 156.000 |
| Nuvem extraordinária | VivaForma | Fora do escopo |

## 7. Controle

- Acompanhar horas realizadas × previstas por entrega, a cada 15 dias, no status para Henrique.
- Alerta amarelo quando o realizado passar de 90% do previsto da fase; vermelho ao usar a reserva.
- Mudanças com impacto de custo seguem a RACI: aprovação de Henrique.
