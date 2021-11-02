# Comandos Git

## `init`

Inicia o repositório git na pasta

## `status`

Mostra os status do git

Mostra arquivos que ainda não estão sendo monitorados

## `add`

Começa rastrear os arquivos

- **Opções**
    
    `<Nome do arquivo>` - Adiciona um arquivo
    
    `.` - Adiciona todos or arquivos que não estão no .gitignore 
    

## `rm`

- **Opções**
    
    `--cached <Nome do arquivo>`  - Para de rastrear um arquivo
    

## `commit`

Salva as alterações dos arquivos rastreados

- **Opções**
    
    `-m "<Mensagem do comit>"` - Coloca uma mensagem na alteração
    

## `remote`

### `add <Nome da branch> <Url da branch>`

Adiciona uma branch remota

## `show`

Mostra o ultimo commit

## `log`

Mostra o histórico de commits

*Parecido com o comando* `reflog`

## `push`

Envia arquivos para a o repositório remoto

## `pull`

Pega tudo do branch remoto e atualiza **tudo** do branch local

# *Branches*

## `branch`

Mostra todas as branches

- **Opções**
    
    `<Nome da nova branch>` - Cria uma nova branch
    

## `checkout <Nome da branch>`

Muda de branch

## `merge <Nome da branch>`

Junta as branches

A junção é feita entre branch **atual** (branch que será mudada) e a branch passada no comando (branch que tem a mudança)

## Legenda

### **Arquivo sendo rastreado**

Alterações no arquivo que forem comitadas serão salvas então o arquivo tera uma ponto salvo na linha do tempo

## Sites para mais referencias

- [Comandos Git - Aprenda Git do básico ao avançado](https://comandosgit.github.io/)