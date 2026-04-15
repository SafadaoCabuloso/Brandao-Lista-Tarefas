# Brandao-Lista-Tarefas
Projeto de API do professor Brandão
___
    Basicamente esse projeto do Brandão foca na criação de uma API de lista de tarefas (to do list) usando Node.js puro, sem depender de frameworks (Express, litify). O objetivo principal era entender o funcionamento das requisições HTTP, bem como organizar o código usando uma estrutura em camadas. Foquei no desafio Pleno (valendo menção *B*), ou seja, fiz os desafios do Júnior e do Pleno.

    Para configurar o ambiente, o Node.js deve estar instalado na máquina. Depois disso, basta navegar até a pasta do projeto pelo terminal. Já que o foco do projeto é usar o Node.js puro, não precisa instalar mais nenhum pacote a não ser ele para rodar.

    Para executar o projeto, devemos usar o comando `node src/app.js` no terminal. Isso inicia o servidor na porta 3000, que pode ser acessado em `http://localhost:3000`. A partir disso, é só colar o URL no Postman (tem que instalá-lo).
    
    A solução segue uma arquitetura em camadas para manter o código organizado. A camada de rotas lida com as requisições recebidas e as direciona para o controlador apropriado. 
    O controlador atua como intermediário entre a requisição e a lógica da aplicação, processando os dados de entrada e retornando as respostas. A camada de serviço contém a lógica de negócios, incluindo validações e gerenciamento de tarefas. 
    Por fim, o modelo define a estrutura dos dados usados ​​na aplicação. Os dados são armazenados na memória usando um array, sem integração com banco de dados. Essa abordagem foi suficiente para atender aos requisitos do projeto e compreender plenamente o funcionamento de uma API.
