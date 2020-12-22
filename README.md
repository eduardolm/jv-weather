# JvWeather

Projeto desenvolvido em Angular, durante bootcamp Avanade / Digital Innovation One.

# Objetivo

Os objetivos deste projeto são aprofundar os conhecimentos em Angular, através do desenvolvimento de um sistema de consulta de condições climáticas, utilizando OpenWeather API.
Nesse projeto criamos os componentes, utilizamos estados da página, criamos favoritos e views detalhadas das condições climáticas da cidade escolhida.

# Stack utilizada

 + NodeJs
 + TypeScript
 + Angular
 + Nrgx
 + Github
 + ngx-bootstrap

# Como testar

Para a execução deste programa é preciso ter instalados Node.js, Angular CLI.
Após toda a infraestrutura da aplicação ter sido instalada, podemos executar a aplicação através do comando:

`ng s`

Esse comando inicia a aplicação, que pode ser acessada através do browser, no seguinte endereço:

`http://localhost:4200`

Para testar a aplicação basta escrever o nome da cidade que se deseja consultar numa das caixas de diálogo. Ao clicar em 'Pesquisar',
os dados climáticos da cidade escolhida são retornados na tela.
Para acessar detalhes sobre os dados, basta clicar em 'Ver detalhes'.
Os detalhes da previsão do tempo para os próximos dias são exibidos.

Podemos também adicionar e remover cidades aos favoritos para maior facilidade de consulta.
Todas as informações de clima são recebidas da OpenWeather API.

