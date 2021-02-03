<img src="http://javaops.ru/static/img/logo/javaops_30.png" width="223"/>

Открытый курс для всех желающих приобщиться к живой современной разработке на Java
# [Разработка Spring Boot 2.x HATEOAS приложения (BootJava)](http://javaops.ru/view/bootjava?ref=gh)
## [Программа](http://javaops.ru/view/bootjava#program)

### Java приложения на самом современном и востребованном стеке: Spring Boot 2.x, Spring Data Rest/HATEOAS, Lombok, JPA, H2, ....
Мы создадим с нуля основу любого современного REST веб-приложения: аутентификация и авторизация на основе ролей, регистрация пользователя в приложении, управление своим профилем и администрирование пользователей.

### Examples:

#### GET http://localhost:8080/api
#### GET http://localhost:8080/api/users
#### GET http://localhost:8080/api/users/1
#### GET http://localhost:8080/api/users/search
#### GET http://localhost:8080/api/users/search/by-email?email=User@gmail.com
#### GET http://localhost:8080/api/users/search/by-lastname?lastName=Admin
#### GET http://localhost:8080/api/users/search/by-lastname?lastName=last
#### POST http://localhost:8080/api/users
Content-Type: application/json

{
"email": "test@test.com",
"firstName": "Test",
"lastName": "Test",
"password": "test",
"roles": [ "ROLE_USER"]
}

#### PATCH http://localhost:8080/api/users/1
Content-Type: application/json

{
"lastName": "User+Last"
}

#### GET http://localhost:8080/api/account