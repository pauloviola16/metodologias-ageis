# Métricas do Kanban

## Lead Time
Tempo total que um item leva desde que entra no sistema até ser concluído. 
É a visão de quem está esperando a entrega: "quanto tempo desde que eu pedi 
isso?"

## Cycle Time
Tempo desde que o item realmente começou a ser trabalhado (entrou em 
"Doing") até ser concluído. Não conta o tempo que ficou esperando na fila. 
É a visão de quem está fazendo o trabalho: "quanto tempo levamos trabalhando 
nisso, de fato?"

> A diferença entre os dois é justamente o tempo de espera. Se um item fica 
> 5 dias parado no "To Do" e depois leva 2 dias sendo feito, o Lead Time é 
> 7 dias, mas o Cycle Time é só 2.

## Delivery Rate (Throughput)
Número de itens de trabalho concluídos por unidade de tempo (ex: quantos 
itens o time termina por semana). Ajuda a prever quanto trabalho o time 
consegue entregar num período futuro.

## Work in Progress (WIP)
Quantidade de itens que estão "em andamento" no sistema, num determinado 
momento. É a métrica que o **WIP Limit** controla diretamente — se o limite 
é 3 e já tem 3 itens em "Doing", ninguém pode começar um quarto item até 
que um dos três seja concluído.
