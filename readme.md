# documentação de api 

* Escolher um local no computador para criar o projeto 
* Abrir o gitbash nesta pasta

com o gitbash aberto executar o comando para criar a raiz do projeto: (mkdir = criar a pasta)
```
mkdir NOME_PROJETO
```
Acessar a pasta:
```
cd NOME_DO_PROJETO
```
(cd = acessar pasta)
Comando para a abrir o vscode 
```
code .
```
Criar o arquivo gerenciador de pacotes node
```
npm init -y
```
Criar arquivo .gitignore(criar arquivo para não enviar arquivos para o gitignore)
```
touch .gitignore
```
Criar arquivo .env(arquivo para reservar variaveis do projeto)
```
touch .env 
```
## Instalar os pacotes do projeto 
```
npm i express nodemon dotenv 
```
* express: será o servidor da api
* nodemon: atualiza os arquivos alterados sem parar o dervidor
* dotenv: gerenciador de variaveis de ambiente 

Criar pasta src
```
mkdir src 
```
criar arquivo server.js dentro da pasta src
```
touch src/server.js 
```
Adicionar arquivos e pastas no gitignore 
```
node_modules
.env
```