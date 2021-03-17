# Tutorial Project with GraphQL and REST APIs with Node.js, MongoDB, Fastify and Swagger

## Tools Used

- Node.js
- MongoDB
- Fastify
- Swagger
- GraphQL

## Tutorial I followed

[Part 1: Creation of REST API](https://www.freecodecamp.org/news/how-to-build-blazing-fast-rest-apis-with-node-js-mongodb-fastify-and-swagger-114e062db0c9/)

[Part 2: Implementation of GraphQL](https://www.freecodecamp.org/news/how-to-build-a-blazing-fast-graphql-api-with-node-js-mongodb-and-fastify-77fd5acd2998/
)

## Remarks

This wasn't my first GraphQL tutorial but I was curious to see how an existing REST API could be converted to GraphQL. I was surprised to find that this project decided to end with both the REST API and the GraphQL server implemented instead of converting the REST API fully. This lined up with the research I've been doing about published GraphQL APIs. Having a published REST API makes a lot more sense with status codes and the learning curve then a GraphQL one. However, a frontend application can easily use GraphQL to access the exact data it needs. Additionally, the `GraphQLList` and using `GraphQLObjectType` was new to me because I had previously used the `buildSchema` method.
