# Primeiro ciclo — 30 dias (12/10 a 10/11/2026)

**Estrutura diária:** 10 min recordação + 30 min estudo + 60 min prática + 15 min revisão + 5 min commit/planejamento.

## Semana 1: requisitos e fundamentos de arquitetura
- **D01 (12/10):** diagnóstico (10 perguntas); definir projeto piloto; escrever requisitos funcionais e não funcionais.
- **D02:** qualidade: performance, confiabilidade, escalabilidade, manutenibilidade, segurança; exemplos mensuráveis.
- **D03:** restrições e trade-offs; classificar requisitos por prioridade.
- **D04:** arquiteturas em camadas, modular, hexagonal; escolher uma e explicar exclusões.
- **D05:** C4 nível 1 (contexto) e nível 2 (containers); desenhar fluxo.
- **D06:** implementar um endpoint mínimo + testes + README.
- **D07:** revisão da semana, 15 questões de memória, ADR-0001 e retrospectiva.

## Semana 2: algoritmos e estruturas de dados
- **D08:** notação Big-O; comparar buscas lineares e binárias.
- **D09:** arrays, listas e mapas; decisões por carga.
- **D10:** pilhas, filas, prioridades; implementar fila e testes.
- **D11:** árvores e hashes; resolver 2 problemas.
- **D12:** ordenação e custo de memória; benchmark local.
- **D13:** resolver 3 exercícios sem IA, depois obter code review.
- **D14:** escrever comparativo de complexidade e refazer erros.

## Semana 3: algoritmos e concorrência
- **D15:** recursão, programação dinâmica e memoização.
- **D16:** grafos BFS/DFS com casos de teste.
- **D17:** processos e threads; experimento simples.
- **D18:** race conditions, locks e deadlocks; demonstrar falha.
- **D19:** concorrência, imutabilidade e estruturas thread-safe.
- **D20:** mini-laboratório: fila de tarefas com concorrência e métricas.
- **D21:** revisão semanal, questões conceituais e diário.

## Semana 4: redes e protocolos
- **D22:** camadas TCP/IP e ciclo de resolução DNS.
- **D23:** HTTP: verbos, códigos, idempotência, cabeçalhos.
- **D24:** TLS e autenticação de transporte; captura segura local.
- **D25:** conexão, timeout, retry, backoff; experimento.
- **D26:** caching HTTP, ETag e CDN (conceitos e demonstração).
- **D27:** trace de uma requisição ponta a ponta.
- **D28:** revisão, desenho de sequência, teste aplicado.

## Dias 29 e 30
- **D29 (09/11):** avaliação integradora (requisitos + algoritmo + redes + refatoração).
- **D30 (10/11):** revisão de progresso, atualizar habilidades, planejar mês 2.

## Definition of Done de cada dia
- [ ] 120 minutos dedicados (ou reagendar sem fingir conclusão)
- [ ] Explicação própria (5–10 linhas)
- [ ] Experimento/solução/artefato verificável
- [ ] Ao menos 1 teste ou pergunta crítica
- [ ] Commit ou registro de impedimento

## Diagnóstico inicial (responda sem pesquisar)
1. O que distingue arquitetura de design de código?
2. Quando usar monólito modular em vez de microsserviços?
3. O que é coesão e como medir sintomas de baixo acoplamento?
4. Qual a diferença entre consistência forte e eventual?
5. O que é idempotência em uma API?
6. Como investigar p99 de latência?
7. Como definir SLO e error budget?
8. Como identificar deadlock?
9. O que deve constar num ADR?
10. O que significa uma migração sem downtime?

Avalie cada resposta: 0 (não sei), 1 (parcial), 2 (explico e aplico). Guarde a pontuação inicial; reavalie após 90 dias.
