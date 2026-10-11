# Integrações e automações de estudo

## Papéis
- **Google Calendar:** reserva de tempo, compromissos e lembretes. **Uma série recorrente diária de 2 horas**, iniciando no horário escolhido pelo estudante; lembretes 30 e 5 min antes.
- **Todoist:** tarefas executáveis do dia e backlog da semana; no máximo 3 prioridades por sessão. Projeto sugerido `Formação — Engenharia e Arquitetura de Software`.
- **GitHub:** fonte de verdade do currículo, evidências, código, diagramas e decisões. Issues são trabalhos com critérios de aceite; commits registram experimentos.
- **ChatGPT:** tutoria socrática, simulação de entrevistas, revisão de ADRs e do progresso. Não marcar tarefas completas automaticamente só por ter conversado.
- **VS Code:** ambiente de exercícios, depuração e testes.
- **Anki (opcional):** cartões sobre conceitos que exigem recuperação espaçada. Evitar decorar listas de padrões sem contexto.
- **Exercism / LeetCode / laboratórios:** prática de algoritmos e linguagem.
- **Obsidian ou Markdown (opcional):** notas sincronizadas pelo Git, sem necessidade de duplicar o plano em 5 aplicativos.

## Conexões previstas
1. Conectar Todoist à conta, se desejar executar tarefas via ChatGPT.
2. Escolher horário de estudo realista para criar o bloco recorrente no Google Calendar.
3. Importar as tarefas semanais do GitHub para o Todoist manualmente ou por automação autorizada.
4. Vincular URLs das Issues relevantes na descrição de cada sessão/tarefa.
5. Fazer revisão semanal: comparar commits/artefatos com o planejamento, sem assumir que todo commit = aprendizado.

## Organização sugerida de Issues
- `[S01] Diagnóstico e requisitos` — critérios: requisitos, atributos de qualidade e decisão.
- `[S02] Análise de complexidade e estruturas` — 5 desafios e benchmarks.
- `[S03] Concorrência e algoritmos` — race condition demonstrada e corrigida.
- `[S04] Protocolos e redes` — captura e explicação do fluxo HTTP/TLS.

**Campos recomendados em cada tarefa:**
- Semana/dia, objetivo, material, experimento, definição de pronto, evidência (link de commit), dificuldades e revisão D+1/D+7/D+30.

## Evitando duplicidades
O **currículo mora no GitHub**; o **horário mora no Calendar**; o **checklist cotidiano mora no Todoist**. Não mantenha três cópias independentes do mesmo backlog.

## Automação avançada (opcional, posterior)
Usar GitHub Actions, n8n ou integrações oficiais para:
- Gerar Issue da semana a partir do roadmap.
- Sincronizar apenas tarefas selecionadas para Todoist.
- Publicar resumo semanal de commits, testes e artefatos.
- Gerar relatório de progresso com horas reais informadas no Todoist.

**Segurança:** tokens em secret managers/variáveis seguras; permissões mínimas; nunca publicar tokens no repositório público. Não presumir sincronização bidirecional nativa entre todos os serviços.

## Horário pendente
O plano acadêmico e o repositório independem de horário fixo. Para criar o Calendar corretamente, definir **hora de início** no fuso `America/Fortaleza` (UTC−03:00) e revisar conflitos.
