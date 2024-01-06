# Primeiros passos com Git e GitHub

Existem duas formas de obter um repositório Git na sua maquina:

- Transformando um diretório local que não esta sob controle de versão, num repositório Git; (git init)
- git init esse comando inicializa um nove repositorio vazio.
- Clonando um repositório Git existente
- git clone permite clonar/baixar um repositorio do servidor (remoto) no seu computador (local)
- git add . ou git add <nome da pasta> adiciona a area de stage
- git reset. ou git reset <nome da pasta> remove da area de stage
- git commit -m “escreva o nome do commit”    faz o commit obs para fazer o commit os arquivos tem q esta no stage
- git remote add origin → vincula o repositorio local a um repositorio remoto
- git push envia todas as alteracoes do repositorio local para o repositorio remoto
    
    git push -u origin “nome da branch”
    
- git pull baixa todas as alteracoes do repositorio remoto para o repositorio local
