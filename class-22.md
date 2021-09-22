# APIs

[Main Page](https://jrdelmu.github.io/reading-notes/)

1. What does REST stand for?
  - Representational State Transfer
2. REST APIs are designed around a ____.
  - resources
3. What is an identifer of a resource? Give an example.
  - A URI that uniquely identifies the resource
  - https://racecars.com/orders/1
4. What are the most common HTTP verbs?
  - GET
  - POST
  - PUT
  - PATCH
  - DELETE
5. What should the URIs be based on?
  - URIs should be based on nouns
6. Give an example of a good URI.
 - https://racecars.com/orders
7. What does it mean to have a ‘chatty’ web API? Is this a good or a bad thing?
 - A chatty API will impose a load on the web server and should be avoided
8. What status code does a successful GET request return?
  - HTTP status code 200 (OK)
9. What status code does an unsuccessful GET request return?
  - HTTP status code 406 (Not Acceptable)
10. What status code does a successful POST request return?
  - HTTP status code 201 (Created)
11. What status code does a successful DELETE request return?
  - HTTP status code 204 (No Content)