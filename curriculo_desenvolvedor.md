# Mateus Andriola
**Engenheiro de Software Full-Stack & Sistemas Distribuídos**
📍 Paraná, Brasil | 🌐 [github.com/mateus-andriola](https://github.com/mateus-andriola) | 💼 [linkedin.com/in/mateusandriola](https://linkedin.com/in/mateusandriola)
📧 mateusandriola18@gmail.com | 📞 +55 (41) 9 8438-7343

---

## 1. Resumo Executivo & Perfil Técnico

Engenheiro de Software Full-Stack com sólida experiência em arquitetura de sistemas distribuídos, desenvolvimento de plataformas web/mobile de alta performance e engenharia cloud-native. Especialista no ecossistema **TypeScript/JavaScript** (React, Next.js, NestJS), **Go**, **Elixir/Phoenix** e **Rust**, aliado a um profundo conhecimento em bancos de dados relacionais (**PostgreSQL**, **Oracle DB**) e orquestração de contêineres (**Kubernetes**, **Docker**, **AWS**).

Comprovada capacidade de projetar soluções de grande escala, otimizar pipelines de processamento massivo de dados (redução de 75% no tempo de execução de consultas SQL complexas) e sustentar ambientes com alta concorrência (+100.000 requisições concorrentes sem escalabilidade horizontal). Atuação pragmática com foco em Clean Architecture, Domain-Driven Design (DDD), Micro-frontends e desenvolvimento de ferramentas internas de engenharia de software (como parsers SQL e geradores automáticos de query binds).

---

## 2. Principais Destaques de Engenharia & Impacto

- **Alta Concorrência & Performance**: Projetou e otimizou serviços backend e pipelines assíncronos que sustentaram mais de **100.000 requisições concorrentes** em plataforma de saúde multi-tenant sem necessidade de escalabilidade horizontal.
- **Otimização Extrema de Banco de Dados**: Liderou a refatoração e otimização de rotinas SQL para criação massiva de pedidos, aumentando a capacidade de processamento de **5.000 para 180.000 itens**, reduzindo o tempo total de execução em **75%**.
- **Arquitetura de Plataforma Multi-Tenant**: Atuou na transição arquitetural de sistemas isolados legados (ASP.NET) para ecossistemas modernos descentralizados com **Next.js**, **NestJS** e **Micro-Frontends**.
- **Engenharia de Plataforma SaaS Cloud-Native**: Construiu do zero e manteve plataforma SaaS de ensino e streaming de vídeo escalável utilizando **React** e **AWS Amplify**, atendendo milhares de alunos ativos.
- **Análise Empírica de Código (GitHub/Graphify)**: Mais de **160.000 linhas de código** autorais distribuídas em 64 repositórios analisados via parseamento AST (Graphify), cobrindo desde concorrência em Go/Elixir até controladores de mídia em Rust e parsers SQL em TypeScript.

---

## 3. Matriz de Qualificação Técnica

### 3.1 Engenharia Frontend & Micro-Frontends (Peso 10/10)
- **Linguagens & Frameworks**: TypeScript, JavaScript (ES6+), React 18/19, Next.js (App Router & Pages Router), HTML5, CSS3, Tailwind CSS, Chakra UI, Radix UI.
- **Arquitetura Frontend**: Micro-frontends (arquitetura desacoplada via componentes remotos e roteamento dinâmico), Server-Side Rendering (SSR), Static Site Generation (SSG), Incremental Static Regeneration (ISR).
- **Gerenciamento de Estado & Data Fetching**: React Query / TanStack Query, Zustand, Redux Toolkit, Context API, SWR.
- **Evidências em Código (Projetos)**: `micro-frontends-main`, `micro-frontends-counter`, `dashgo`, `reactjs-infinite-carousel` (componente reutilizável de carrossel infinito), `next-saas-rbac`, `nlw-agents-web`.

### 3.2 Backend, APIs & Microserviços (Peso 10/10)
- **Linguagens & Frameworks**: Go, TypeScript (NestJS, Express, Fastify), Elixir (Phoenix Framework), Node.js.
- **Design de APIs & Comunicação**: RESTful APIs (Swagger/OpenAPI), GraphQL, WebSockets, gRPC, JSON-RPC.
- **Padrões de Projeto**: Clean Architecture, Hexagonal Architecture, Domain-Driven Design (DDD), Dependency Injection, Middleware Pattern, RBAC (Role-Based Access Control).
- **Evidências em Código (Projetos)**: `access_managment` (Gestão de papéis e permissões em Elixir), `sql_constructor` (Query builder autor em Node.js/TS), `nlw-agents-server`, `bossaBoxAPIChallenge`, `Wabanex-nlw6`.

### 3.3 Sistemas Concorrentes, Distribuídos & Sistemas de Baixo Nível (Peso 9/10)
- **Elixir / OTP**: Modelo de Atores, Processos Isolados, GenServer, Supervision Trees, Phoenix Channels, Ecto. Excelente capacidade de construir sistemas tolerantes a falhas e assíncronos.
- **Go (Golang)**: Goroutines, Channels, Mutexes, Interfaces implícitas, estruturas de alto desempenho e APIs HTTP concorrentes.
- **Rust & C++**: Gerenciamento de memória e concorrência segura em Rust (Cargo), estruturas de dados avançadas e algoritmos em C++.
- **Evidências em Código (Projetos)**: `access_managment` (Elixir/OTP), `nlw-heat` (Elixir), `rocketpay` (Elixir), `project_navigator` (Go), `go_beecrowd_challenges` (Go), `media-player-controller` (Rust - controlador Spotify via IPC), `CppChallenges` (C++).

### 3.4 Bancos de Dados, ORMs & Otimização SQL (Peso 9/10)
- **Bancos de Dados Relacionais & NoSQL**: PostgreSQL, Oracle Database, MySQL, SQLite, Redis, MongoDB.
- **ORMs & Query Builders**: Prisma ORM, Ecto (Elixir), TypeORM, Knex.js, e desenvolvimento de **Query Builders customizados**.
- **Habilidades em Banco de Dados**: Indexação avançada, análise de planos de execução (`EXPLAIN ANALYZE`), prevenção de Deadlocks, otimização de CTEs, queries em lote e construção de queries SQL com binds parametrizados automáticos.
- **Evidências em Código (Projetos)**: `sql_constructor` (Projeto Node.js/TS para construção de queries SQL e geração automática de binds), `spending_plan`, `ecolink-mvp`.

### 3.5 Desenvolvimento Mobile (Peso 8/10)
- **Tecnologias**: React Native, Expo, Java Android Nativo, React Navigation.
- **Recursos**: Geolocalização em tempo real, armazenamento local, componentes nativos, consumo de APIs REST/WebSockets em conexões móveis.
- **Evidências em Código (Projetos)**: `APPEntregas` (App de rotas de entregas com geolocalização em TS/RN), `lista-de-compras-rn`, `Lista-de-Compras` (Java Android nativo para cálculo de compras no mercado).

### 3.6 Cloud Native, DevOps & Infraestrutura (Peso 9/10)
- **Orquestração & Conteinerização**: Kubernetes (Deployments, Services, Ingress, ConfigMaps, Helm), Docker, Docker Compose.
- **Cloud Providers**: AWS (Amplify, S3, EC2, ECS, Lambda, IAM).
- **CI/CD & Observabilidade**: GitHub Actions, Docker Registry, Logs estruturados, testes de carga e monitoramento de saúde de serviços.
- **Evidências em Código (Projetos)**: `amplify-next-template`, `amplify-test`, manifestos Docker/K8s em múltiplos repositórios.

---

## 4. Experiência Profissional

### **Pangaea Healthcare** | Engenheiro de Software Full-Stack / Plataforma
*Fevereiro 2025 – Junho 2026* | **Stack**: Next.js · React · Go · Kubernetes · PostgreSQL · Docker
- Atuou no desenvolvimento de aplicações full-stack e serviços de plataforma orientados a alta concorrência.
- Projetou e implementou a transição arquitetural de um produto isolado de gestão de sinistros médicos para um ecossistema de saúde multi-tenant e multiaplicação.
- Desenvolveu microserviços em Go e pipelines assíncronos de alta capacidade para processamento de fluxos de dados de saúde em larga escala.
- Implementou otimizações de desempenho que permitiram à plataforma sustentar mais de **100.000 requisições concorrentes** sem necessidade de escalabilidade horizontal.
- Operou e manteve serviços cloud-native em clusters Kubernetes, aprimorando a confiabilidade operacional e a padronização de deploys.

### **Tok&Stok** | Engenheiro de Software Full-Stack
*Janeiro 2022 – Fevereiro 2025* | **Stack**: Next.js · React · NestJS · Oracle Database · Docker · TypeScript
- Desempenhou papel estratégico na modernização do ecossistema de software do varejo, migrando sistemas legados monolíticos ASP.NET para uma arquitetura moderna descentralizada com Next.js e NestJS.
- Desenvolveu módulos full-stack para gestão de compras de produtos, logística e gestão de distribuição de estoque.
- Liderou engenharia de consultas SQL sobre Oracle Database: reescreveu e indexou procedimentos e rotas de banco de dados para criação massiva de pedidos, aumentando o throughput de **5.000 para 180.000 itens** por operação, reduzindo em **75%** o tempo de execução.
- Implementou padronização de conteinerização com Docker e CI/CD para acelerar o ciclo de entrega de novas funcionalidades aos times de negócio.

### **Pato Academy** | Engenheiro de Software Full-Stack (SaaS)
*Julho 2021 – Março 2023* | **Stack**: React · AWS Amplify · JavaScript/TypeScript · Node.js · GraphQL/REST
- Desenvolveu do zero a plataforma SaaS de ensino e treinamento em cibersegurança para o criador Gabriel Pato.
- Arquitetou funcionalidades essenciais incluindo streaming de conteúdo de vídeo, controle de acesso, gestão de turmas, autenticação e transmissões ao vivo.
- Utilizou ecossistema AWS Amplify para fornecer infraestrutura serverless escalável e de baixa manutenção.
- Manteve e evoluiu a plataforma continuadamente por quase 2 anos, suportando o crescimento de milhares de alunos com alta disponibilidade.

---

## 5. Catálogo de Projetos do GitHub Categorizados (Análise via Graphify)

Abaixo estão listados os projetos de destaque do ecossistema autoral, extraídos e analisados com parseamento AST e grafos de dependência via **Graphify**:

```carousel
### 1. Ferramentas de Engenharia & Query Engines
- **sql_constructor** (TypeScript | Node.js | SQL)
  - *Descrição*: Lib/ferramenta autor para construção dinâmica de queries SQL complexas com geração automática de binds parametrizados, prevenindo SQL Injection e otimizando reuso de código.
  - *Métricas*: Parser de AST SQL, utilitários de construção de cláusulas WHERE/JOIN dinâmicas.

<!-- slide -->

### 2. Arquitetura de Sistemas Distribuídos & Concorrência
- **access_managment** (Elixir | OTP | Ecto)
  - *Descrição*: Sistema de gestão de acesso baseado em papéis (RBAC) construído em Elixir/OTP, utilizando modelo de atores para garantir consistência e isolamento.
- **project_navigator** (Go | Systems)
  - *Descrição*: Aplicação de navegação e inspeção de projetos desenvolvida em Go, focada em alta performance de leitura no sistema de arquivos.
- **media-player-controller** (Rust | Systems)
  - *Descrição*: Controlador de reprodução de mídia do Spotify desenvolvido em Rust, com comunicação IPC de baixo nível e uso eficiente de memória.

<!-- slide -->

### 3. Arquitetura Micro-Frontends & Frontend de Alta Complexidade
- **micro-frontends-main** & **micro-frontends-counter** (Next.js | React | CSS)
  - *Descrição*: Arquitetura de Micro-Frontends demonstrando desacoplamento de aplicações web, onde um shell principal Next.js consome e orquestra micro-aplicações isoladas de forma dinâmica.
- **reactjs-infinite-carousel** (TypeScript | React)
  - *Descrição*: Componente React para criação de carrosséis infinitos com tamanho ajustável, publicado e otimizado para reutilização de UI.
- **nlw-agents-web** & **nlw-agents-server** (TypeScript | Next.js | Tailwind CSS)
  - *Descrição*: Aplicação web e servidor backend orientados a agentes inteligentes de IA, integrando interfaces reativas moderníssimas com server-side rendering.

<!-- slide -->

### 4. Aplicações Mobile & Engenharia Nativa
- **APPEntregas** (TypeScript | React Native)
  - *Descrição*: Aplicativo mobile completo para roteamento e gerenciamento de entregas com geolocalização e cálculo dinâmico de trajetos.
- **Lista-de-Compras** (Java | Android Nativo)
  - *Descrição*: Aplicativo nativo em Java Android para cálculo automatizado e em tempo real do valor de compras de supermercado.

<!-- slide -->

### 5. Backend APIs, Autenticação & Desafios de Engenharia
- **next-saas-rbac** (TypeScript | Next.js | Prisma ORM)
  - *Descrição*: Boilerplate completo de arquitetura SaaS com autenticação, multi-tenant e controle de acesso baseado em papéis (RBAC).
- **rinha** (TypeScript | Fastify | Docker)
  - *Descrição*: Submissão para a Rinha de Backend, focada em alta taxa de transferência (throughput) e baixa latência de I/O em ambientes conteinerizados.
- **bossaBoxAPIChallenge** & **bossaBoxChallengeElixir** (TypeScript / Elixir)
  - *Descrição*: APIs REST para gerenciamento de ferramentas de desenvolvedores, implementadas em TypeScript (Node) e em Elixir (Phoenix), demonstrando versatilidade entre ecossistemas.
```

---

## 6. Resumo Numérico dos Repositórios (Métricas Graphify)

| Categoria Principal | Total de Repositórios | Tecnologias Chave | Métricas de Código Destacadas |
| :--- | :---: | :--- | :--- |
| **Frontend & Web Applications** | 24 | React, Next.js, TypeScript, Tailwind | Componentização modular, SSR/SSG, State Mgmt |
| **Backend APIs & Microserviços** | 8 | NestJS, Express, Go, Phoenix | REST, WebSockets, Clean Arch, RBAC |
| **Sistemas Concorrentes (Elixir/Go)** | 11 | Elixir, OTP, Go Modules | Modelo de atores, Goroutines, Canais assíncronos |
| **Mobile App Development** | 4 | React Native, Java Nativo | Geolocalização, consumo de APIs, UX Mobile |
| **Micro-Frontends & Componentes Lib** | 3 | Next.js, React Component | Desacoplamento remoto, Carrossel Infinito, UI Libs |
| **Sistemas de Baixo Nível / Tooling** | 3 | Rust, C++, TypeScript Parser | IPC, Rust Cargo, Algoritmos C++, Query Builder |
| **Outros / Automações / Protótipos** | 11 | Python, HTML, CSS Animations | Scripts de automação, estudos de animação |
| **TOTAL GERAL** | **64** | **TypeScript, Go, Elixir, Rust** | **161.999 Linhas de Código Analisadas** |

---

## 7. Formação Acadêmica

**Bacharelado em Ciência da Computação**  
*Universidade Cruzeiro do Sul* | Julho 2023 – Em Andamento  
Foco em Algoritmos, Estrutura de Dados, Engenharia de Software, Redes de Computadores e Sistemas Operacionais.
