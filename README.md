
<img src="https://github.com/user-attachments/assets/4ffe98d4-7f24-4558-901b-655eb0252954" alt="logobranca" width="600" height="150" />

# Desafio de Programação - Stack Java / Angular e Node.js / React

## Objetivo
Este repositório contém desafios de programação para desenvolvedores de diferentes níveis (Júnior, Pleno e Sênior), envolvendo a criação de uma aplicação web ou mobile para o gerenciamento de produtos. Dependendo do nível, as funcionalidades variam em complexidade e uso de tecnologias avançadas.

## Instruções Gerais
- **Não faça um fork deste repositório.** Em vez disso, clone o projeto para seu próprio repositório.
- Após finalizar o desafio, encaminhe o link do repositório para o responsável técnico.
- Certifique-se de que o projeto esteja devidamente documentado com as instruções para rodá-lo.

## 1. Desafio - Desenvolvedor Júnior (Java & Angular)
### Objetivo
Desenvolver uma aplicação web básica para gerenciamento de produtos, utilizando Angular no front-end e Java com Spring Boot no back-end.

### Funcionalidades
1. **Cadastro de Produtos:**
   - Campos: Nome (obrigatório), Descrição (opcional), Preço (obrigatório), Quantidade (obrigatório)
   - Validação dos campos
2. **Listagem de Produtos:**
   - Filtros simples (nome e preço)
   - Funcionalidade para editar e excluir produtos

### Stack Tecnológica
- **Front-end:** Angular, Typescript, Angular Material, HttpClient
- **Back-end:** Java com Spring Boot, MySQL ou PostgreSQL (Spring Data JPA)

### Funcionalidades da API
- `GET /products`: Lista todos os produtos
- `POST /products`: Cadastra um novo produto
- `PUT /products`: Atualiza dados de um produto
- `DELETE /products`: Exclui um produto

---

## 2. Desafio - Desenvolvedor Pleno (Java & Angular)
### Objetivo
Desenvolver uma aplicação web avançada com funcionalidades adicionais para o gerenciamento de produtos.

### Funcionalidades
1. **Cadastro de Produtos com Imagem**
   - Validação avançada dos campos
2. **Listagem de Produtos:**
   - Filtros avançados (nome, preço, quantidade, data de adição)
   - Exibição de imagens dos produtos
3. **Histórico de Alterações:**
   - Visualização de alterações nos produtos

### Stack Tecnológica
- **Front-end:** Angular, Typescript, Angular Material, RxJS
- **Back-end:** Java com Spring Boot, MySQL ou PostgreSQL (Spring Data JPA e Spring Security)

### Funcionalidades da API
- `GET /products`: Lista produtos com filtros e paginação
- `POST /products`: Cadastra um novo produto com imagem
- `PUT /products`: Atualiza dados de um produto e registra alterações
- `DELETE /products`: Exclui um produto
- `GET /history`: Lista histórico de alterações

---

## 3. Desafio - Desenvolvedor Sênior (Java & Angular)
### Objetivo
Desenvolver uma aplicação web robusta e escalável com funcionalidades avançadas.

### Funcionalidades
1. **Cadastro e Gerenciamento de Produtos:**
   - Upload de imagem com preview
2. **Listagem de Produtos:**
   - Filtros avançados e paginação infinita
3. **Histórico de Alterações**
4. **Favoritos e Recomendações:**
   - Gerenciamento de favoritos e recomendações baseadas no histórico
5. **Notificações Push**

### Stack Tecnológica
- **Front-end:** Angular, Typescript, Angular Material, RxJS, NgRx
- **Back-end:** Java com Spring Boot e Spring Cloud, RabbitMQ (opcional), Redis (opcional)

### Funcionalidades da API
- `GET /products`: Lista produtos com filtros avançados e paginação
- `POST /products`: Cadastra um novo produto com imagem e histórico
- `PUT /products`: Atualiza dados do produto e registra alterações
- `DELETE /products`: Exclui um produto
- `GET /history`: Lista o histórico de alterações
- `GET /favorites`: Lista produtos favoritos
- `POST /favorites`: Adiciona produto aos favoritos
- `GET /recommendations`: Lista produtos recomendados

---

## 1. Desafio - Desenvolvedor Júnior (Node.js & React)
### Objetivo
Desenvolver uma aplicação básica para gerenciamento de produtos utilizando React ou React Native no front-end e Node.js no back-end.

### Funcionalidades
1. **Cadastro de Produtos:**
   - Validação de campos (Nome, Preço, Quantidade)
2. **Listagem de Produtos:**
   - Filtros simples (nome e preço)
   - Edição e exclusão de produtos

### Stack Tecnológica
- **Front-end:** React ou React Native (Typescript), Axios, React Hook Form
- **Back-end:** Node.js (Express.js, AdonisJS ou NestJS), MySQL ou PostgreSQL (Sequelize)

### Funcionalidades da API
- `GET /products`: Lista todos os produtos
- `POST /products`: Cadastra um novo produto
- `PUT /products`: Atualiza dados de um produto
- `DELETE /products`: Exclui um produto

---

## 2. Desafio - Desenvolvedor Pleno (Node.js & React)
### Objetivo
Desenvolver uma aplicação web avançada para gerenciamento de produtos.

### Funcionalidades
1. **Cadastro de Produtos com Imagem**
2. **Listagem de Produtos com Filtros Avançados:**
   - Paginação e carregamento infinito
3. **Histórico de Alterações**

### Stack Tecnológica
- **Front-end:** React ou React Native (Typescript), Axios, React Hook Form
- **Back-end:** Node.js (AdonisJS), MySQL ou PostgreSQL, Redis (opcional)

---

## 3. Desafio - Desenvolvedor Sênior (Node.js & React)
### Objetivo
Desenvolver uma aplicação web robusta e escalável com React ou React Native e Node.js (NestJS).

### Funcionalidades
1. **Cadastro e Gerenciamento de Produtos:**
   - Upload de imagem com preview
2. **Listagem de Produtos:**
   - Filtros avançados e paginação infinita
3. **Favoritos e Recomendações:**
   - Gerenciamento de favoritos e notificações push

### Stack Tecnológica
- **Front-end:** React ou React Native (Typescript), React Hook Form
- **Back-end:** Node.js (NestJS e Clean Architecture), PostgreSQL ou MySQL (TypeORM), RabbitMQ (opcional), Redis (opcional)

### Funcionalidades da API
- `GET /products`: Lista produtos com filtros avançados e paginação
- `POST /products`: Cadastra um novo produto com imagem
- `PUT /products`: Atualiza dados e registra alterações
- `DELETE /products`: Exclui um produto
- `GET /history`: Lista histórico de alterações
- `GET /favorites`: Lista produtos favoritos
- `POST /favorites`: Adiciona produto aos favoritos
- `GET /recommendations`: Lista recomendações

---

## Instruções de Implementação
1. Clone o repositório para seu próprio ambiente:
   ```bash
   git clone <url-do-seu-repositorio>
