# Rotina: agendar o que foi aprovado (rodar sob demanda ou diariamente)

1. Ler `approvals/queue.md`. Considerar **apenas** linhas com `[x]`. Se não houver nenhuma, encerrar sem fazer nada.
2. Para cada item aprovado, conferir se existe a mídia e a legenda final. Se faltar, não agendar e avisar o que falta.
3. Descobrir o melhor horário com `getBestTimeToPostByNetwork` (Metricool, brandId 7904241, fuso America/Sao_Paulo) para a rede do post.
4. Agendar com `createScheduledPost` somente em datas futuras. Usar `createScheduledPostForReview` quando a ferramenta estiver disponível, para o post ficar em revisão no Metricool.
5. Mover o item para "Já agendados" em `approvals/queue.md`, com data e horário. Commit e push.
6. Nunca publicar imediatamente e nunca agendar item sem `[x]`.
