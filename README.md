# Spring Security with JWT in Spring Boot

https://www.youtube.com/watch?v=-HYrUs1ZCLI

Example of JTW to secure the REST endpoints 

- '/token' POST method that generates the JWT token based on the JSON sent: '{ "username": "name", "id": 123, "role": "admin"}' 
- '/rest/hello' Requires the JWT Token with Header 'key - "Authorisation"' and 'value - "Token [JWT_Token]"'