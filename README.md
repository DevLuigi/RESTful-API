
<div align="center">
    <h1> API RESTful </h1>
</div>


<div align="center">
   <img src="http://img.shields.io/static/v1?label=STATUS&message=EM%20DESENVOLVIMENTO&color=RED&style=for-the-badge" alt="badge-em-desenvolvimento"/>
</div>

<br>

### Tópicos 

- [Descrição do projeto](#descrição-do-projeto)

- [Objetivo](#objetivo)

- [Funcionalidades](#funcionalidades)

- [Ferramentas utilizadas](#ferramentas-utilizadas)

- [Como rodar o projeto](#como-rodar-o-projeto)

- [Autor](#autor)

<br>

## Descrição do projeto 
<p align="justify">
  Esta API RESTful foi desenvolvida com o propósito de estudo e experimentação prática dos conceitos fundamentais da arquitetura REST. O projeto adota boas práticas como o uso correto dos verbos HTTP, modelagem de recursos, respostas padronizadas em JSON e implementação de HATEOAS, buscando alcançar o nível mais alto do Modelo de Maturidade de Richardson.
</p>

<br>

## Objetivo
<p>
  O objetivo principal deste projeto é aprofundar o entendimento sobre a construção de APIs modernas e escaláveis, utilizando uma abordagem progressiva que evolui até o nível máximo de maturidade REST. Ao longo do desenvolvimento, são explorados temas como autenticação, validação de dados, tratamento de erros, versionamento e documentação, com foco em criar uma base sólida para projetos reais.
</p>

<br>

## Funcionalidades

:heavy_check_mark: `Funcionalidade 1:` Cadastro de novos usuários com validações de entrada.

:heavy_check_mark: `Funcionalidade 2:` Atualização de dados cadastrais do usuário.

:heavy_check_mark: `Funcionalidade 3:` Exclusão de conta de usuário.

:heavy_check_mark: `Funcionalidade 4:` Autenticação de usuários com geração de token (JWT).

:heavy_check_mark: `Funcionalidade 5:` Consulta de informações do usuário autenticado.

:heavy_check_mark: `Funcionalidade 6:` Listagem de todos os usuários (requer permissão específica).

:heavy_check_mark: `Funcionalidade 7:` Paginação, ordenação e filtros na listagem de usuários.

:heavy_check_mark: `Funcionalidade 8:` Tratamento de exceções com mensagens padronizadas.

:heavy_check_mark: `Funcionalidade 9:` Suporte a HATEOAS nos endpoints de usuário.

:heavy_check_mark: `Funcionalidade 10:` Documentação da API com Swagger.

<br>

## Ferramentas utilizadas
![Java](https://img.shields.io/badge/java-%23ED8B00.svg?style=for-the-badge&logo=openjdk&logoColor=white)
![Spring](https://img.shields.io/badge/spring-%236DB33F.svg?style=for-the-badge&logo=spring&logoColor=white)
![Postgres](https://img.shields.io/badge/postgres-%23316192.svg?style=for-the-badge&logo=postgresql&logoColor=white)
![Swagger](https://img.shields.io/badge/-Swagger-%23Clojure?style=for-the-badge&logo=swagger&logoColor=white)

<br>

## Como rodar o projeto

Para executar este projeto localmente, siga os passos abaixo:

1 - Clone o repositório:
~~~bash
  git clone https://github.com//DevLuigi/RESTful-API.git
~~~

2 - Acesse o diretório do projeto:
~~~bash
  cd substitua/pelo/repositorio/onde/foi/clonado/RESTful-API
~~~

3 - Configure as variáveis de ambiente:
Altere o arquivo application.properties no diretório src/main/resources, e defina as configurações do banco de dados e demais variáveis exigidas pelo projeto. Exemplo básico:
~~~bash
  spring.datasource.url=jdbc:postgresql://localhost:5432/seu_banco
  spring.datasource.username=seu_usuario
  spring.datasource.password=sua_senha
  spring.jpa.hibernate.ddl-auto=update
~~~

4 - Compile o projeto com Maven:
~~~bash
  ./mvnw clean install
~~~

5 - Execute a aplicação:
~~~bash
  ./mvnw spring-boot:run
~~~

6 - Acesse a API:
A aplicação será executada em http://localhost:8080 (por padrão). Você pode testar os endpoints utilizando ferramentas como Postman, Insomnia ou via cURL.

<br>

## Autor

| [<img src="https://avatars.githubusercontent.com/u/89977964?s=400&u=a0d21d2cf86edf9e2f66bcef496882e445f38f6d&v=4" width=115><br><sub>Luigi da Silva Coelho</sub>](https://github.com/DevLuigi) |
| :---: |
