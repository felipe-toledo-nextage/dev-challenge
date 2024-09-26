
<img src="https://github.com/user-attachments/assets/4ffe98d4-7f24-4558-901b-655eb0252954" alt="logobranca" width="600" height="150" />

# Desafio de Programação - Stack Java / Angular /  Node.js / React / React Native

## Objetivo
Desenvolver uma aplicação web ou mobile para gerenciamento de produtos com funcionalidades de cadastro, listagem, edição e exclusão, variando em complexidade conforme o nível do desenvolvedor (Júnior, Pleno, Sênior).

## Instruções Gerais
- Clone o projeto em seu próprio repositório (Não fazer Fork deste repositório).
- Ao concluir, envie o link do repositório para o responsável técnico.
- O projeto deve conter documentação clara e instruções para rodá-lo.
- Para casos do projeto web deve ser responsivo para dispositivos mobiles.
- Será avaliado conceitos de código limpo, modularização do código, boas práticas de arquitetura, utilização adequada de padrões de projeto, legibilidade, organização, e tratamento de erros.

---

## 1. Desafio - Desenvolvedor Júnior (Node.js & React ou React Native)

### Funcionalidades
- **Cadastro de Produtos**
  - Campos obrigatórios: Nome, Preço, Quantidade
  - Campos opcionais: Descrição
  - Validação de todos os campos.
- **Listagem de Produtos**
  - Filtros simples: Nome, Preço
- Funcionalidade de edição e exclusão de produtos.

### Stack Tecnológica
- Front-end: React ou React Native, Typescript, Axios, React Hook Form
- Back-end: Node.js (Express.js, AdonisJS ou NestJS), MySQL / PostgreSQL

### Rotas da API
- `GET /products`: Lista todos os produtos
- `POST /products`: Cadastra um novo produto
  - Campos obrigatórios: Nome, Preço, Quantidade
  - Campos opcionais: Descrição
- `PUT /products/{id}`: Atualiza dados de um produto
- `DELETE /products/{id}`: Exclui um produto

---

## 2. Desafio - Desenvolvedor Pleno (Node.js & React ou React Native)

### Funcionalidades
- **Cadastro de Produtos com Imagem**
  - Campos obrigatórios: Nome, Preço, Quantidade, Imagem
  - Campos opcionais: Descrição
  - Validação avançada de campos (tamanho de texto, tipos de dados).
- **Listagem de Produtos com Filtros Avançados**
  - Paginação e carregamento infinito.
- Funcionalidade de edição e exclusão de produtos.
- **Histórico de Alterações**

### Stack Tecnológica
- Front-end: React ou React Native, Typescript, Axios, React Hook Form
- Back-end: Node.js (AdonisJS ou NestJS), MySQL/PostgreSQL, Redis (opcional)

### Rotas da API
- `GET /products`: Lista todos os produtos com filtros avançados e paginação
- `POST /products`: Cadastra um novo produto com imagem
  - Campos obrigatórios: Nome, Preço, Quantidade, Imagem
  - Campos opcionais: Descrição
- `PUT /products/{id}`: Atualiza dados de um produto e registra alterações
- `DELETE /products/{id}`: Exclui um produto
- `GET /history`: Lista histórico de alterações

---

## 3. Desafio - Desenvolvedor Sênior (Node.js & React ou React Native)

### Funcionalidades
- **Cadastro e Gerenciamento de Produtos**
  - Campos obrigatórios: Nome, Preço, Quantidade, Imagem ( Upload de imagem com preview )
  - Campos opcionais: Descrição
  - Validação avançada de campos (tamanho de texto, tipos de dados).
- **Listagem de Produtos**
  - Filtros avançados com paginação infinita.
- Funcionalidade de edição e exclusão de produtos.
- **Favoritos e Recomendações**
  - Gerenciamento de produtos favoritos e notificações push.

### Stack Tecnológica
- Front-end: React ou React Native, Typescript, React Hook Form, React Query ou Redux Saga o front-end deverá ser hospedado de maneira gratuita na plataforma Vercel no caso de Web.
- Back-end: NodeJS, hospedagem na AWS utilizando o nível gratuito, AWS Lambda para arquitetura serverless, AWS API Gateway e AWS RDS MySQL, AWS RDS PostgreSQL ou AWS DynamoDB como banco de dados.

### Rotas da API
- `GET /products`: Lista todos os produtos com filtros avançados e paginação
- `POST /products`: Cadastra um novo produto com imagem
  - Campos obrigatórios: Nome, Preço, Quantidade, Imagem
  - Campos opcionais: Descrição
- `PUT /products/{id}`: Atualiza dados de um produto e registra alterações
- `DELETE /products/{id}`: Exclui um produto
- `GET /history`: Lista histórico de alterações
- `GET /favorites`: Lista produtos favoritos
- `POST /favorites`: Adiciona produto aos favoritos
- `GET /recommendations`: Lista recomendações

----------

## 1. Desafio - Desenvolvedor Júnior (Java & Angular)

### Funcionalidades
- **Cadastro de Produtos**
  - Campos obrigatórios: Nome, Preço, Quantidade
  - Campos opcionais: Descrição
  - Validação: Todos os campos obrigatórios devem ser preenchidos corretamente.
- Funcionalidade de edição e exclusão de produtos.
- **Listagem de Produtos**
  - Filtros: Nome, Preço
- Funcionalidade de edição e exclusão de produtos.

### Stack Tecnológica
- Front-end: Angular, Typescript, Angular Material
- Back-end: Java com Spring Boot, MySQL/PostgreSQL (Spring Data JPA)

### Rotas da API
- `GET /products`: Lista todos os produtos
- `POST /products`: Cadastra um novo produto
  - Campos obrigatórios: Nome, Preço, Quantidade
  - Campos opcionais: Descrição
- `PUT /products/{id}`: Atualiza dados de um produto
- `DELETE /products/{id}`: Exclui um produto

---

## 2. Desafio - Desenvolvedor Pleno (Java & Angular)

### Funcionalidades
- **Cadastro de Produtos com Imagem**
  - Campos obrigatórios: Nome, Preço, Quantidade, Imagem
  - Campos opcionais: Descrição
  - Validação avançada de campos (tamanho de texto, tipos de dados).
- **Listagem de Produtos**
  - Filtros avançados: Nome, Preço, Quantidade, Data de adição
  - Exibição de imagens dos produtos.
- Funcionalidade de edição e exclusão de produtos.
- **Histórico de Alterações**
  - Visualização de histórico de alterações dos produtos.

### Stack Tecnológica
- Front-end: Angular, Typescript, Angular Material, RxJS
- Back-end: Java com Spring Boot, MySQL/PostgreSQL, Spring Security

### Rotas da API
- `GET /products`: Lista todos os produtos com filtros e paginação
- `POST /products`: Cadastra um novo produto com imagem
  - Campos obrigatórios: Nome, Preço, Quantidade, Imagem
  - Campos opcionais: Descrição
- `PUT /products/{id}`: Atualiza dados de um produto e registra alterações
- `DELETE /products/{id}`: Exclui um produto
- `GET /history`: Lista o histórico de alterações dos produtos

---

## 3. Desafio - Desenvolvedor Sênior (Java & Angular)

### Funcionalidades
- **Cadastro e Gerenciamento de Produtos**
  - Campos obrigatórios: Nome, Preço, Quantidade, Imagem (Com preview)
  - Campos opcionais: Descrição
  - Validação avançada de campos (tamanho de texto, tipos de dados).
- **Listagem de Produtos**
  - Filtros avançados com paginação infinita.
- Funcionalidade de edição e exclusão de produtos.
- **Histórico de Alterações**
- **Favoritos e Recomendações**
  - Gerenciamento de produtos favoritos e recomendações com base no histórico.
- **Notificações Push**

### Stack Tecnológica
- Front-end: Angular, Typescript, Angular Material, RxJS, NgRx
- Back-end: Java com Spring Boot, Spring Cloud, RabbitMQ (opcional), Redis (opcional)

### Rotas da API
- `GET /products`: Lista todos os produtos com filtros avançados e paginação
- `POST /products`: Cadastra um novo produto com imagem e histórico
  - Campos obrigatórios: Nome, Preço, Quantidade, Imagem
  - Campos opcionais: Descrição
- `PUT /products/{id}`: Atualiza dados do produto e registra alterações
- `DELETE /products/{id}`: Exclui um produto
- `GET /history`: Lista histórico de alterações
- `GET /favorites`: Lista produtos favoritos
- `POST /favorites`: Adiciona produto aos favoritos
- `GET /recommendations`: Lista produtos recomendados
---

## Instruções de Implementação
1. Clone o repositório para seu próprio ambiente:
   ```bash
   git clone <url-do-repositorio>
