# Testes de API usando Cypress 💻

Este projeto abrange testes automatizados para a API Restful utilizando o framework Cypress.

## Pré-requisitos 🛠️

- Visual Studio Code
- Node.js
- Cypress


## Cenários de teste 📋

### Buscar dispositivos 🔍

- **Buscar todos os dispositivos:**
  - Verificar se todos os dispositivos têm as propriedades 'id', 'name' e 'data'.
  - Verificar se o status da resposta é ![Verde](https://via.placeholder.com/15/00FF00/000000?text=+) 200.

- **Buscar dispositivos por id:**
  - Verificar se o dispositivo retornado possui o nome correto.
  - Verificar se o status da resposta é ![Verde](https://via.placeholder.com/15/00FF00/000000?text=+) 200.

- **Buscar dispositivos por id inválido:**
  - Verificar se o status da resposta é ![Vermelho](https://via.placeholder.com/15/FF0000/000000?text=+) 404.
  - Verificar se a mensagem de erro informa que o objeto não existe.

### Cadastrar dispositivos ➕

- **Cadastrar dispositivos com sucesso:**
  - Verificar se o dispositivo foi cadastrado com sucesso.
  - Verificar se o nome do dispositivo é correto.
  - Verificar se o status da resposta é ![Verde](https://via.placeholder.com/15/00FF00/000000?text=+) 200.

- **Cadastrar dispositivos com name vazio:**
  - Verificar se o dispositivo foi cadastrado com sucesso.
  - Verificar se o campo 'name' está vazio.
  - Verificar se o status da resposta é ![Verde](https://via.placeholder.com/15/00FF00/000000?text=+) 200.

### Atualizar objeto 🔄

- **Atualizar objeto por id:**
  - Verificar se o objeto foi atualizado com sucesso.
  - Verificar se o nome do objeto foi atualizado corretamente.
  - Verificar se o status da resposta é ![Verde](https://via.placeholder.com/15/00FF00/000000?text=+) 200.

- **Atualizar objeto por id inválido:**
  - Verificar se o status da resposta é ![Vermelho](https://via.placeholder.com/15/FF0000/000000?text=+) 404.
  - Verificar se a mensagem de erro informa que o objeto não existe.

### Atualizar parcialmente objeto 🔄

- **Atualizar parcialmente objeto por id:**
  - Verificar se o objeto foi atualizado parcialmente com sucesso.
  - Verificar se o nome do objeto foi atualizado corretamente.
  - Verificar se o status da resposta é ![Verde](https://via.placeholder.com/15/00FF00/000000?text=+) 200.

- **Atualizar parcialmente por id inválido:**
  - Verificar se o status da resposta é ![Vermelho](https://via.placeholder.com/15/FF0000/000000?text=+) 404.
  - Verificar se a mensagem de erro informa que o objeto não existe.

## Elaborado por

Guilherme Lobato.

## Aprendizado

Este projeto foi elaborado durante o Bootcamp ao Vivo do Cypress - Dia 1 - 5 PASSOS PARA AUTOMATIZAR API COM CYPRESS ([Assista aqui](https://www.youtube.com/watch?v=aeisYRv1WCg)).

## API Utilizada

Os testes foram conduzidos utilizando a API disponível em [restful-api.dev](https://restful-api.dev/).
