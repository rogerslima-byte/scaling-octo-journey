# Rotina: relatório semanal de métricas (segunda-feira)

1. Ler `config/account.md` (contas, brandId do Metricool, regras).
2. Instagram (Windsor, conector `instagram`): puxar `get_fields` primeiro, depois os últimos 7 dias com `date, media_type, media_caption, media_permalink, media_reach, media_views, media_saved, media_shares, media_engagement` e o total de `followers_count`, `follower_count_1d`, `reach_followers`, `reach_non_followers`.
3. TikTok (Metricool, brandId 7904241): métricas `TKPO02, TKPO05, TKPO07, TKPO08, TKPO09, TKPO10, TKPO13` dos últimos 7 dias.
4. Facebook (Windsor, conector `facebook_organic`): alcance e engajamento das 3 páginas, se houver dados.
5. Escrever `reports/AAAA-MM-DD-semanal.md` com: números da semana, variação contra o relatório anterior, top 3 posts, pior post, 3 recomendações para a semana seguinte.
6. Regras: nunca inventar número; campo vazio vira "sem dado". Se uma rede falhar, dizer qual e por quê.
7. Commit em uma branch `relatorio-AAAA-MM-DD` e push. Não mexer em `approvals/`.
