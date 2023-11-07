# API Rest da aplicação Voll.med
## Construção:
- Passo 1: Criar um repositorio no github com o nome de api.
- Passo 2: Criar um projeto maven em springboot 3.0.0 com a linguagem java 17 e empacotando en jar.
Com as seguintes dependencias: Spring Web, Spring Boot Devtools, Lombok Validation, MySQL Driver, Spring Data JPA e
  Flyway Migration.
- Passo 3: Configurando a string de conexão no banco, usuario e  password.
  
  <pre>
  spring.datasource.url=jdbc:mysql://localhost/vollmed_api
  spring.datasource.username=root
  spring.datasource.password=root
  </pre>

- Passo 4: Criar uma classe para a entidade JPA para o Medico.
- Passo 5: Criar uma Interfarce para o MedicoRepository.
- Passo 6: Criar uma classe uma migration com o node de V1__create-table-medicos.sql para criar uma tablela com o nome 
  de Medico no banco de bados.