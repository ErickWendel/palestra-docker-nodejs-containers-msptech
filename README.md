## Communication between containers

- When the Heroes Postgres API receives new heroe, it sends to another container (MongoDB API) to register this heroe too
- Hot reload integrated with Typescript to any alterations are reflected to container and refresh API with new code.
- Integration with Redis pub/sub to send messages and objects

Original Repositories

- [https://github.com/ErickWendel/nodejs-with-mongodb-api-example](https://github.com/ErickWendel/nodejs-with-mongodb-api-example)
- [https://github.com/ErickWendel/nodejs-with-postgres-api-example](https://github.com/ErickWendel/nodejs-with-postgres-api-example)

## Running

`docker-compose up`
