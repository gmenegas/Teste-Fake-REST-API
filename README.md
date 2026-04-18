# Teste-Fake-REST-API

## Objetivo

Garantir a integridade, estrutura e regras de negócio da API de listagem de atividades, validando que os dados retornados estejam corretos e consistentes.

---
## Ferramentas utilizadas

- Postman – Execução de testes de API

- JavaScript – Scripts de validação no Postman

- GitHub – Versionamento e organização do portfólio

- NodeJS

- Newman
---

## API usada

[Fake REST API](https://fakerestapi.azurewebsites.net/index.html)

---

## Passo a Passo para uso no postman

1. Abrir Postman

2. Importar ambiente e coleção

3. Executar todos os requests

4. Conferir resultados nos testes

## Passo a Passo para uso no newman

1. Abrir Terminal

2. Executar o comando: newman run "FakeRESTApi.postman_collection.json" -e "baseurl.postman_environment.json" -r html

4. Abrir o arquivo .html na pasta "newman" 

  
