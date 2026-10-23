# Blow Poker Clube – Fechamento

Versionamento do fechamento do cash game e do painel publicado.

- `index.html`: painel de fechamento (botões "Carregar sem despesas" e "Carregar com despesas").
- `data/fechamentos.json`: resumo por fechamento, espelhando a aba CASHGAME da planilha.
- `data/aportes_cabelim.json`: detalhe de aportes do Cabelim, espelhando a aba APORTES.
- `data/despesas.json`: lançamentos de despesas (aba RECEITAS, DESPESAS, DIVIDAS).

O `index.html` recebe os dados em constantes JavaScript geradas a partir dos JSON.

Fonte: planilha NOVO_FECHAMENTO_GERAL 3.MAIN, Google Sheets `1rUM13geLJBsSe58QWcZ4ZPNxiNOsFnV2AdSzd1TMuqM`.
Abas usadas: CASHGAME (fechamentos), SOCIOS CASH & GERAL (mesa, torneio, aportes e saldo por sócio), APORTES (detalhe de aportes), RECEITAS, DESPESAS, DIVIDAS (despesas) e SOCIOS TORNEIO (total de torneios).
Saldo do sócio segue a planilha: inclui torneio.
Atualizado em 23/10/2026 com 27 fechamentos (09/09 a 20/10).
Atualização manual: cada alteração da planilha gera um novo commit com os dados e o painel.
