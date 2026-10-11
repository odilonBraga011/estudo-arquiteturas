# Roadmap de 52 semanas — 14 horas por semana

**Período:** 12/10/2026 a 10/10/2027. **Regra:** cada semana fecha com uma entrega observável e revisão. Avance por competência, não apenas por calendário.

| Semana | Tema | Evidência prática |
|---|---|---|
| 01 | Diagnóstico; requisitos funcionais e atributos de qualidade | Diagnóstico inicial, requisitos e trade-offs |
| 02 | Complexidade, Big-O, estruturas de dados | Benchmarks e solução de 5 desafios |
| 03 | Algoritmos, recursão e concorrência | Testes e comparação de estratégias |
| 04 | Redes: TCP/IP, DNS, HTTP e TLS | Traçar uma requisição, diagrama e experimento |
| 05 | SO, memória, processos, threads, I/O | Laboratório de contenção e perfilamento |
| 06 | SOLID, coesão e acoplamento | Refatorar um caso com testes |
| 07 | Design patterns: criação, estrutura e comportamento | Comparar implementação com e sem padrão |
| 08 | Refatoração, code smells e legibilidade | PR documentado e decisão técnica |
| 09 | Modelagem de domínio e linguagem ubíqua | Event storming e glossário |
| 10 | DDD: entidades, VOs, agregados, invariantes | Modelo com testes de domínio |
| 11 | DDD: bounded contexts e context map | Context map e contratos |
| 12 | Arquitetura hexagonal, clean, onion e camadas | Mesmo caso implementado com ports/adapters |
| 13 | Revisão e projeto 1: decisão arquitetural | ADR + diagrama C4 + demo |
| 14 | Arquitetura de monólito modular e modularidade | Fronteiras verificadas em testes |
| 15 | APIs: REST, contratos, versionamento, erros | OpenAPI + testes de contrato |
| 16 | Event-driven, pub/sub e integração síncrona/assíncrona | Experimento com mensagens |
| 17 | CQRS, outbox e idempotência | Consumo duplicado sem efeito duplicado |
| 18 | SQL, normalização e índices | EXPLAIN ANALYZE com medições |
| 19 | Transações, isolamento, locks, MVCC | Demonstração de anomalias |
| 20 | NoSQL, Redis, cache e invalidação | Medir hit ratio e latência |
| 21 | Modelagem para escala e evolução de schemas | Migração reversível e testes |
| 22 | Filas, streams, retry, DLQ e backpressure | Processador tolerante a falhas |
| 23 | Consistência, replicação e consenso (conceitos) | Simulação de atrasos/partições |
| 24 | Sistemas distribuídos: timeouts, circuit breakers | Testes com falhas injetadas |
| 25 | System design: estimativas e gargalos | Design de feed/URL shortener com cálculos |
| 26 | Revisão e projeto 2 | Arquitetura comparativa com testes de carga |
| 27 | Testes unitários, integração, contrato e E2E | Pirâmide de testes no projeto |
| 28 | TDD, property-based e mutation testing | Avaliação de eficácia dos testes |
| 29 | Segurança: ameaça, autenticação e autorização | Threat model STRIDE |
| 30 | OWASP Top 10 e segurança de APIs | Corrigir falhas de laboratório |
| 31 | Criptografia aplicada, secrets, identidade, OAuth/OIDC | Fluxos e checklist auditável |
| 32 | Container, imagens, redes, Docker Compose | Ambiente reprodutível |
| 33 | CI/CD, GitHub Actions e qualidade | Pipeline test/build/scan |
| 34 | Kubernetes e orquestração | Deployment, health probes e rollback |
| 35 | Infra como código e ambientes | Plano IaC (sem deploy pago obrigatório) |
| 36 | Cloud e Well-Architected, custos/FinOps | Trade-offs cloud vs on-prem |
| 37 | Observabilidade: logs, métricas, traces | Dashboard e tracing distribuído |
| 38 | SRE: SLI, SLO, erro budget e incidentes | SLO e runbook |
| 39 | Revisão e projeto 3 | Demo com falha controlada e postmortem |
| 40 | Performance: profiling, CPU, memória e GC | Baseline e melhoria mensurada |
| 41 | Engenharia de capacidade e testes de carga | Relatório p95/p99 e limites |
| 42 | Resiliência: chaos engineering e recuperação | Plano de falhas e restore ensaiado |
| 43 | Evolução arquitetural e strangler fig | Plano de migração incremental |
| 44 | Padrões avançados: saga, workflow, compensação | Orquestração vs coreografia |
| 45 | Sistemas em tempo real, websockets e eventos | Prova de conceito em tempo real |
| 46 | Arquitetura frontend, estado e contratos | Fronteiras e teste de frontend |
| 47 | Arquitetura mobile/offline-first | Estratégia de sincronização |
| 48 | Engenharia de dados e sistemas analíticos | ETL simples + modelo |
| 49 | Arquitetura organizacional, Conway, governança | RFC de padrão arquitetural |
| 50 | Comunicação, liderança, trade-offs e ADRs | Apresentação com objeções |
| 51 | Projeto final: arquitetura end-to-end | C4, ADRs, código, testes e SLO |
| 52 | Revisão e banca simulada | Portfólio, pontos fracos e plano seguinte |

## Critérios para avançar
1. Consigo explicar o problema **sem consultar material**?
2. Sei dar um exemplo de quando **não** usar a técnica?
3. Implementei e testei ao menos um cenário?
4. Consigo defender a escolha com custos e consequências?
5. Registrei a evidência (commit, ADR, diagrama, benchmark)?

**Se dois ou mais itens forem “não”, repetir/aprofundar a semana.**

## Rotação diária
Segunda: conceitos e exercícios de recordação. Terça: código. Quarta: padrões e modelagem. Quinta: dados/sistemas e benchmarks. Sexta: testes/segurança/operação. Sábado: projeto integrador. Domingo: revisão + retrospectiva.

**Temas de aprofundamento após o primeiro ano:** compiladores, teoria de linguagens e tipos, sistemas operacionais avançados, consenso formal, sistemas embarcados, IA/ML systems, privacy engineering, fintech, arquitetura de dados em escala, sistemas críticos, liderança/staff+ e arquitetura corporativa.
