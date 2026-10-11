# Projetos práticos e portfólio

## Projeto A — Monólito modular de negócio (semanas 1–14)
**Problema:** sistema de gestão com múltiplas unidades, usuários, produtos/recursos e transações.
**Sugestão tecnológica:** Java + Spring Boot, PostgreSQL, Docker, testes automatizados.
**Incrementos:** API mínima → invariantes de domínio → módulos → persistência → segurança → documentação C4/ADRs → pipeline.
**Experimentos:** mudar regra de negócio sem alterar infraestrutura; comparar abordagem em camadas vs hexagonal; medir custo dos testes.
**Entrega:** aplicação executável, testes, ADR-0001, C4 e relatório trade-offs.

## Projeto B — Pedidos/eventos com integração assíncrona (semanas 15–26)
**Problema:** pedido/convite e notificação, com APIs e eventos.
**Incrementos:** contrato OpenAPI, idempotency-key, transações, cache, outbox, consumidor resiliente, DLQ, retries.
**Experimentos:** mensagens duplicadas e fora de ordem; serviço indisponível; consistência eventual; lock contention.
**Entrega:** diagrama de sequência, ADR de mensageria, testes de integração e relatório de cargas.

## Projeto C — Sistema observável e seguro (semanas 27–39)
**Problema:** operar os projetos A e B em ambiente reproduzível.
**Incrementos:** threat modeling, OAuth/OIDC em laboratório, pipeline CI, Docker, instrumentação OTel, métricas, logs, traces, SLO, runbook.
**Experimentos:** indisponibilidade, recuperação, carga e latência p95/p99.
**Entrega:** dashboard, scripts de carga, relatório de incidentes, checklist de segurança e CI.

## Projeto D — Banca de arquitetura (semanas 40–52)
Escolher uma demanda (ex.: plataforma de vendas/gestão, escalas de trabalho ou convites).
**Entregar:** requisitos e estimativas, análise de alternativas, diagramas C4, 4+ ADRs, APIs, modelo de dados, código mínimo funcional, testes, simulação de incidentes, custo aproximado, segurança, SLO e apresentação de 15 minutos.
**Critério:** argumentar com evidências por que usar e por que não usar cada decisão.

## Regras de portfólio
- Um projeto **não** exige microserviços para ser considerado avançado.
- Evitar credenciais e dados privados; usar fixtures sintéticas.
- Versões, comandos de execução, métricas e limitações devem estar documentados.
- Criar subdiretórios em `projetos/` conforme cada trabalho iniciar, não gerar scaffolding inútil.

## Exercícios rápidos
1. Refatore uma regra de cálculo com SOLID sem criar abstrações desnecessárias.
2. Demonstre e corrija duas requisições duplicadas que causam cobrança repetida.
3. Explique por que um índice acelera uma consulta e piora uma escrita.
4. Desenhe a quebra de consistência quando o broker cai após o commit do banco.
5. Trace uma requisição e localize 90% da latência.
6. Faça threat modeling dos fluxos de autenticação de um sistema próprio de laboratório.
