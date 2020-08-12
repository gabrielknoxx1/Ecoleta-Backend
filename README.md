<h1 align="center">
Ecoleta - NLW 1.0 Booster
</h1>

<p align="center">Projeto criado na NLW 1.0 , neste diretório contem a parte da 
api da aplicação </p>

<hr>

## Tecnologias

- [x] Node JS
- [x] TypeScript
- [x] Knex 
- [x] Sqlite 
- [x] Express 
- [x] Express 


## Instalação
Após acessar /server

1. Run `npm install` or `yarn install`.<br />
2. Run `npm start` .<br />
3. Após esse passo confira no terminal a mensagem <b>Server Online</b>.<br />

## Rotas
O arquivo <b>Insomnia_Rotas.json</b> contem a configuração das rotas para serem importadas no <b>Insomnia</b> ou <b>Postman</b>

<b>Get - Listar pontos</b> - Lista os pontos de coleta baseado nos QueryParams <br />
<b>Get - Listar ponto especifico </b> - Lista os pontos de coleta baseado no ID <br />
<b>Get - Listar items</b> - Lista os items disponiveis para serem coletados <br />
<b>Post - Criar ponto de coleta </b> - Cadastra novos pontos de coleta , recebem como request.body <br />

{
	 "name": "Nome do ponto",
    "email": "email",
    "whatsapp": "whatsapp",
    "latitude": -45.87898566,
    "longitude": -36.1818966,
    "city": "São Paulo",
    "uf": "SP",
	  "items":[
			1,2,6
		]
  
}


##Contato
☎(11) 96139-8325
📧byelg.sousa@gmail.com

Redes Sociais

<a href="https://www.linkedin.com/in/gabriel-sousa-5a719893/">
  <img src="https://icomoon.io/icons39f00d9/4/456.svg"></img>
</a>
<a href="https://www.instagram.com/gabrielknoxx">
  <img src="https://icomoon.io/icons39f00d9/4/387.svg"></img>
</a>