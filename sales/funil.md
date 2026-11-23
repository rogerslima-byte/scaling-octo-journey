# Funil de vendas — TR Premium (R2lcross)

Objetivo: transformar comentário e DM com palavra-chave em conversa de venda, sem você precisar responder cada um do zero.

## Dados que faltam (preencher antes de ativar qualquer resposta automática)

- Preço do TR Premium: **R$ 85,88** (periodicidade a confirmar: mensal, trimestral ou outra). Não informar o valor nas mensagens automáticas até confirmar.
- Link ou WhatsApp para fechamento: ______
- O que está incluso (treino, nutrição, acompanhamento): ______
- Prazo de resposta que você consegue cumprir: ______
- Há avaliação inicial gratuita? ______

## Palavras-chave dos CTAs

| Palavra | Usada em | Intenção |
|---|---|---|
| CONSULTORIA | Reels e carrosséis de acompanhamento | Quer conhecer o TR Premium |
| EXECUCAO | Reels de técnica | Quer o passo a passo; lead morno |
| PLANO | Posts sobre dieta e rotina | Quer um plano pessoal |
| COMEÇAR | Posts de motivação | Lead frio; nutrir antes de vender |

## Sequência de DM (rascunho, nada é enviado sem a sua aprovação)

1. **Resposta imediata:** "Oi! Aqui é do R2lcross 👋 Vi que você comentou [PALAVRA]. Qual é o seu principal objetivo hoje: emagrecer, ganhar massa ou ter mais constância?"
2. **Qualificação (2 perguntas no máximo):** onde treina (academia ou casa) e quantos dias por semana consegue treinar.
3. **Oferta:** explicar em 3 linhas como funciona o TR Premium (treino + nutrição + acompanhamento 100% online) e enviar o link ou chamar no WhatsApp.
4. **Follow-up:** 24 h e 72 h depois, uma mensagem curta e sem pressão. Depois disso, parar.

Regras: sem promessa de resultado ou prazo, sem prescrição individual de dieta por DM, e transferir para você qualquer pergunta de saúde (lesão, medicação, gestação).

## Automação das respostas

O **ChatGenius** (conta gratuita) já tinha 4 gatilhos de comentário criados em 23/11/2026 de manhã, antes desta conversa. Eu não os criei nem alterei.

| Palavra | Estado em 23/11 | Texto fala de |
|---|---|---|
| PLANO | **ATIVO** | "Método TR 120", 180 dias, 120 vídeos |
| BLACK | **ATIVO** | Black Friday, 30% de desconto, 10 vagas, até 30/11 |
| CONSULTORIA | pausado | consultoria "TR Fitness Premium" |
| EXECUCAO | pausado | "Método TR 120" |

Pendências antes de manter ou ligar:
1. Os textos usam "TR Fitness Premium" e "Método TR 120". A marca definida é **R2lcross | TR Premium**. Alinhar os nomes.
2. Confirmar se a oferta de Black Friday (30%, 10 vagas) é real e se o preço R$ 85,88 corresponde ao Método TR 120.
3. Testar com uma conta sua (`simulate_comment`) antes de ligar outros gatilhos.

## Controle de leads

Acompanhar em `sales/leads.md`. O relatório semanal lê esse arquivo e calcula: leads novos, conversas ativas, fechamentos e taxa de conversão por palavra-chave, para você ver qual conteúdo vende e não só qual alcança.
