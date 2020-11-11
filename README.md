# Aplicação web em arquitetura de microserviço utilizando Docker 🐳

Esse artigo foi criado por conta da aula "Microserviço na prática - do zero ao push" apresentado no meu curso de Introdução a Docker! Curtiu?
[Eu quero o curso](http://bit.ly/cursoAprendaDockerdoZero)

### Se liga

- É preciso ter o Docker e o Compose instalado
- Testado e aprovado no Linux ❤️

### Como testar?

	git clone https://github.com/ricardoferreiracosta08/microservice-simple-docker-compose.git
	docker-compose up -d

Agora, manda ver 🤘

Qualquer contribuição é bem-vinda!

### Como funciona?

![](./overview.png)

Tecnicamente, é uma aplicação web PHP em arquitetura de microserviço com containers Docker que se conecta 
via API Restful Flask com mapeamento objeto-relacional SQLAlchemy, escrito em Python, com persistência em banco de dados PostgreSQL.

- Mais sobre o assunto no meu blog [AQUI](https://ricardoferreira.site/2020/11/aplicacao-web-microservico-docker-python-php/)
### Referências

Me basei nesse código: [Docker with SQLAlchemy](https://github.com/hmajid2301/articles/tree/master/8.%20Docker%20with%20SQLAlchemy) do 
[@hmajid2301](https://github.com/hmajid2301)
