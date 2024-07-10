# Desafio de Desenvolvimento Full Stack

## Descrição

O objetivo deste desafio é desenvolver um sistema de controle de estoque de produtos com um backend em (Java/Kotlin ou NodeJs) e um frontend em React. O sistema deve ser capaz de integrar-se com a API pública de [REST Countries](https://restcountries.com/) para agregar informações de localidade dos fornecedores dos produtos cadastrados.

## Funcionalidades do Sistema

### Backend

O backend deve expor APIs para um CRUD de Produtos e Fornecedores. A estrutura do banco de dados deve contemplar as seguintes entidades:

#### Produto

- ID (UUID)
- Nome
- Descrição
- Preço
- Quantidade
- Categoria
- Fornecedor
- Data de Criação

#### Fornecedor

- ID (UUID)
- Nome
- Código do País

### Requisitos de Backend

#### Obrigatório:

- Implementação em Java/Kotlin ou NodeJs
- Utilização do Spring Boot caso implementação for em Java/Kotlin
- Uso de banco de dados relacional (e NoSQL, se necessário)
- Documentação da API com Swagger
- Testes automatizados
- Inclusão de um arquivo `README.md` com instruções para executar a aplicação e os testes

#### Desejável:

- Filtragem, paginação e ordenação na listagem de produtos
- Autenticação via JWT
- Cache
- Dockerfile ou Docker Compose

### Integração com API Pública

- API pública: [REST Countries](https://restcountries.com/)
- Utilizar a API para agregar informações de países nos fornecedores

### Frontend

O frontend deve ser desenvolvido em React e deve incluir componentes de acordo com especificações de um design system. A aplicação deve ter uma página de listagem de produtos com capacidade de filtragem e edição.

### Material

- [Handoff dos componentes](https://xd.adobe.com/view/9789f7fc-9a9f-49b6-a434-0cd07f25c991-c2da/)

### Requisitos de Frontend

#### Obrigatório:

- Implementação em React
- Aplicação de um tema pré-definido no CSS com tokens de cor e espaçamento
- Criação de componentes baseados no design system fornecido
- Campo de filtro para listar produtos por nome, categoria, nome do fornecedor e região do fornecedor
- Inclusão de um arquivo `README.md` com instruções para executar a aplicação

### Estrutura do Sistema

**Listagem de Produtos**
- Tabela para exibir os produtos
- Funcionalidade de filtragem

**OBS: Disponibilizar o código-fonte em um repositório público no GitHub.**

_Estamos ansiosos para ver suas habilidades em ação e como você pode contribuir para nosso time! Boa sorte!_
