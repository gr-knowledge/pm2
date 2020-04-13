# pm2
Knowledge of pm2


|**COMANDO**|**DESCRIÇÃO**|
|---|---|
|```npm  install -g pm2```|Instalação|
|```pm2 status\|list```|mostra todos os processos gerenciados pelo pm2|
|```pm2 start server.js```|inicia um processo|
|```pm2 start server.js --name apelido```|Atribui um apelido ao processo|
|```pm2 start server.js -i 4```|Distribui carga entre 4 closters|
|```pm2 show\|describe ID```|Mais detalhes do processo|
|```pm2 log ID```|Mostra logs do processo (ID opcional)|
|```pm2 logs --json / --format```|Formata saída do log|
|```pm2 monit```|mostra consumo da CPU, memória e log|
|```pm2 delete ID```|Deleta um processo|
|```pm2 stop ID```|Para um processo|
|```pm2 restart ID```|Reinicia processo|
|```pm2 reload all```|Recarrega arquivos|
|```pm2-startup install```|Possibilita uso do startup (somente windows)|
|```pm2 save```|Caso esteja utilizando startup, salva novo modo caso exista|
|```pm2 resurrect```|Volta para modo salvo anteriormente|
|```pm2 startup / unstartup```|Ao reiniciar pc iniciar automaticamente como estava|
|```pm2 flush```|?|
