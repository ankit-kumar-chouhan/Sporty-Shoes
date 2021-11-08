
DESCRIPTION

Project objective:

As a Full Stack Developer, complete the features of the application by planning the development and pushing the source code to the GitHub repository. 
      

Background of the problem statement:

Sporty Shoes is a company that manufactures and sells sports shoes. They have a walk-in store, and now, they wish to launch their e-commerce portal sportyshoes.com.

# Sporty Shoes - SimpliLearn Phase 3 Assessment

## Technologies Used

| Java | 1.8 |
| ------ | ------- |
| Spring Boot | 2.2.10 |
| Lombok  | --- |
| Swagger-ui | 2.7.0 |
| H2 | --- |
| JPA | --- |
| Spring Security Starter | --- | 


## File Structure

```
src
├── main
│   ├── java
│   │   └── com
│   │       └── api
│   │           └── sportyShoes
│   │               ├── SportyShoes.java
│   │               ├── config
│   │               │   ├── SpringSecurityConfig.java
│   │               │   └── SwaggerConfig.java
│   │               ├── controller
│   │               │   ├── CRUDController.java
│   │               │   └── SearchController.java
│   │               ├── exceptionHandler
│   │               │   └── BusinessException.java
│   │               ├── model
│   │               │   ├── PurchaseReport.java
│   │               │   └── Shoe.java
│   │               ├── repository
│   │               │   ├── PurchaseReportRepository.java
│   │               │   └── ShoesRepository.java
│   │               └── service
│   │                   ├── SportyShoesService.java
│   │                   └── impl
│   │                       └── SportyShoesServiceImpl.java
│   └── resources
│       └── application.properties
└── test
    ├── java
    └── resources

16 directories, 13 files
```

## Project Structure

This project uses Spring Boot for Model and Controller Implementation
Availaible apis are -
  - /shoe (CRUD)
  - /purchaseReport (CRUD)
  - /shoe/all
  - /purchaseReport/(category|all|dop)

Current Implementation relies simply on String for storing order list.

It can be extended to utilize many-to-many relationship b/w Shoe and PurchaseReport Entities.

Also for admin authentication spring-security-starter has been used with credentials saved in `application.properties` file.




