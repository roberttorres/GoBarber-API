
  <h2 align = "center"> Go Barber - API &nbsp; <img src = "https://github.githubassets.com/images/icons/emoji/unicode/2702.png" width = "22" height = "22" > </h2>  
</p>  

<p align = "center"> Uma API NodeJS para gerenciamento de agendamentos de serviços de barbearia. </p>


<h2> Proposta da API </h2> 

Essa aplicação é responsável por possibilitar agendamentos de serviços entre clientes e prestadores de serviços. Esse sistema serve tanto para criação de apps de estabelecimentos específicos, quanto para conectar profissionais liberais a seus clientes. <p>
  
<h2> Principais Tecnologias Utilizadas </h2>

<ul>
    <li>
        NodeJS
    </li> 
    <li>
        Docker
    </li> 
    <li>
        Postgres
    </li>    
    <li>
        MongoDB
    </li>    
    <li>
        JWT
    </li> 
    <li>
        Multer
    </li> 
</ul>

<h2> Requisitos de Software &nbsp; <img src = "https://github.githubassets.com/images/icons/emoji/unicode/1f9d0.png" width = "22" height = "22" > </h2>  

<b>Você precisará instalar em sua máquina: </b>
<ul>
    <li>
        NodeJS
    </li>    
    <li>
        Postgres
    </li>  
    <li>
        MongoDB
    </li> 
    <li>
        Docker
    </li> 
</ul>

<b>Recomendável: </b>  

<ul>
    <li>
        Insomnia (fazer requisições à api)
    </li>    
    <li>
        PostBird (gerenciar DB)
    </li>  
    <li>
        Linux (ou Mac)
    </li> 
</ul>

Após o Docker estar devidamente instalado, rode os seguintes comandos no seu terminal:

<ul>
    <li>
      <code> docker run --name redisbarber -p 6379:6379 -d -t redis:alpine </code> ;
    </li>    
    <li>
      <code> docker run --name mongobarber -p 27017:27017 -d -t mongo </code> ;
    </li>  
    <li>
        <code> docker run --name pgbarber -e POSTGRES_PASSWORD=docker -p 5433:5432 -d postgres </code> ;
    </li> 
</ul>

<h2> Instalação </h2>

1. Abra seu terminal em uma pasta qualquer e clone este repositório <code> https://github.com/roberttorres/GoBarber-API.git </code>
2. Navegue até o diretório do servidor: <code> cd backend </code>
3. Rode <code> yarn </code> para instalar todas as dependências
4. Copie o arquivo <code> .env.example </code> e renomeie para <code> .env </code>
5. Insira todos os valores para as variáveis de ambiente no <code> .env </code>
6. Rode <code> yarn dev </code> e <code> yarn queue </code> para iniciar a API no endereço <code> http://localhost:3000 </code>

<h2> <img src = "https://github.githubassets.com/images/icons/emoji/unicode/1f4dd.png" width = "22" height = "22" > Licença </h2>

Esse projeto se encontra sob a licença <b> MIT. </b> Acesse o arquivo <a href="/LICENSE"> LICENSE </a> para mais detalhes.
    
<p align="center"> 
    Made with ❤️ by <a href="https://www.linkedin.com/in/robert-torres1000/">Robert Torres</a>
</p>  
