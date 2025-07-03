## 🛠 Tecnologias utilizadas

- Java 21

- Spring Boot 3.5.0

- Spring Security: Para autenticação e autorização.

- JPA (Java Persistence API): Para mapeamento objeto-relacional.

- Hibernate: Implementação da JPA para persistência de dados.

- MySQL: Banco de dados relacional para produção.

- H2 Database: Banco de dados em memória para testes.

- Maven: Para gerenciamento de dependências e build do projeto.

- JWT (JSON Web Token): Para criação de tokens de acesso seguros.
- Heroku: Para deploy e hospedagem da aplicação.

---

## 🧪 Funcionalidades principais

- Autenticação de Usuários: Login e registro com validação de dados e tratamento de erros.

- Gerenciamento de Usuários: CRUD (criação, leitura, atualização e exclusão) de usuários.

- Segurança com JWT: Rotas protegidas que exigem um token de autenticação válido.

- Perfil de Usuário: Endpoint para recuperar os dados do usuário logado de forma segura (sem a senha).

---

## 🧰 Como rodar o projeto localmente

#### ⚙️ Pré-requisitos

- JDK 21 ou superior

- Maven

- Git

---

## ▶️ Instruções

#### Bash:

#### Clone o repositório
git clone https://github.com/rivalixgaming/plataformarivalix-backend.git

#### Acesse a pasta
cd plataformarivalix-backend

#### Instale as dependências
mvn install

#### Execute o projeto
mvn spring-boot:run
O servidor estará rodando em http://localhost:8080.

---

## 🚧 Status do projeto

#### 🛠 Em desenvolvimento: Novas funcionalidades estão sendo implementadas e o projeto segue em evolução.
