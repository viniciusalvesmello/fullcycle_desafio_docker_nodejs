## Desafio curso Docker, utilizando Nginx com Node.js (Plataforma FullCycle da Code Education)

### Como executar?

Para executar os containers baixe o projeto e acesse a pasta e execute o comando abaixo.

```
docker-compose up -d
```

### Como visualizar o resultado?

Ao acessar no browser a URL `http://localhost:8080/` será exibida a mensagem abaixo.

#### Mensagem que será exibida

<h1>Full Cycle Rocks!</h1>

1. Nome aleatório

#### Como são gerados e exibidos os nomes?

Toda vez que você acessa a URL são executados os passos abaixo:

* Gera um um nome aleatório utilizando o pacote [faker-br](https://www.npmjs.com/package/faker-br);
* Insere o nome na tabela `people` do `mysql`;
* Recupera todos os nomes na tabela `people` e exibe a lista.