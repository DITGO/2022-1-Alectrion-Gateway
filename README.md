<div align="center">
    <img src="https://github.com/fga-eps-mds/2022-1-Alectrion-DOC/blob/gh-pages/docs/documentation/Documentos/Identidade%20Visual/S%C3%ADmbolo_Alectrion.png?raw=true" height="350px" width="350px">
</div>

## Sobre

Alectrion é um sistema de controle e gerenciamento de inventário e ordens de serviços de TI.

Aplicação disponível em: [link da aplicação](https://alectrion-front.herokuapp.com/)

## Requisitos
- Local(sem docker)
    - node (versão 16.10.0 ou superiores)
    - yarn (versão 1.22.18)
- Docker
    - Docker e docker-compose
## Instalação e Execução

1. Clone o projeto 

    > git clone https://github.com/fga-eps-mds/2022-1-Alectrion-Gateway

2. Entre na pasta do projeto

    > cd 2022-1-Alectrion-Gateway

3. Crie um arquivo .env(variaveis de exemplo no .env.example deste repositório) adicionando as URL para os serviços
 UserApi e EquipamentApi.

### Local(Sem docker)

4. Instale as depencencias
        
    > yarn

6. Crie um arquivo .env da mesma forma do arquivo .env.example

7. Execute o projeto

    > yarn dev


### Docker

4. Gerar imagem

    > docker build -t alectrion-gateway .

6. Rodar container
    
    > docker run --env-file .env -p 4000:4000 -d --name alectrion-gateway-container alectrion-gateway

A aplicação será iniciada na porta 4000

## Contribuir
Para contribuir com esse projeto é importante seguir nosso [Guia de Contribuição](docs\documentation\Documentos\guia-contribuicao.md) do repositório e seguir nossa [Política de Branches](docs\documentation\Documentos\politicas-branch.md).

## Ambientes

- [Pages](https://fga-eps-mds.github.io/2022-1-Alectrion-DOC/)

- [Documentação](https://github.com/fga-eps-mds/2022-1-Alectrion-DOC)

- [Front-End](https://github.com/fga-eps-mds/2022-1-Alectrion-FrontEnd)

- [Back-End: UserAPI](https://github.com/fga-eps-mds/2022-1-Alectrion-UserAPI)
  
- [Back-End: EquipamentAPI](https://github.com/fga-eps-mds/2022-1-Alectrion-EquipamentApi) 

- [Back-End: GateWay](https://github.com/fga-eps-mds/2022-1-Alectrion-Gateway) 


## Integrantes

| Disciplina | Matricula | Nome | Github | E-mail |
|------------|-----------|------|--------|--------|
|EPS|150128312|Guilherme Leal|[gleal17](https://github.com/gleal17)|guilhermelml@gmail.com|
|EPS|150132344|João Pedro Soares|[jpcirqueira](https://github.com/jpcirqueira)|jpcirqueira81@gmail.com|
|EPS|150136862|Lucas Alexandre|[lucasA27](https://github.com/lucasA27)|150136862@aluno.unb.br|
|EPS|150141220|Matheus Estanislau|[MatheusEstanislau](https://github.com/MatheusEstanislau)|matheus.estanislau@icloud.com|
|EPS|170080366|Moacir Mascarenha|[moacirmsj](https://github.com/moacirmsj)|170080366@aluno.unb.br|
|MDS|190016647|Lucas Oliveira Meireles|.[Katuner](https://github.com/Katuner)|katunerx@gmail.com|
|MDS|190094320|Pedro Siqueira|[PedroSiq](https://github.com/PedroSiq)|pedroaugustossiqueira@gmail.com|
|MDS|190125152|Andrew Oliveira Cerqueira Lugon|[andrewlugon](https://github.com/andrewlugon)|andrewlugon000@gmail.com|
|MDS|202017503|Wildemberg Sales da Silva Junior|[wildemberg-sales](https://github.com/wildemberg-sales)|junior_sales2010@hotmail.com|
|MDS|202046265|Mário Vinícius|[mv23c](https://github.com/mv23c)|mario.mvbc@gmail.com|
|MDS|202016560|Igor Silva de Paiva|[IgorSPaiva](https://github.com/IgorSPaiva)|202016560@aluno.unb.br|
|MDS|212008197|João Pedro Alves Machado|[pedroblome](https://github.com/pedroblome)|212008197@aluno.unb.br|
|MDS|202016800|Lucas Heler Lopes|[Akaeboshi](https://github.com/Akaeboshi) |lucasheler3@gmail.com| 
