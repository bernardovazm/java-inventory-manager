### CRUD em Java - Sistema de Gestão de Estoque

Sistema simples para gerenciamento de estoque.

**Funções**: Criar, ler, atualizar e deletar produtos.

### Tecnologias

- **Backend**: Spring Boot, Spring Data JPA, Banco de Dados H2
- **Frontend**: HTML, JavaScript, Bootstrap

### Endpoints

- GET: `/api/products` - Obter todos os produtos
- POST: `/api/products` - Criar um produto
- PUT: `/api/products/{id}` - Atualizar um produto
- DELETE: `/api/products/{id}` - Deletar um produto

### Configuração

1. Execute o backend com `mvn spring-boot:run`
2. Para consumir a API, abra `src/resources/static/index.html`.
