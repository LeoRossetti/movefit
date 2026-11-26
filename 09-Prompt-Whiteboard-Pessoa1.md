# Prompt para o Claude Whiteboards — Parte da Pessoa 1

Conteúdo dos documentos 01 a 04 (Stakeholders, RACI, Escopo e Backlog). Cole o texto abaixo da linha `---` no chat do whiteboard. Os detalhes completos ficam nos arquivos `.md`; o quadro é só o resumo visual.

Observações para revisão (não colar no quadro):
- Fernanda Lopes fica só em "Consultar e envolver" (decisão tomada: opção 1). No Mapa do colega, o item 4 ainda a lista também em "Manter satisfeito"; esse ajuste no documento dele está com a Pessoa 2.
- O Backlog não vai para o quadro. Ele aparece pelas entregas do Roadmap.
- Nenhum valor interno de custo da WEBFLOW está neste prompt.

---

Monte um quadro simples para o projeto MoveFit (cliente VivaForma, contratada WEBFLOW, código NX-MF-2026-017, kick-off em 26/11/2026). Pode usar cores, ícones e um visual caprichado, em português, mas sem encher o quadro de informação: cada área deve ser curta e fácil de ler. Divida em 4 áreas.

**Área 1 — Matriz de stakeholders (poder × interesse)**
- **Gerenciar de perto** (poder alto, interesse alto):
  - Henrique Valença, Diretor Administrativo, patrocinador. Status quinzenal e decisões críticas sob demanda.
  - Juliana Prado, Gerente de Operações, ponto focal operacional proposto. Semanal.
  - Marcelo Iwata, Coordenador de TI (acessos, rede, segurança, integrações). Semanal na descoberta e nas integrações.
- **Consultar e envolver** (poder médio, interesse alto):
  - Fernanda Lopes, Coordenadora Financeira (cobrança, inadimplência, Pagar.me). Por workshop e marco financeiro.
  - Thiago Mota, Supervisor da Unidade Centro (piloto). Semanal na preparação e diário na operação assistida.
  - Patrícia Luz, Coordenadora de Professores (agenda e turmas). Descoberta, refinamento e homologação.
- **Manter informados e envolver** (poder baixo, interesse alto ou médio):
  - Carla Nunes, Recepção da Unidade Centro, usuária-chave. Entrevistas, testes e piloto.
  - Alunos da VivaForma, representados por usuários-chave.
  - Marketing da VivaForma, identidade visual, acionado por marco.
- **Manter satisfeitos e coordenar dependências** (poder médio, interesse médio): fornecedores Control iD, Pagar.me e fornecedor de rede.
- Mostre com uma seta o engajamento atual e o desejado dos principais. Exemplo: Thiago passa de neutro para quem lidera; os alunos passam de "desconhece" para apoiadores.

**Área 2 — Governança e RACI (resumo)**
Mostre só "quem decide o quê":
- **Henrique** aprova o Plano e a baseline inicial, mudanças com impacto em escopo, prazo ou custo, e o aceite do encerramento.
- **Juliana** aprova requisitos, critérios de aceite, prioridade do backlog, a homologação de cada marco (em até 5 dias úteis) e o Go/No-Go operacional do piloto.
- **Camila Nogueira** (gerente do projeto WEBFLOW) aprova mudanças dentro da baseline, prepara a entrega para homologação e coordena a migração, o cutover e a operação assistida.
- **Marcelo** aprova a disponibilização de dados, acessos, credenciais e equipamentos do cliente.
- **Marina Salles** (arquitetura) aprova arquitetura, segurança e integrações.
- **Lucas Ferraz** (Product Owner) prepara e mantém o backlog e os requisitos.
- **Diego, Bruna, Caio e Igor** desenvolvem e integram. **Larissa Furtado** (QA) testa. **Renata Paiva** (UX) desenha as interfaces. **Paulo Reis** cuida da implantação e do treinamento.
- Regras de destaque: o piloto só é liberado depois do parecer de TI, QA, implantação e negócio. Decisões técnicas entre TI e WEBFLOW são registradas e comunicadas a Camila e Juliana.

**Área 3 — Escopo em três colunas**
- **Incluído:** cadastros; planos e matrículas; financeiro operacional (inclui visão de inadimplência e Pagar.me); agenda e reservas; controle de acesso (integração principal no piloto da Unidade Centro); avaliação física; portal responsivo do aluno com usuário e senha; painel gerencial; migração inicial (alunos ativos, planos vigentes e saldos em aberto, com até duas cargas de validação e uma final); implantação (treinamento remoto em até 4 sessões de 2 horas, piloto e 5 dias úteis de operação assistida); plataforma e segurança; ambientes DEV, HML e PRD.
- **Condicional** (só entra sem mudança se a condição for atendida): catracas das demais unidades (equipamento compatível e conectividade); histórico legado adicional de avaliações (no layout acordado, sem saneamento pela WEBFLOW); SMS (provedor e créditos pagos pela VivaForma); SSO Microsoft 365 (sem impacto em esforço, prazo e custo).
- **Fora do escopo:** app nativo iOS ou Android; QR Code ou carteira digital; compra, troca ou manutenção de catracas e equipamentos de rede; folha, comissionamento e ponto; serviços contábeis, conciliação bancária completa e emissão fiscal; licenças de terceiros, créditos de SMS e tarifas do gateway; saneamento manual das bases legadas; migração irrestrita do histórico; funcionalidades não descritas; sustentação pós-garantia.
- Destaque três decisões: QR Code fica fora e é o exemplo do fluxo de mudanças; o dashboard de inadimplência está incluído; SSO é condicional e usuário e senha é a baseline.
- Abaixo, mostre as restrições principais: vigência de 120 dias corridos a partir do kick-off (até 26/03/2027); piloto da Unidade Centro em 08/03/2027; a recepção não pode parar durante a implantação; o projeto atravessa o pico de janeiro e fevereiro; homologação de cada marco em até 5 dias úteis; solução web responsiva.

**Área 4 — Fluxo de mudanças (exemplo: pedido de QR Code)**
O cliente pede entrada física por QR Code, que está fora da baseline. O fluxo é:
1. Pedido registrado (nenhum pedido verbal altera a baseline).
2. Análise de impacto em escopo, prazo, custo, arquitetura e premissas, feita por Camila com Lucas, Marina, Larissa e Marcelo consultados.
3. Decisão: se não afeta escopo contratado, prazo final ou custo, Camila aprova. Se afeta, Henrique e a autoridade comercial da WEBFLOW aprovam formalmente.
4. Resultado comunicado a Juliana e registrado. Se aprovado, entra no Backlog e no Roadmap.

Depois, agrupe as notas por tema e aponte se alguma das áreas está confusa.
