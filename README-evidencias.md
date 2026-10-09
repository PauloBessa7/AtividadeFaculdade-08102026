# Evidencias

## Primeiro comando

docker compose up -d

![alt text](image.png)

## Erro na API

![alt text](image-1.png)

## Correções

### Backend
- Variável de ambiente alterada -> PORT: "4000"
- Novo volume para /app/registros

### Frontend
- Adicionando propriedade hostname:"localhost"
- Variável de ambiente alterada -> API_URL: "http://api:4000"
- Adicionar dependencia de com a API

## Container
- Definição de registros

## Comandos depois das correções

![alt text](image-2.png)

![alt text](image-3.png)

![alt text](image-4.png)

![alt text](image-5.png)

## Critério 3

![alt text](image-6.png)

![alt text](image-7.png)

![alt text](image-8.png)