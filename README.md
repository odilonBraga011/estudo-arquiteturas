# Formação contínua em Engenharia e Arquitetura de Software

Plano de estudos **iniciado em 12/10/2026**, projetado para **2 horas por dia, de segunda a sexta-feira** (10 h/semana; 520 h em 52 semanas). Esta é uma trilha adaptativa, não uma promessa de dominar tudo em um ano.

> Objetivo: sair da memorização de padrões e evoluir para **projetar, implementar, medir, documentar, defender e operar sistemas** com consciência de trade-offs.

## Comece aqui

1. [Guia de estudos e rotina diária](docs/GUIA-DE-ESTUDOS.md)
2. [Roteiro detalhado das primeiras 20 sessões: o que ler, praticar e entregar](docs/ROTEIRO-DIARIO-20-SESSOES.md)
3. [Roadmap completo de 52 semanas](docs/PLANO-52-SEMANAS.md)
3. [Primeiros 30 dias — tarefas concretas](docs/PRIMEIROS-30-DIAS.md)
4. [Fontes, cursos e exercícios](docs/RECURSOS.md)
5. [Projetos práticos e portfólio](docs/PROJETOS.md)
6. [Avaliações, métricas e revisões](docs/AVALIACAO.md)
7. [Calendar, GitHub, Todoist e automações](docs/INTEGRACOES.md)

## Ritual de 120 minutos

| Min | Atividade |
|---:|---|
| 0–10 | Recordação ativa do que foi estudado antes (sem consulta) |
| 10–40 | Teoria com leitura ativa e anotações curtas |
| 40–100 | Implementação, experimento, laboratório, kata ou desenho de solução |
| 100–115 | Testes, análise de trade-offs e registro do que aprendeu |
| 115–120 | Commit, checklist e definição do próximo passo |

A **entrega de cada semana** deve ser verificável: código funcionando, testes, diagrama, ADR, benchmark, postmortem ou comparação fundamentada. A revisão integradora ocorre às sextas-feiras.

## Calendário semanal

| Dia | Modo |
|---|---|
| Segunda | Fundamentos e modelos mentais |
| Terça | Código e padrões |
| Quarta | Design e experimentação |
| Quinta | Dados, desempenho e sistemas |
| Sexta | Qualidade, segurança, operações e revisão |
| Sexta-feira (final da sessão) | Revisão da semana e retrospectiva |

Os **temas de cada dia** vêm da semana correspondente no [plano de 52 semanas](docs/PLANO-52-SEMANAS.md).

## Projetos âncora

- **Monólito modular de negócio:** arquitetura, contratos, DDD, testes, auditoria.
- **Sistema distribuído de pedidos/convites:** mensageria, integração, idempotência e observabilidade.
- **Projeto de system design completo:** requisitos, capacidade, custos, segurança, SLOs, ADRs e apresentação.
- Trilha opcional: **otimização e escalas** com solver CP-SAT, quando adequado ao tema.

## Organização

```text
docs/                  # plano, rotina, bibliografia, critérios e integrações
templates/             # diário, ADR, revisão, desafio de system design
calendario/            # calendários e importações opcionais
projetos/              # documentação e experimentos dos projetos
diario/                # registros semanais (criar conforme avançar)
```

## Regras importantes

- **Entender antes de adotar:** não escolher microsserviços, DDD, CQRS ou cloud sem conhecer contexto e custos.
- **Prática deliberada:** estimar resultado antes de executar; comparar, medir e corrigir.
- **IA como mentora crítica:** pedir revisão e contraexemplos, nunca terceirizar a própria explicação.
- **Revisão semanal:** ajustar a sequência com base nas lacunas, não apenas cumprir horas.
- **Privacidade:** não versionar credenciais, dados reais de clientes ou informações empresariais sigilosas.

Início: 12/10/2026 · Idioma: pt-BR · Exemplos sugeridos: Java/Spring, TypeScript/Angular, PostgreSQL, Docker (troque conforme necessário).
