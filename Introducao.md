# Conceitos essenciais

## 🤔 O que é? 

- É um conjunto de regras e protocolos que permite diferentes softwares se comuniquem e interajam entre si. Em termos simples, é como um garçom que recebe pedidos **(requisições)** de diferentes clientes **(aplicações)** e os entrega á cozinha **(servidor)**, trazendo as repostas de volta para cada cliente.

## API REST

- É um tipo especifico de **API** que segue regras definidas pela arquitetura **REST**, que uso principalmentes pacotes **HTTP**. Segue principios como: Stateless: Cada requisições é independente, o servidor não guarda estado da sessão. Metodos HTTP padronizados: **GET, PUT, DELETE, POST.**

## Web Services

- São um conjunto de métodos invocados por outras aplicações utilizando tecnologias **Web** sendo uma solução utilzada na integração de sistemas e na comunicação entre aplicações distintas.

## Web API 

- É uma **API** na internet, com um conjunto de serviços expostos via web para realizar a integração da aplicação com diversos tipos de clientes **(web, mobile, dekstop, etc).**

## API SOAP

- É um protocolo **(w3C)** baseado em **XML**, usado para trocar informações entre aplicações no mesmo ou em diferentes sistemas operacionais.

## ASP.NET CORE

- É o framework da **Microsoft** para criar **Web APIs** aderentes ao estilo REST(RESTFUL) na plataforma .NET Core.

- Permite criar serviços RESTFUL, conhecidos como Web APIs usando a linguagem C#.
- Para tratar as solicitações usa os Controladores que são classes C#
- Podemos também usar as Minimal APIs para tratar os requests criando APIs com apenas u único arquivo.

## API RESTFUL 

- Uma API é RESTFUL quando ela é aderente ao estilo REST.
- Possuir uma arquitetura cliente-servidor
- Ser sem stateless
- Ter uma interface uniforme

# Estado: 

Toda requisição recebe um código de resposta conhecido como status. Com o status é possivel saber se uma operação foi realizada com sucesso

<img src="./image.png" alt="Image que descreve o estado">

Uma requisição HTTP se divide em 3 partes: - Request Line: Método HTTP + URI + Protocolo HTTP - Headers: Metadados que se enviam na requisição com informação. - Body: Informação adicional enviada ao servidor.

# Métodos HTTP

- Get: 
    - Usadas para recuperar informações(Retornar a representação do recurso);
    - Não altera o estado(Método seguro);
    - É idempotente(Produz o mesmo resultado se repetida);
    - Possiveis retornos para o código de status HTTP.
- Post:
    - Usado para criar uma informação;
    - Alteram o estado do recurso;
    - Não são idempotentes;
    - Possiveis retornos para o codigo de status http.

- Put
    - Usado para atualizar uma informação;
    - Alteram o estado do recurso;
    - São idempotentes;
    - Possíveis retornos para o código de status HTTP;
- Delete:
    - Usado para deletar uma informação;
    - Alteram o estado do recurso;
    - São idempotentes;
    - Possiveis retornos para o código de status HTTP;
