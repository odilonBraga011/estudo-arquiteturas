# Guia operacional — O que estudar a cada dia (primeiras 20 sessões)

**Agenda:** segunda a sexta, 06:00–08:00 (America/Fortaleza). **Primeira sessão:** 12/10/2026.

## Como usar
1. Às 06:00, abra **Todoist → Hoje**, selecione a tarefa da data e clique no link *Roteiro detalhado*.
2. **06:00–06:10:** responda sem consulta 2–3 perguntas do conteúdo anterior (na 1ª sessão, faça um mini diagnóstico).
3. **06:10–06:40:** use os recursos de leitura indicados **na seção daquele dia**. Não é necessário ler tudo; privilegie trechos diretamente ligados ao objetivo.
4. **06:40–07:40:** realize o experimento/exercício definido. Anote seu palpite antes de executar.
5. **07:40–07:55:** execute testes, valide resultados, escreva limitações e trade-offs.
6. **07:55–08:00:** registre no GitHub (commit/arquivo/issue) e a dúvida para amanhã.

**Regra:** a atividade só está concluída depois que houver evidência verificável. Caso a prática ultrapasse 2h, registre o progresso e continue em outra sessão em vez de marcar a tarefa indevidamente.

**Importante:** exercícios e fontes são sugestões verificáveis e gratuitas para consulta, e algumas fontes estão em inglês. Adapte o ritmo conforme o diagnóstico. `Todoist` registra o checklist; `Google Calendar` reserva o horário; `GitHub` guarda materiais e evidências.

---

## S01

**Data:** 2026-10-12 | **Título:** Diagnóstico e projeto piloto | **Semana:** 1

**O que entender (06:10–06:40):** Diferença entre arquitetura, requisitos funcionais, restrições e atributos de qualidade.

**Material:** [Azure — princípios de design](https://learn.microsoft.com/en-us/azure/architecture/guide/design-principles/) · [Roteiro diagnóstico](https://github.com/odilonBraga011/estudo-arquiteturas/blob/main/docs/PRIMEIROS-30-DIAS.md)

**O que praticar (06:40–07:40):** Responda as 10 perguntas do diagnóstico sem consulta (0–2 pontos). Escolha um sistema de laboratório (ex.: pedidos, escalas ou convites). Registre 5 requisitos funcionais, 5 de qualidade, 3 restrições e os atores.

**O que validar (07:40–07:55):** testes cobrindo pelo menos um erro/borda, explicação em linguagem própria e trade-offs. Nas primeiras sessões, aplique avaliação conceitual quando código ainda não existir.

**Entrega/critério de conclusão:** projetos/projeto-piloto/visao.md, contendo contexto, requisitos, suposições, diagnóstico com pontuação e 3 questões para revisitar.

**Vinculação:** [Issue da semana](https://github.com/odilonBraga011/estudo-arquiteturas/issues/1).

---

## S02

**Data:** 2026-10-13 | **Título:** Atributos de qualidade mensuráveis | **Semana:** 1

**O que entender (06:10–06:40):** Qualidade como cenário mensurável: latência, disponibilidade, segurança, manutenibilidade, custo.

**Material:** [AWS Well-Architected](https://aws.amazon.com/architecture/well-architected/) · [Azure — design principles](https://learn.microsoft.com/en-us/azure/architecture/guide/design-principles/)

**O que praticar (06:40–07:40):** Pegue 5 requisitos de qualidade de ontem e torne cada um testável: estímulo, ambiente, resposta, medida. Ex.: consulta com p95 < 300 ms sob 50 req/s (meta hipotética); justifique números.

**O que validar (07:40–07:55):** testes cobrindo pelo menos um erro/borda, explicação em linguagem própria e trade-offs. Nas primeiras sessões, aplique avaliação conceitual quando código ainda não existir.

**Entrega/critério de conclusão:** projetos/projeto-piloto/qualidades.md com cenários mensuráveis e prioridades (não alegar que metas já foram alcançadas).

**Vinculação:** [Issue da semana](https://github.com/odilonBraga011/estudo-arquiteturas/issues/1).

---

## S03

**Data:** 2026-10-14 | **Título:** Trade-offs de arquiteturas | **Semana:** 1

**O que entender (06:10–06:40):** Monólito em camadas, monólito modular e microsserviços; custos de rede, deploy, autonomia e testes.

**Material:** [Martin Fowler — Monolith First](https://martinfowler.com/bliki/MonolithFirst.html) · [Azure — estilos arquiteturais](https://learn.microsoft.com/en-us/azure/architecture/guide/architecture-styles/)

**O que praticar (06:40–07:40):** Compare 3 opções para o mesmo projeto numa matriz: complexidade, equipe, deploy, dados, observabilidade, custo e evolução. Escolha uma opção; formule 3 situações nas quais a escolha deixaria de valer.

**O que validar (07:40–07:55):** testes cobrindo pelo menos um erro/borda, explicação em linguagem própria e trade-offs. Nas primeiras sessões, aplique avaliação conceitual quando código ainda não existir.

**Entrega/critério de conclusão:** projetos/projeto-piloto/alternativas.md com matriz de decisão e conclusão argumentada.

**Vinculação:** [Issue da semana](https://github.com/odilonBraga011/estudo-arquiteturas/issues/1).

---

## S04

**Data:** 2026-10-15 | **Título:** Diagrama C4 | **Semana:** 1

**O que entender (06:10–06:40):** C4 nível 1 (contexto) e nível 2 (containers) e os limites entre sistemas externos e aplicação.

**Material:** [C4 Model](https://c4model.com/) · [arc42 documentação de arquitetura](https://arc42.org/)

**O que praticar (06:40–07:40):** Desenhe os usuários, sua aplicação e integrações externas (contexto); depois API, banco, frontend e dependências (containers). Use Mermaid, PlantUML ou draw.io; explique 3 decisões.

**O que validar (07:40–07:55):** testes cobrindo pelo menos um erro/borda, explicação em linguagem própria e trade-offs. Nas primeiras sessões, aplique avaliação conceitual quando código ainda não existir.

**Entrega/critério de conclusão:** projetos/projeto-piloto/arquitetura.md com 2 diagramas, legenda e explicação dos fluxos.

**Vinculação:** [Issue da semana](https://github.com/odilonBraga011/estudo-arquiteturas/issues/1).

---

## S05

**Data:** 2026-10-16 | **Título:** Endpoint, testes e ADR | **Semana:** 1

**O que entender (06:10–06:40):** Contratos HTTP, estrutura simples de aplicação, decisão arquitetural registrada em ADR.

**Material:** [Spring — Building a RESTful Web Service](https://spring.io/guides/gs/rest-service) · [ADR template do repositório](https://github.com/odilonBraga011/estudo-arquiteturas/blob/main/templates/ADR.md)

**O que praticar (06:40–07:40):** Implemente uma API mínima do projeto piloto (ex.: GET /health e POST /pedidos com validação simples) e 2 testes. Escreva ADR-0001 com alternativas. Revise a semana e identifique lacunas.

**O que validar (07:40–07:55):** testes cobrindo pelo menos um erro/borda, explicação em linguagem própria e trade-offs. Nas primeiras sessões, aplique avaliação conceitual quando código ainda não existir.

**Entrega/critério de conclusão:** Código executável, instruções de execução, 2 testes passando e ADR-0001.md.

**Vinculação:** [Issue da semana](https://github.com/odilonBraga011/estudo-arquiteturas/issues/1).

---

## S06

**Data:** 2026-10-19 | **Título:** Big-O e benchmarks | **Semana:** 2

**O que entender (06:10–06:40):** Crescimento do custo, complexidade de tempo e espaço; pior caso versus média.

**Material:** [MIT OCW — Introduction to Algorithms](https://ocw.mit.edu/courses/6-006-introduction-to-algorithms-spring-2020/) · [VisuAlgo](https://visualgo.net/en)

**O que praticar (06:40–07:40):** Implemente busca linear e binária em coleções ordenadas. Rode tamanhos 100, 10.000 e 100.000, repita as medições, registre ambiente; preveja e compare os resultados.

**O que validar (07:40–07:55):** testes cobrindo pelo menos um erro/borda, explicação em linguagem própria e trade-offs. Nas primeiras sessões, aplique avaliação conceitual quando código ainda não existir.

**Entrega/critério de conclusão:** Código, testes de borda e tabela com complexidade teórica e tempos observados; explique limitações do benchmark.

**Vinculação:** [Issue da semana](https://github.com/odilonBraga011/estudo-arquiteturas/issues/2).

---

## S07

**Data:** 2026-10-20 | **Título:** Arrays, listas e mapas | **Semana:** 2

**O que entender (06:10–06:40):** Acesso, busca, remoção e memória em arrays, listas, mapas e hash tables.

**Material:** [Exercism — Java](https://exercism.org/tracks/java) · [Oracle — Collections Framework](https://docs.oracle.com/javase/tutorial/collections/)

**O que praticar (06:40–07:40):** Resolva 2 tarefas equivalentes com ArrayList e HashMap. Para cada operação, antecipe custo; faça testes com duplicatas, entradas vazias e ausência de chave.

**O que validar (07:40–07:55):** testes cobrindo pelo menos um erro/borda, explicação em linguagem própria e trade-offs. Nas primeiras sessões, aplique avaliação conceitual quando código ainda não existir.

**Entrega/critério de conclusão:** 2 soluções com testes e uma matriz quando usar arrays, listas e mapas no projeto.

**Vinculação:** [Issue da semana](https://github.com/odilonBraga011/estudo-arquiteturas/issues/2).

---

## S08

**Data:** 2026-10-21 | **Título:** Fila, pilha e prioridade | **Semana:** 2

**O que entender (06:10–06:40):** LIFO, FIFO e heap/priority queue: propriedades e casos de uso.

**Material:** [Oracle — Java Collections](https://docs.oracle.com/javase/tutorial/collections/) · [VisuAlgo](https://visualgo.net/en)

**O que praticar (06:40–07:40):** Implemente uma pilha para desfazer operações, uma fila para pedidos e uma fila de prioridade para chamados. Inclua testes de ordem e condições vazias.

**O que validar (07:40–07:55):** testes cobrindo pelo menos um erro/borda, explicação em linguagem própria e trade-offs. Nas primeiras sessões, aplique avaliação conceitual quando código ainda não existir.

**Entrega/critério de conclusão:** 3 implementações demonstráveis, testes e descrição de complexidade das operações.

**Vinculação:** [Issue da semana](https://github.com/odilonBraga011/estudo-arquiteturas/issues/2).

---

## S09

**Data:** 2026-10-22 | **Título:** Árvores, hashing e grafos | **Semana:** 2

**O que entender (06:10–06:40):** BST, hash collisions e introdução a grafos, percursos BFS/DFS.

**Material:** [MIT OCW — Algorithms](https://ocw.mit.edu/courses/6-006-introduction-to-algorithms-spring-2020/) · [VisuAlgo](https://visualgo.net/en)

**O que praticar (06:40–07:40):** Desenhe uma árvore e um grafo de 7 nós. Implemente busca em um deles e teste caso ausente e ciclos. Compare mapa hash para lookup versus árvore ordenada.

**O que validar (07:40–07:55):** testes cobrindo pelo menos um erro/borda, explicação em linguagem própria e trade-offs. Nas primeiras sessões, aplique avaliação conceitual quando código ainda não existir.

**Entrega/critério de conclusão:** Código com testes e explicação em Markdown sobre custos e escolha das estruturas.

**Vinculação:** [Issue da semana](https://github.com/odilonBraga011/estudo-arquiteturas/issues/2).

---

## S10

**Data:** 2026-10-23 | **Título:** Ordenação e revisão | **Semana:** 2

**O que entender (06:10–06:40):** Sort baseado em comparação, estabilidade e custo assintótico; vieses em medição.

**Material:** [MIT OCW — Algorithms](https://ocw.mit.edu/courses/6-006-introduction-to-algorithms-spring-2020/) · [Exercism](https://exercism.org/tracks/java)

**O que praticar (06:40–07:40):** Compare 2 ordenações com dados aleatórios, ordenados e inversos; documente complexidade e estabilidade. Revise os 5 exercícios da semana sem olhar solução.

**O que validar (07:40–07:55):** testes cobrindo pelo menos um erro/borda, explicação em linguagem própria e trade-offs. Nas primeiras sessões, aplique avaliação conceitual quando código ainda não existir.

**Entrega/critério de conclusão:** Relatório com resultados reproduzíveis, casos de teste, 5 questões explicadas e retrospectiva.

**Vinculação:** [Issue da semana](https://github.com/odilonBraga011/estudo-arquiteturas/issues/2).

---

## S11

**Data:** 2026-10-26 | **Título:** Recursão e memoização | **Semana:** 3

**O que entender (06:10–06:40):** Caso base, stack e overlapping subproblems; recursão ingênua versus memoização.

**Material:** [MIT OCW — Algorithms](https://ocw.mit.edu/courses/6-006-introduction-to-algorithms-spring-2020/) · [Exercism — Java](https://exercism.org/tracks/java)

**O que praticar (06:40–07:40):** Faça Fibonacci ingênuo, memoizado e iterativo. Teste n=0,1 e limites razoáveis; compare tempo e memória sem confundir benchmark com prova matemática.

**O que validar (07:40–07:55):** testes cobrindo pelo menos um erro/borda, explicação em linguagem própria e trade-offs. Nas primeiras sessões, aplique avaliação conceitual quando código ainda não existir.

**Entrega/critério de conclusão:** 3 versões, testes e análise da complexidade.

**Vinculação:** [Issue da semana](https://github.com/odilonBraga011/estudo-arquiteturas/issues/3).

---

## S12

**Data:** 2026-10-27 | **Título:** BFS e DFS | **Semana:** 3

**O que entender (06:10–06:40):** Representação por lista de adjacência, fila e pilha; percursos de grafos.

**Material:** [VisuAlgo — Graph Traversal](https://visualgo.net/en/dfsbfs) · [MIT OCW — Algorithms](https://ocw.mit.edu/courses/6-006-introduction-to-algorithms-spring-2020/)

**O que praticar (06:40–07:40):** Implemente BFS e DFS em grafo não direcionado com ciclo. Teste origem ausente, destino inalcançável e múltiplos componentes; explique caminho mínimo em grafo não ponderado.

**O que validar (07:40–07:55):** testes cobrindo pelo menos um erro/borda, explicação em linguagem própria e trade-offs. Nas primeiras sessões, aplique avaliação conceitual quando código ainda não existir.

**Entrega/critério de conclusão:** Código, teste de 3 cenários e um desenho de grafo usado na prova.

**Vinculação:** [Issue da semana](https://github.com/odilonBraga011/estudo-arquiteturas/issues/3).

---

## S13

**Data:** 2026-10-28 | **Título:** Processos, threads e concorrência | **Semana:** 3

**O que entender (06:10–06:40):** Processo, thread, ciclo de vida, agendamento e diferença entre concorrência e paralelismo.

**Material:** [Oracle — Concurrency](https://docs.oracle.com/javase/tutorial/essential/concurrency/) · [Java API — java.util.concurrent](https://docs.oracle.com/en/java/javase/25/docs/api/java.base/java/util/concurrent/package-summary.html)

**O que praticar (06:40–07:40):** Execute 100 tarefas pequenas em série e via ExecutorService; registre duração e número de threads. Explique por que mais threads pode piorar resultado.

**O que validar (07:40–07:55):** testes cobrindo pelo menos um erro/borda, explicação em linguagem própria e trade-offs. Nas primeiras sessões, aplique avaliação conceitual quando código ainda não existir.

**Entrega/critério de conclusão:** Laboratório com logs, tempos, ambiente e reflexão sobre overhead.

**Vinculação:** [Issue da semana](https://github.com/odilonBraga011/estudo-arquiteturas/issues/3).

---

## S14

**Data:** 2026-10-29 | **Título:** Race conditions e deadlocks | **Semana:** 3

**O que entender (06:10–06:40):** Seções críticas, atomicidade, lock ordering e consequências da sincronização.

**Material:** [Oracle — Synchronization](https://docs.oracle.com/javase/tutorial/essential/concurrency/sync.html) · [Java API — java.util.concurrent](https://docs.oracle.com/en/java/javase/25/docs/api/java.base/java/util/concurrent/package-summary.html)

**O que praticar (06:40–07:40):** Crie contador compartilhado concorrente com resultado incorreto provável; corrija usando AtomicInteger. Demonstre (apenas em processo de teste com timeout) risco de deadlock e prevenção por ordem de locks.

**O que validar (07:40–07:55):** testes cobrindo pelo menos um erro/borda, explicação em linguagem própria e trade-offs. Nas primeiras sessões, aplique avaliação conceitual quando código ainda não existir.

**Entrega/critério de conclusão:** Teste que expõe o problema e teste da correção; anotações de riscos e trade-offs.

**Vinculação:** [Issue da semana](https://github.com/odilonBraga011/estudo-arquiteturas/issues/3).

---

## S15

**Data:** 2026-10-30 | **Título:** Fila concorrente e revisão | **Semana:** 3

**O que entender (06:10–06:40):** BlockingQueue, produtores/consumidores, limites e encerramento seguro.

**Material:** [Java API — BlockingQueue](https://docs.oracle.com/en/java/javase/25/docs/api/java.base/java/util/concurrent/BlockingQueue.html) · [Oracle — Concurrency](https://docs.oracle.com/javase/tutorial/essential/concurrency/)

**O que praticar (06:40–07:40):** Construa 2 produtores e 2 consumidores com fila de capacidade limitada; teste processamento único, backpressure e shutdown. Compare com implementação insegura.

**O que validar (07:40–07:55):** testes cobrindo pelo menos um erro/borda, explicação em linguagem própria e trade-offs. Nas primeiras sessões, aplique avaliação conceitual quando código ainda não existir.

**Entrega/critério de conclusão:** Código, teste de concorrência e revisão de três falhas/aprendizados.

**Vinculação:** [Issue da semana](https://github.com/odilonBraga011/estudo-arquiteturas/issues/3).

---

## S16

**Data:** 2026-11-02 | **Título:** DNS, TCP/IP e ciclo da requisição | **Semana:** 4

**O que entender (06:10–06:40):** DNS, IP, portas, conexão TCP e separação dos papéis HTTP/TLS.

**Material:** [MDN — Overview of HTTP](https://developer.mozilla.org/en-US/docs/Web/HTTP/Overview) · [Cloudflare Learning — DNS](https://www.cloudflare.com/learning/dns/what-is-dns/)

**O que praticar (06:40–07:40):** Trace uma requisição de uma API pública: nome do host, resolução DNS, conexão e resposta. Desenhe um diagrama de sequência com o que ocorre em cada camada.

**O que validar (07:40–07:55):** testes cobrindo pelo menos um erro/borda, explicação em linguagem própria e trade-offs. Nas primeiras sessões, aplique avaliação conceitual quando código ainda não existir.

**Entrega/critério de conclusão:** diagrama-requisicao.md com fluxo e resultados de comandos (nslookup e curl -v), omitindo dados pessoais.

**Vinculação:** [Issue da semana](https://github.com/odilonBraga011/estudo-arquiteturas/issues/4).

---

## S17

**Data:** 2026-11-03 | **Título:** HTTP e idempotência | **Semana:** 4

**O que entender (06:10–06:40):** Métodos seguros/idempotentes, códigos de status, headers e semântica HTTP.

**Material:** [RFC 9110 — HTTP Semantics](https://www.rfc-editor.org/rfc/rfc9110) · [MDN — HTTP](https://developer.mozilla.org/en-US/docs/Web/HTTP)

**O que praticar (06:40–07:40):** No laboratório API, faça GET, POST e PUT ou PATCH. Simule envio duplicado de uma operação: explique perigo de POST repetido e implemente chave idempotente simplificada com testes.

**O que validar (07:40–07:55):** testes cobrindo pelo menos um erro/borda, explicação em linguagem própria e trade-offs. Nas primeiras sessões, aplique avaliação conceitual quando código ainda não existir.

**Entrega/critério de conclusão:** Tabela de métodos/códigos, 2 testes de duplicação e explicação do limite da solução.

**Vinculação:** [Issue da semana](https://github.com/odilonBraga011/estudo-arquiteturas/issues/4).

---

## S18

**Data:** 2026-11-04 | **Título:** TLS e transporte seguro | **Semana:** 4

**O que entender (06:10–06:40):** Certificados, cadeia de confiança, validação de hostname, handshake TLS.

**Material:** [OWASP — TLS Cheat Sheet](https://cheatsheetseries.owasp.org/cheatsheets/Transport_Layer_Security_Cheat_Sheet.html) · [RFC 8446 — TLS 1.3](https://www.rfc-editor.org/rfc/rfc8446)

**O que praticar (06:40–07:40):** Compare curl -v em endpoint HTTPS conhecido e servidor HTTP local. Registre protocolo/certificado exibidos; explique ameaça mitigada pelo TLS e limite de proteção.

**O que validar (07:40–07:55):** testes cobrindo pelo menos um erro/borda, explicação em linguagem própria e trade-offs. Nas primeiras sessões, aplique avaliação conceitual quando código ainda não existir.

**Entrega/critério de conclusão:** Resumo de handshake, 3 verificações de segurança e diagrama de comunicação.

**Vinculação:** [Issue da semana](https://github.com/odilonBraga011/estudo-arquiteturas/issues/4).

---

## S19

**Data:** 2026-11-05 | **Título:** Timeouts, retry, cache e backoff | **Semana:** 4

**O que entender (06:10–06:40):** Tempo-limite, falhas transitórias, backoff exponencial com jitter, retry storm e cache HTTP.

**Material:** [AWS — Timeouts, retries and backoff](https://aws.amazon.com/builders-library/timeouts-retries-and-backoff-with-jitter/) · [MDN — HTTP caching](https://developer.mozilla.org/en-US/docs/Web/HTTP/Caching)

**O que praticar (06:40–07:40):** Simule endpoint lento/falhando no localhost; cliente com timeout e retry limitados. Compare com cache simples; discuta por que não repetir operações não idempotentes.

**O que validar (07:40–07:55):** testes cobrindo pelo menos um erro/borda, explicação em linguagem própria e trade-offs. Nas primeiras sessões, aplique avaliação conceitual quando código ainda não existir.

**Entrega/critério de conclusão:** Experimento com tempos, número de tentativas, diferenças e recomendações.

**Vinculação:** [Issue da semana](https://github.com/odilonBraga011/estudo-arquiteturas/issues/4).

---

## S20

**Data:** 2026-11-06 | **Título:** Tracing e revisão do mês | **Semana:** 4

**O que entender (06:10–06:40):** Caminho de requisição, tempo de DNS/conexão/servidor, propagação de falhas e observabilidade.

**Material:** [Chrome DevTools — Network](https://developer.chrome.com/docs/devtools/network) · [OpenTelemetry Docs](https://opentelemetry.io/docs/)

**O que praticar (06:40–07:40):** Faça diagrama ponta a ponta de GET/POST, identifique 3 potenciais gargalos e seus sinais. Refaça cinco perguntas do diagnóstico sem consulta e avalie avanços.

**O que validar (07:40–07:55):** testes cobrindo pelo menos um erro/borda, explicação em linguagem própria e trade-offs. Nas primeiras sessões, aplique avaliação conceitual quando código ainda não existir.

**Entrega/critério de conclusão:** relatorio-mes-01.md com diagrama, diagnóstico revisado, 3 próximos pontos de estudo e links de commits.

**Vinculação:** [Issue da semana](https://github.com/odilonBraga011/estudo-arquiteturas/issues/4).

---
