# Comandos Git

## `init`

Inicia o repositório git na pasta

## `status`

Mostra os status do git

Mostra arquivos que ainda não estão sendo monitorados

## `diff`

Mostra todas as mudanças feitas no código

- **Opções**
    
    `<Arquivo>`  Mostra as mudanças apenas de um arquivo
    

## `add`

Começa rastrear os arquivos

- **Opções**
    
    `<Nome do arquivo>` - Adiciona um arquivo
    
    `.` - Rastreia todas as mudanças nos arquivos (menos os deletados) que não estão no .gitignore 
    
    `-u` - Rastreia todas as mudanças nos arquivos (menos nos recém criados) que não estão no .gitignore 
    
    `-A` - Rastreia **todas** as mudanças nos arquivos que não estão no .gitignore 
    

## `rm`

- **Opções**
    
    `--cached <Arquivo>`  - Para de rastrear um arquivo
    

## `commit`

Salva as alterações dos arquivos rastreados

- **Opções**
    
    `-m "<Mensagem do comit>"` - Coloca uma mensagem na alteração
    

## `reset`

Volta o código no tempo apagando os commits no histórico / log

- **Opções**
    
    `--soft` A mudanças feitas após o commit continuam e precisam ser monitoradas e comitadas
    
    `--hard` A mudanças feitas após o commit são apagadas
    

## `revert`

Volto código no tempo sem apagar os commits no histórico  / log

- **Opções**
    
    `--no-edit` Não abrirá o editor de texto
    

## `remote`

- **Opções**

### `add <Nome que desejar> <Url da branch>`

Salva um novo link para um repositório remoto com um nome desejado

## `show`

Mostra o ultimo commit

## `log`

Mostra o histórico de commits

*Parecido com o comando* `reflog`

## `push`

Envia arquivos para a o repositório remoto

- **Opções**
    
    `<Repositório salvo> <Branch>` Envia para o repositório remoto a branch desejada
    
    `<Repositório salvo> :<Branch>` Apaga a branch desejada do repositorio remoto
    

## `pull`

Pega as novas modificações do branch remoto para a branch local

- **Opções**

# *Branches*

## `branch`

Mostra todas as branches

- **Opções**
    
    `<Nome da branch>` Cria uma nova branch
    
    `-D <Nome da branch>` Apaga a branch
    

## `checkout`

Muda de branch

- **Opções**
    
    `HEAD -- <Arquivo>`  Apaga as alterações não comitadas de um arquivo
    
    `-b <Nome da branch>` Cria uma nova branch e alterna para ela
    
    `<Nome da branch>` Muda de branch
    
    `<Id de um commit> -- <Nome do arquivo>` Recupera a versão de um arquivo de um commit  
    

## `merge <Nome da branch>`

Junta as branches

A junção é feita entre branch **atual** (branch que será mudada) e a branch passada no comando (branch que tem a mudança)

## Legenda

### **Arquivo sendo rastreado / trackeado / monitorado**

Alterações no arquivo que forem comitadas serão salvas então o arquivo tera uma ponto salvo na linha do tempo

## Referencias

[Curso de Git e Github COMPLETO 2021 [Iniciantes] + Desafios + Muita Prática](https://youtu.be/kB5e-gTAl_s)

[Curso de Git & GitHub Para Completos Iniciantes](https://youtu.be/Yp0RRTdtkqY)

[COMO USAR GIT E GITHUB NA PRÁTICA! - desde o primeiro commit até o pull request! 2/2](https://youtu.be/UBAX-13g8OM)

[O QUE É GIT E GITHUB? - definição e conceitos importantes 1/2](https://youtu.be/DqTITcMq68k)

[CURSO COMPLETO DE GIT (2 HORAS E 30 MINUTOS)](https://youtu.be/OuOb1_qADBQ)

## Outras recomendações

[Comandos Git](https://comandosgit.github.io/)

[GitHub - DanielHe4rt/git4noobs: Aulão de Git para iniciantes](https://github.com/DanielHe4rt/git4noobs)
