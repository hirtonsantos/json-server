# json-server-doit

# Endpoints:

## Registro do usuário:

`POST /register`  

` { {  
	"name": "teste",  
	"email": "teste@teste.com",  
	"password": "123456"  
}`    

## Login do usuário:

`POST /login`  

` { {  
	"email": "teste@teste.com",  
	"password": "123456"  
}`    

## Acesso aos produtos :
# OBS => Necessário autenticação

`GET /products`  

`[  
	{  
		"id": 1,  
		"name": "Hamburguer",  
		"category": "Sanduíches",  
		"price": 14,  
		"img": "https://i.ibb.co/fpVHnZL/hamburguer.png"  
	},  
	{  
		"id": 2,  
		"name": "X-Burguer",  
		"category": "Sanduíches",  
		"price": 16,  
		"img": "https://i.ibb.co/djbw6LV/x-burgue.png"  
	},   
]`    

