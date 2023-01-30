# Repositório para os código no Linux 
## Geral
### Listando processos 
````
ps -aux            -- listar todos os processos
ps -U  fmeserver   -- listar todos os processos do usuário femserver 
ps -U tinorberto | awk '{print $1}' -- lista apenas apenas o nª do processo
pgrep -U 999 |xargs kill -9  -- matar todos os processos do usuário tinorberto

````
