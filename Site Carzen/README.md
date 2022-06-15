<div id="top"></div>



<!-- Icones das redes sociais -->

<div class="social" >
    <a href="https://www.instagram.com/carzenbr/" >
    <img class = "icons" src="https://carzen.com.br/assets/svg/icon-instagram.svg">
    </a>
    <a href="https://www.facebook.com/carzenbr">
    <img class = "icons" src="https://carzen.com.br/assets/svg/icon-facebook.svg">
    </a>
    <a href="https://www.youtube.com/channel/UC8C5ROCZhcUB89vaysn7_Rg">
    <img class = "icons" src="https://carzen.com.br/assets/svg/icon-youtube.svg">
    </a>
</div>


<!-- CARZEN LOGO + Descrição -->
<br />
<div align="center">
  <a href="https://carzen.com.br">
    <img src="https://carzen.com.br/assets/svg/logo-gradient.svg" alt="Logo" width="380" height="80">
    </a>

  <h3 align="center">Documentação</h3>

  <p align="center">
     para desenvolvedores do site Carzen, Painel administrativo e Ms Integração
    <br />
    <br /> 
    <!-- Sites do carzen-->
    <a class="sitecarzen" href="https://carzen.com.br/?target=_blank" target="_blank" >Site Carzen</a>
    ·
    <a class="sitecarzen" href="https://painel.carzen.com.br/?target=_blank" target="_blank" >Painel administrativo Carzen</a>
  </p>
</div>
<br>


<!-- Menu de conteudo da documentação -->
<div class="summary">
<details>
  <summary id="menu">Conteudos da documentação</summary>
  <ol>
    <li>
      <a href="#site-carzen">Carzen site para clientes</a>
      <ul>
        <li><a href="#front-end">Front-end</a></li>
        <li><a href="#back-end">Back-end</a></li>
        <li><a href="#banco-de-dados">Banco de dados</a></li>
      </ul>
    </li>
    <li>
      <a href="#painel-administrativo-carzen">Painel administrativo Carzen</a>
      <ul>
        <li><a href="#front-end-do-painel">Front-end</a></li>
        <li><a href="#back-end-do-painel">Back-end</a></li>
        <li><a href="#banco-de-dados-do-painel">Banco de dados</a></li>
      </ul>
    </li>
    <li>
      <a href="#ms-integração">MS integração</a>
      <ul>
        <li><a href="#back-end-ms-integração">Back-end</a></li>
        <li><a href="#banco-de-dados-ms-integração">Banco de dados</a></li>
      </ul>
    </li>
    <li><a href="#tecnologias">Tecnologias usadas.</a></li>
    <li><a href="#contato">Contato.</a></li>
  </ol>
</details>
</div>
<br>
<hr>

<!-- Site Carzen -->
## Site Carzen

<div class='sitecarzen'>
    <img src="https://media.discordapp.net/attachments/976861084302581800/985997049877118976/unknown.png?width=963&height=498" alt="site-carzen" width="420" height="220">
</div>

Neste site é onde o cliente acessa para realizar consultas e comprar seus produtos.

Como foi feito :
* Neste site foi ultizado Angular para o front-end com primeng.
* Para o back-end foi usado Java nativo com lombok para getters & setters.
* Com o banco de dados postgreSQL.

<br>

### Front-end

Para documentação do front-end, com suas rotas mais detalhadas acesse :

 * [Documentação site carzen](https://github.com/cconferi/Documentacao-carzen/blob/master/Site%20Carzen/Documentao-site-carzen.pdf)

 Contem um arquivo em formato PDF  mostrando a url acessada, junto com a rota e o front end que é mostrado no site.

<br>

### Back-end

Para documentação detalhando as rotas chamadas pelo backend foi usado o Swagger.
É possivel acessar a documentaçao do swagger utilizando docker atraves do passo-a-passo mostrando em:

* [Docker swagger ui master](https://github.com/cconferi/Documentacao-carzen/tree/master/Site%20Carzen/docker-swagger-ui-master)

Ou tambem é possivel abrir o arquivo do swagger atraves do [Swagger Editor](https://editor.swagger.io/) utilizando o arquivo:

* [swaggerEditor-site.yaml](https://github.com/cconferi/Documentacao-carzen/blob/master/Site%20Carzen/swaggerEditor-site.yaml)

**Obs:** Para fazer testes de chamadas de rotas abrindo o .yaml via  [Swagger Editor](https://editor.swagger.io/), é preciso rodar o sistema localmente.

<br>

### Banco de dados

Para detalhamento das tabelas do banco de dados, basta acessar : 

* [Tabelas db Carzen](https://github.com/cconferi/Documentacao-carzen/tree/master/Escritorio%20de%20TI%20-%20Comentarios%20banco%20de%20dados/Tabelas%20db%20Carzen)

Nesta pasta ira conter todas as tabelas que contem no banco de dados,comentadas a função da tabela, das colunas e seu o relacionamento da tabela.

<br>

<p align="right">(<a href="#top">Volte para o inicio ⇡ </a>)</p>

<hr>
<br>

<!-- GETTING STARTED -->
## Painel Administrativo Carzen


Ferramenta desenvolvida exclusivamente voltada ao atendimento operacional.

</p>Sendo possivel visualizar informações de forma macro um todo ou somente um cadastro especifico de cliente, tendo como usabilidade opção de compras, consultas e cadastro.

<br>

[Painel Carzen](https://painel.carzen.com.br/login )
 


<div class='sitepainelcarzen'>
    <img src="https://media.discordapp.net/attachments/976168464924409946/986246154025070612/painel_carzen.png?width=859&height=325" alt="site-carzen" width="420" height="220">
</div>



Como foi feito:

* Neste painel foi ultizado Angular para o front-end com primeng.

* Para o back-end esta ultilizando Java com Quarkus e lombok para getters e setters.

* Com o banco de dados postgreSQL.

<br>

### Front-End do painel

Para documentação do front-end, com suas rotas mais detalhadas acesse :

 * [Documentação site carzen](https://github.com/cconferi/Documentacao-carzen/blob/master/Painel-Carzen/documenta%C3%A7%C3%A3o%20painel%20frontend%20%E2%86%92%20painel%20backend%20%E2%86%92%20webservice%20backend.pdf)

 Contem um arquivo em formato PDF  mostrando a url acessada, junto com a rota e o front end que é mostrado no site.

<br>

### Back-End do painel

Na documentação back-end possui Possui o swagger docker-compese e o readme


* [Docker swagger ui master](https://github.com/cconferi/Documentacao-carzen/tree/master/Painel-Carzen/docker-swagger-ui-master)
Para o passo a passo para encontrar o Swagger no Doc abra o Readme.
Ou, pode visualizar o mesmo no site [https://editor.swagger.io/]

<br>

### Banco de Dados do painel

Para detalhamento das tabelas do banco de dados, basta acessar :

* [Tabelas Banco de Dados](https://github.com/cconferi/Documentacao-carzen/tree/master/Escritorio%20de%20TI%20-%20Comentarios%20banco%20de%20dados/tabelas%20db%20Painel%20Carzen)

Nesta pasta ira conter todas as tabelas que contem no banco de dados,comentadas a função da tabela, das colunas e seu o relacionamento da tabela. 

<br>
<p align="right">(<a href="#top">Volte para o inicio ⇡ </a>)</p>

<hr>

<br>


<!-- MS integração -->
## MS integração


<br>


### Back-end Ms integração

Para documentação detalhando as rotas chamadas pelo backend foi usado o Swagger.
É possivel abrir o arquivo do swagger atraves do [Swagger Editor](https://editor.swagger.io/) utilizando o arquivo:

* [swagger_5-msintegracao formatado.yaml](https://github.com/cconferi/Documentacao-carzen/blob/master/ms-integra%C3%A7%C3%A3o%20-%20DOC-API/swagger_5-msintegracao%20formatado.yaml)

**Obs:** Para fazer testes de chamadas de rotas abrindo o .yaml via  [Swagger Editor](https://editor.swagger.io/), é preciso rodar o sistema localmente.

<br>

### Banco de dados Ms integração

No banco de dados do Ms integração foi usado mongoDB.
Para visualizar o diagrama das tabelas basta clicar em:
 * [MRN_msintegracao](https://github.com/cconferi/Documentacao-carzen/blob/master/ms-integra%C3%A7%C3%A3o%20-%20DOC-API/MRN_msintegracao%20(1).pdf)

Tem tambem alguns exemplos em:
 * [Exemplos](https://github.com/cconferi/Documentacao-carzen/tree/master/ms-integra%C3%A7%C3%A3o%20-%20DOC-API/Exemplos)

<br>
<p align="right">(<a href="#top">Volte para o inicio ⇡ </a>)</p>
<hr>
<br>


<!-- Tecnologias usadas no sistema -->
## Tecnologias

Todas tecnologias e IDE's usada no projeto.

* [Angular](https://www.java.com/pt-BR/)
* [Java nativo ](https://www.java.com/pt-BR/ )
* [Java w/ Quarkus ](https://quarkus.io/ )
* [Lombok ](https://projectlombok.org/ )
* [PrimeNg ](https://www.primefaces.org/primeng/ )
* [Eclipse ](https://www.eclipse.org/downloads/ )
* [VsCode](https://code.visualstudio.com/ )
* [WordPress](https://wordpress.com/pt-br/ )


<p align="right">(<a href="#top">Volte para o inicio ⇡ </a>)</p>


<hr>
<br>

<!-- CONTATO -->
## Contato

<p>Union Solutions</p>
<p>Escritorio de t.i </p>
<a href = "mailto: ti@unionsolutions.com.br">ti@unionsolutions.com.br
</a>
<p>Whatspp: (27) 99840-4918



<p align="right">(<a href="#top">Volte para o inicio ⇡ </a>)</p>



