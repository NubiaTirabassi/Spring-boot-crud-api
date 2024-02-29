# Spring-boot-crud-api
# API Spring Boot
Esta é uma amostra de API Spring Boot projetada para mostrar operações básicas de CRUD para gerenciamento de usuários. Ela fornece endpoints para criar, recuperar, atualizar e excluir informações de usuário.

# Endpoints
1. Listar Todos os Usuários
URL: /listatodos
Método: GET
Descrição: Recupera uma lista de todos os usuários armazenados no banco de dados.
Resposta:
Status: 200 OK
Corpo: Array JSON contendo informações do usuário.

2. Salvar Usuário
URL: /salvar
Método: POST
Descrição: Salva um novo usuário no banco de dados.
Corpo da Requisição: Objeto de usuário no formato JSON.
Resposta:
Status: 201 Created
Corpo: Objeto JSON contendo as informações do usuário salvo.

3. Excluir Usuário
URL: /deletar
Método: DELETE
Descrição: Exclui um usuário do banco de dados com base no ID de usuário fornecido.
Parâmetros:
iduser: O ID do usuário a ser excluído.
Resposta:
Status: 200 OK
Corpo: Mensagem de sucesso indicando que o usuário foi excluído com sucesso.

# Dependências
Spring Boot
Spring Web
Spring Data JPA
Banco de Dados H2 (embutido)
Spring Boot Starter Test

# Notas
Esta API demonstra o uso de injeção de dependência do Spring Boot, anotações de controlador, mapeamentos de solicitações, métodos HTTP, entidades de resposta e operações básicas de CRUD com repositório JPA.
Ela utiliza um banco de dados H2 embutido para armazenamento de dados.
A API foi projetada para fins de demonstração e pode exigir configuração adicional e tratamento de erros para uso em produção.

Sinta-se à vontade para explorar e contribuir com o código!
