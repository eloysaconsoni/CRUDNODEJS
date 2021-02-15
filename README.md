# CRUD em Noje.js com AdonisJs

Está API se baseia na criação de um CRUD funcional com as principais características de 

1. Login
2. Inserção
3. Exibição de dados
4. Exibição de dados por ID
5. Criação
6. Atualização
7. Exclusão
8. Relacionamentos
9. Testes

## Programas Principais

Crie um clone em sua máquina e instale as principais ferramentas

[Node.js](https://nodejs.org/ "Node.js")

Em seu CMD rode o comando para instalar o AdonisJs
```bash 
npm i -g @adonisjs/cli
```


### Configuração e execução

Dentro da pasta raiz da API rode os seguintes comandos

Instale os arquivos do package.json
```bash 
npm install
```
Crie as tabelas no banco executando as migrations
```bash 
adonis migration:run
```
Crie os arquivos iniciais para que se possa logar no sistema
```bash 
adonis seed
```
