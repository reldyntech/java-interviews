# Java Technical Assessment

In this assessment, 
* you may use any IDEs (IntelliJ, Eclipse, VS Code etc)
* you may use any database (PostgreSQL, MySQL, H2 etc)

1. Create a public github repository (reldyn-java-test) under your personal account
2. Generate Spring Boot project using https://start.spring.io/ with dependecies that you think is required
3. Create an entity User with the following fields
   * id (UUID)
   * email (NOT NULL, VARCHAR(100))
   * name (NOT NULL)
   * password (NOT NULL, VARCHAR(100))
4. Connect to any database (PostgreSQL, MySQL, H2 etc) and create the table
5. Build the APIs to perform CRUD on the table
   * POST /users
      - Create new user record
   * DELETE /users/{id}
      - Logically delete user record
   * GET /users
      - Get all non deleted user records
   * GET /users/{id}
      - Get specific record
