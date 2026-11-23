# Central de automações do Instagram — TR Fitness (@r2lcross_estudio)

Este repositório guarda os relatórios, o calendário de conteúdo, os roteiros e a fila de aprovação da página. As rotinas rodam como tarefas agendadas do Claude e **só preparam rascunhos**. Nada é publicado ou agendado sem a sua aprovação.

## Estrutura

| Pasta | Para que serve |
|---|---|
| `config/account.md` | Contas conectadas, nicho, voz da marca e regras de autonomia |
| `reports/` | Relatórios semanais de métricas (Instagram, TikTok, Facebook) |
| `content/calendar/` | Plano semanal de posts |
| `content/scripts/` | Roteiros de Reels e legendas |
| `competitors/` | Lista de concorrentes e relatórios de tendências |
| `approvals/queue.md` | Fila: marque `[x] APROVADO` para liberar o agendamento |
| `automations/` | Os prompts usados por cada tarefa agendada |

## Fluxo

1. **Segunda de manhã**: relatório semanal em `reports/`.
2. **Quarta**: relatório de concorrentes e tendências em `competitors/reports/`.
3. **Sexta**: plano da semana seguinte em `content/calendar/`, com roteiros prontos e itens adicionados em `approvals/queue.md`.
4. **Você aprova** marcando os itens na fila.
5. **Agendamento**: só os itens aprovados vão para o Metricool, no melhor horário do dia.

## Regras fixas

- Autonomia: **preparar e avisar**, ou **agendar apenas após aprovação**. Nunca publicar sozinho.
- Nenhum dado de métrica é inventado. Se a fonte não trouxer o número, o relatório diz isso.
- Sem promessas de resultado ou de emagrecimento. Isso protege a conta e o seu CREF.
