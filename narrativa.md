# Narrativa de Carreira

## Início: Formação e Primeiros Contatos com Tecnologia (até 2005)

A trajetória começou cedo, antes mesmo da faculdade. Aprendi programação praticamente sozinho: primeiro com BASIC (foco em lógica), depois com Pascal/Delphi. Em 2002, ingressei no curso de Ciência da Computação, onde tive contato com Java (JSP para web e outras funcionalidades da linguagem).

---

## Consórcio Odebrecht + Via Engenharia — Assistente Técnico de TI (Ago/2005 – Dez/2008)

O consórcio formado pela Construtora Norberto Odebrecht e Via Engenharia era responsável pela implantação do novo sistema aeroportuário de Goiânia (novo terminal de passageiros, pátio de aeronaves, estacionamento e acesso viário).

### Infraestrutura de TI

Responsável pelo suporte a ~50 usuários administrativos do canteiro de obras e pela administração de toda a infraestrutura de TI. O CPD era composto por:

- Servidores Active Directory e servidor de arquivos
- Link dedicado com roteador Cisco e firewall Juniper
- Conexão com datacenter em São Paulo

**Atividades principais:**
- Administração de servidores e rotinas de backup
- Criação e gestão de GPOs, mapeamento de unidades de rede
- Criação e manutenção de usuários/grupos no Active Directory
- Rotinas de atualização de máquinas e verificações de segurança (antivírus centralizado TrendMicro)
- Manutenção de regras de firewall
- Administração do sistema de telefonia e implantação de sistema de tarifação de chamadas
- Aplicação de políticas de segurança corporativa
- Análise e planejamento de alocação de recursos tecnológicos (TCO / ROI)
- Gerenciamento da rede com foco em redução de custos de telefonia
- Criação de procedimentos para segurança, integridade e confidencialidade das informações

### Desenvolvimento de Sistema de Ponto Eletrônico (2006)

Desenvolvimento de sistema de Ponto Eletrônico em **Delphi + Firebird** (arquitetura client/server com DataSnap). O sistema:

- Capturava dados de coletores de dados/portais
- Analisava marcações e tratava ocorrências (faltas, atrasos, horas extras)
- Distribuía verbas e gerava relatórios de folha de ponto
- Gerava arquivos para integração completa com o sistema de Folha de Pagamento

O sistema também incluía um **módulo de acompanhamento e apropriação de serviços**, responsável pela quantificação dos custos da obra, rateio nas UAs corretas, apropriação de serviços de terceirizados e geração de índices de custo para planejamento.

### Integração com SISENG (2007)

Desenvolvimento de integração com o SISENG (sistema de orçamentação, acompanhamento e planejamento em Engenharia Civil). Para viabilizar a integração:

- Criação de WebService de integração
- Migração do banco de dados de **Firebird para Oracle** (maior escala, alinhando com a base já usada pelo SISENG)

### Apoio a Outras Unidades de Negócio (2008)

Em 2008, início de demanda para apoiar outras unidades nas cidades de São Caetano/SP, Campinas/SP, Dom Pedrito/RS, Natal/RN e Salvador/BA, com o objetivo de treinar os responsáveis locais de TI para manter o padrão corporativo.

**Atividades desenvolvidas nos contratos:**
- Padronização do ambiente de TI
- Aplicação de políticas de segurança corporativa
- Qualificação do recurso de TI local
- Identificação de recurso local para atuação com TI nos contratos
- Análise técnica e reestruturação do ambiente de TI
- Mobilização e logística de telecomunicação
- Adequação dos recursos tecnológicos para implantação do sistema O2

---

## Construtora Odebrecht (Holding) — Treinamentos e Apoio (Dez/2008 – Fim de 2009)

Em dezembro/2008, saída do consórcio e transferência para a holding Construtora Odebrecht para realizar os treinamentos, mantendo os apoios nas unidades até o final de 2009.

---

## Transição para Desenvolvimento Mobile (2010 – 2017)

### Estudos e Preparação (2010 – 2011)

Acompanhando o surgimento do mercado mobile (iPhone, Android, BlackBerry, Palm OS), início dos estudos de desenvolvimento mobile: **Android com Java** e **iOS com Objective-C**. Neste período, Delphi foi gradualmente deixado de lado em favor de Java, que se mostrava mais alinhado ao mercado corporativo.

### Primeiros Projetos Mobile (2012 – 2013)

**Aplicativo de Rádio Online (2012):**
Primeiro ciclo completo de desenvolvimento mobile, nas plataformas iOS e Android, com publicação nas lojas. O app oferecia:
- Transmissão online da emissora de rádio
- Agenda de comércios locais ("lista telefônica") em parceria com a CDL de Bela Vista de Goiás
- Banco de dados local (SQLite) com atualização online, filtros por segmento e nome de estabelecimento
- Arquitetura: **MVP**

**App Interno de Previdência Privada da Odebrecht (2012 – 2013):**
Participação no desenvolvimento do aplicativo interno de previdência privada para iOS e Android. Arquitetura: **MVP**.

### Adoção do Swift e Foco em iOS (2014 – 2017)

Em 2014, a Apple lançou o Swift. As primeiras versões foram acompanhadas sem adoção imediata, mantendo Objective-C. A partir do **Swift 4 (2017)**, com maior maturidade da linguagem, iniciou-se a adoção, incluindo a criação das primeiras *bridges* entre Objective-C e Swift.

Em **setembro/2017**, deixou-se de atuar com serviços de infraestrutura, passando a focar exclusivamente em desenvolvimento.

---

## MoveJa Tecnologia — Desenvolvedor iOS/Android · PJ (Out/2017 – Jun/2018)

Convite para participar de uma startup de plataforma de transporte particular de passageiros (estilo Uber).

**Missão inicial:** migrar o aplicativo MVP desenvolvido em Cordova/JavaScript para tecnologia nativa (iOS em Swift, Android em Java), para suportar geolocalização, notificações e outros serviços de forma mais eficaz.

**Principais resultados:**
- Identificação e correção de falhas graves de segurança que permitiam fraudes ("viagens fake") → **redução de 35–40% nas ocorrências** já nas primeiras versões
- Melhora nas avaliações nas lojas
- Adoção da arquitetura **MVVM** com inclusão de testes unitários (XCTest), inexistentes na versão inicial
- Uso de Google Maps + Directions para geolocalização/endereços; estratégia de cache resultou em **redução de até 55% no consumo das APIs do Google**

Entre abril e maio/2018, com alta carga de trabalho e busca por novos talentos para a startup (participação em eventos de tecnologia na Supera Tecnologia), ao final de maio saiu da MoveJa para realizar freelances na Supera, buscando rotina menos estressante.

---

## Supera Tecnologia — Desenvolvedor Full Stack / Mobile · CLT (Ago/2018 – Jul/2020)

Atuação nas plataformas Android e iOS, com maior foco em iOS. A empresa atendia múltiplos clientes, com trabalho predominante em sustentação e correção de bugs.

**Principais projetos:**

- **RMTC Goiânia** — Apps SiMRmtc (Android/iOS) e RMTC Goiânia: localização de ônibus em tempo real, planejamento de rotas, consulta de pontos de recarga Sitpass, alertas de chegada e atendimento virtual.
- **ValeCard Benefício** — App para usuários de cartões de alimentação, refeição e convênio: desbloqueio de cartões, alteração de senha e busca de estabelecimentos no mapa.
- **ValeCard Motorista** — App para motoristas que utilizam cartões de abastecimento ValeCard.
- **ValeCard Bank** — Solução de conta digital da ValeCard.
- **Rapidili** — App que conecta usuários a distribuidores de bebidas para compra online.

Em jul/2020, encerrou-se o ciclo na Supera. Decisão de focar exclusivamente em iOS, deixando de desenvolver para Android e backend (mantendo acompanhamento do mercado com Kotlin e Java/Spring Boot).

---

## Try Consultoria — Desenvolvedor iOS · PJ Remoto (Jul/2020 – Out/2020)

Contrato com tempo definido. Projeto: **Design System do Banco Santander**.

- Desenvolvimento de componentes UIKit reutilizáveis a partir das definições no Figma
- Elaboração da documentação de uso dos componentes
- Criação de biblioteca de componentes com **Swift Package Manager (SPM)**, facilitando reuso em múltiplos projetos
- Escrita de **unit tests (XCTest)** para garantir consistência visual e comportamental dos componentes no iOS SDK

---

## E-Deploy — Desenvolvedor iOS · App de Consultoras (Natura) · PJ

A E-Deploy é uma empresa brasileira de tecnologia especializada no desenvolvimento de soluções para gestão empresarial com foco em varejo.

- Sustentação e evolução do iOS app Natura para rede de mais de **1 milhão de consultoras**
- Garantia de estabilidade com **Crashlytics** e ciclos de hotfix via TestFlight
- Migração progressiva de módulos legados de **Objective-C para Swift**, reduzindo crashes
- Evolução da qualidade com arquitetura **MVVM** e **VIPER**

---

## Hexacta — Desenvolvedor iOS Sênior · squad Open Finance (Banco Modal) · PJ

Desenvolvimento de módulos iOS nativos para o projeto de Open Finance do Banco Modal.

**Stack e arquitetura:** Swift, UIKit, **MVVM-C**, **RxSwift**, integração com REST APIs e fluxos de consentimento.

**Padrões do projeto:**
- Sem adição de novas bibliotecas/dependências externas ao banco
- Padrão **RxSwift** em vez de callbacks (evitar aninhamentos); uso de delegates nos demais casos
- Todos os observables vinculados a um `DisposeBag()` e desalocados ao fim do uso
- Variáveis de `DisposeBag` privadas, sem acesso externo à classe original

A atuação foi focada na criação de UI. O fluxo de consentimento iniciava na web e derivava para o mobile via **deepLink** (cruzamento de canal).

Em janeiro/2022, foi comunicada a fusão do Banco Modal com o Grupo XP via troca de ações. Em **março/2022**, finalizou-se a prestação de serviços PJ.

---

## Zup Innovation — Mobile Developer Specialist · App Bancário (Itaú) · CLT (Mar/2022 – Fev/2026)

### Fase 1 – Squad de Prevenção a Fraudes (início em Mar/2022)

Alocado na squad de prevenção a fraudes no app **itauCartões** (projeto em estado monolítico). Função principal: desenvolvimento e sustentação/correção de bugs.

### Fase 2 – Squad Login Unificado

A squad foi desmembrada para formar a frente de acesso "Login Unificado". Desenvolvimento **do zero** de um novo módulo desacoplado:

- **Arquitetura:** ViewCode full + MVVM-C + testes unitários
- **Objetivo:** permitir que clientes utilizassem o CPF como forma de login único nos aplicativos do banco (cada app utilizava logins separados anteriormente)

### Fase 3 – Projeto One Itaú (2023 – 2026)

Em 2023, o banco iniciou o projeto **One Itaú** (anunciado ao público em 2024). Foi definida a criação de um novo módulo de identidade e segurança, contemplando:

- Criação de senha de acesso e senha transacional
- FIDO, geolocalização, dispositivo autorizado
- Validação de biometria facial

**Decisão técnica:** houve conflito inicial entre uso de WebView ou desenvolvimento nativo. Apoio ao tech lead na elaboração de documentação justificando o desenvolvimento nativo, com critérios de segurança como ponto principal.

**Padrões e qualidade do módulo:**
- MVVM-C, ViewCode, SwiftLint completo
- Testes unitários com cobertura mínima de 75% (XCTest), aplicando TDD e padrões Strategy, Builder e Coordinator
- Validações de acessibilidade (WCAG)
- Etapas completas de SonarQube, SAST e análise com Veracode
- Uso extensivo do Design System do Itaú

**Observabilidade:**
- Instrumentação com **AppDynamics** e **Crashlytics**, com alertas proativos e redução no MTTR de incidentes em produção

**CI/CD:**
- Inclusão de etapas de code review automático via agente StackSpot
- Agente de validação de acessibilidade WCAG

**Impacto:**
- O módulo possibilitou a migração dos clientes das contas **iti** e usuários do app **itauCartões** para o superApp Itaú, atingindo mais de **5 milhões de clientes**
- Em início de 2026, o módulo já estava em preparação para a próxima migração dos usuários do **Magalu Cartões**

**Rotina diária:**
- Desenvolvimento de features
- Code review de features de outros devs
- Criação de testes unitários
- Geração de versões para testes manuais (QAs) e testes automatizados
- Elaboração de documentos de gestão de mudanças para aprovação antes das versões de loja
- Acompanhamento da liberação nas lojas e validação da integração
- Responsável pelo fechamento de versão (release) do módulo
