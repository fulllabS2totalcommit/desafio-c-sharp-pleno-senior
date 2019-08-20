# desafio-c-sharp

- Criar um fork deste repositorio chamado "Fulllab - Desafio C Sharp";

- Realize o desafio, até onde conseguir;

- Qualquer duvida, só perguntar por email;

- Não faça tudo em apenas um COMMIT!

Desafio:

Crie um projeto ASP .NET Web Api, que:

1)Possua um Endpoint que receba um termo de busca e realize uma busca em uma loja vtex, retornando assim a lista de produtos resultante desta busca em JSON.

 - Documentação do search vtex: https://documenter.getpostman.com/view/845/search-103/Hs43#8b71745e-00f9-6c98-b776-f4468ecb7a5e
 - Loja vtex 1: polishop.vtexcommercestable.com.br
 - Loja vtex 2: taco.vtexcommercestable.com.br

2)Crie um banco de dados Redis e guarde o JSON resultante desta busca usando o termo de busca do Redis.
 - Documentação do Redis: https://redis.io/documentation

3)Crie uma estratégia de Cache para buscar no Redis quando o termo de busca já estiver armazenado. Caso contrário buscar busca padrão na Vtex e armazene o resultado no Redis.

4)Crie um banco de dados MySql com uma tabela chamada Visita (id, e-mail, produto, dataAcesso). Obs.: Enviar script do banco.


5)Crie um Endpoint que receba um id de produto e acumule uma visita para este produto na tabela do MySql.

 - Documentação do MySql: https://dev.mysql.com/doc/


6)Crie um Endpoint que receba um id de produto e uma data e retorne a quantidade de visitas daquele produto para a data especificada.


7)Possua uma rota que receba um body contendo título e mensagem e crie uma push notification no One Signal via rest api.

 - Documentação do One Signal: https://documentation.onesignal.com/v3.0/docs/onesignal-api

8)Crie projeto de testes para validar todas os endpoints.

9)Documente o Código fonte.
