# QuatamMart-k: E-commerce Microservices Solution 💻 

QuatamMart-k is an E-commerce solution that leverages the power of Microservice architecture, utilizing Spring Boot and Spring Cloud technologies.

## Services

The solution is composed of the following services:

- API Gateway
- Consul (service registry and config server)
- Authentication
- Product (catalog)
- User
- Order (cart support for authenticated users)



## Development

### Docker

To run the application using Docker, follow these steps:

```bash
$ cd quatamMart-k
$ mvn clean install
$ docker-compose up -d
```

### Maven

To run individual services, you can use Maven. For example, to run the **Gateway** service:

```bash
$ cd quatamMart-k/gateway
$ mvn spring-boot:run
```

### Postman Collection

We provide a Postman collection for easy testing of our microservices. Click the button below to import the collection:

[![Run in Postman](https://run.pstmn.io/button.svg)](https://app.getpostman.com/run-collection/86806c080fe384e60058?action=collection%2Fimport#?env%5Bmicroservices%5D=W3sia2V5IjoiYXV0aGVudGljYXRpb25fdG9rZW4iLCJ2YWx1ZSI6IiIsImVuYWJsZWQiOnRydWUsInNlc3Npb25WYWx1ZSI6IkJlYXJlci4uLiIsInNlc3Npb25JbmRleCI6MH0seyJrZXkiOiJob3N0IiwidmFsdWUiOiJsb2NhbGhvc3QiLCJlbmFibGVkIjp0cnVlLCJzZXNzaW9uVmFsdWUiOiJsb2NhbGhvc3QiLCJzZXNzaW9uSW5kZXgiOjF9XQ==)

## Todo

- [ ] Complete checkout process functionality
- [ ] Integration with Payment Provider

## Licensing

This code is licensed under the [MIT license](LICENSE.md). Please refer to the LICENSE file for more details.
