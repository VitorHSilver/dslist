# DsListPro
[![NPM](https://img.shields.io/npm/l/react)](https://github.com/VitorHSilver/dslist/blob/main/LICENSE) 

# Sobre o projeto 
About the project

DSList Pro é uma API  construída durante a semana ** INTENSIVÃO JAVA SPRING ** , evento organizado pela [DevSuperior](https://devsuperior.com "Site da DevSuperior").

A aplicação consiste em um sistema de coleção de jogos, onde os jogos são listados por tipos de avaliações , podendo ser alterados de ordem ao arrastar, mudando dinamicamente.


No momento não obtive sucesso em encontrar uma plataforma de hospedagem em Nuvem para a praticidade da demostração da API
Então abaixo tento detalhar por meio a prints das etapas.

## Postman
![Consulta](https://github.com/VitorHSilver/dslist/blob/main/assets/QueryPostman.PNG) 

![Consulta](https://github.com/VitorHSilver/dslist/blob/main/assets/ConsultaH2.png) 

## Após Alteração

![ConsultaAposMudança](https://github.com/VitorHSilver/dslist/blob/main/assets/AfterQuery.jpg) 


## H2
O H2 é um banco de dados em memória que permite todas as operações do CRUD
![H2](https://github.com/VitorHSilver/dslist/blob/main/assets/h2.png) ![H2.1](https://github.com/VitorHSilver/dslist/blob/main/assets/h2.1.png)



## Modelo conceitual
![Modelo Conceitual](https://github.com/VitorHSilver/dslist/blob/main/assets/dslist-model.png)

# Tecnologias utilizadas
Technologies used

- Java
- Spring Boot
- H2
- Postgree
- Docker
- API REST
- Desenvolvimento em Camadas
- Boas Práticas com Padrão de Projetos

## Implantação em produção

- Banco de dados: Postgresql


## Como Testar a API

Antes de começar, certifique-se de ter o seguinte:

1. Faça o download e instale o [Postman](https://www.postman.com/downloads/).

2. Caso você tenha clonado o repositório, não será necessário baixar o arquivo JSON adicional. Caso contrário, baixe o arquivo JSON de teste [Arquivo](https://github.com/VitorHSilver/dslist/blob/main/postman/postman/Dslist.postman_collection.json).

3. Utilize ou crie uma conta no serviço Gmail  para aproveitar todos os recursos da API.

4. Abra o Postman.

5. Na parte superior esquerda do Postman, clique em "Import".

6. Se você baixou o arquivo JSON no passo 2, selecione "Upload File" e selecione o arquivo "Dslist.postman_collection.json". Caso contrário, se você clonou o repositório, o arquivo já deve estar disponível no Postman.

7. Após a importação, você verá uma coleção de solicitações chamada "Dslist". Todas as demonstrações de consulta estarão disponíveis nessa coleção.

8. Agora você pode testar as demonstrações das consultas chamando os diferentes endpoints da API e observando as respostas.



```bash

# clonar repositório
git clone git@github.com:VitorHSilver/dslist.git

# Instale as dependências
cd dslist
./mvnw install

# Execute a aplicação
./mvnw spring-boot:run
```

# Autor

Vitor Henrique da Silva

[Linkedin](https://www.linkedin.com/in/vitor-hsilver)
