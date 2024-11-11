# Bootcamp #01 Qualiters Club
Teste de API Rest do manual a CI/CD

## O que é
Este repositório foi criado para o bootcamp de Teste de API Rest.

## Tecnologias utilizadas
- Postman versão v 11.18.0
- node version v18.16.1
- newman v5.3.2
- newman-reporter-html

## Documentações
- Analise Técnica: Analise/
- Doc da API: [Consulte Swagger](https://serverest.dev/#/)

## Como instalar o ambiente
- Primeiro: instale o node em seu computador [baixe aqui](https://nodejs.org/en/download)
- Segundo: realize a instalação do newman de forma global [baixe aqui a dependencia](https://www.npmjs.com/package/newman)
```
npm install -g newman
```
- Terceiro: realize a instalação da dependencia dos relatórios (opcional) [newman-reporter-html](https://www.npmjs.com/package/newman-reporter-html)
```
npm install -g newman-reporter-html
```
## Como rodar os testes
### Pelo Postman web ou desktop
- Import a collection e o environment
- Execute os teste de forma manual ou automatizada
### Pelo newman
- Abra o console de preferência
- Execute a seguinte linha de comando para rodar os testes
```
newman run ServeRest.postman_collection.json -e serveRest_env.postman_environment.json -r cli
```
- Execute os teste com relatório
```
newman run ServeRest.postman_collection.json -e serveRest_env.postman_environment.json -r cli,htmlextra
```
### Report
Se você optou por rodar os teste com o report htmlextra, você gerou um arquivo html com o resultado dos testes e para verificar as validaçõe

## Entre em contato
email: vitorcarrasco@gmail.com
LinlID:
