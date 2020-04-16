# Restful API with Node, Koa, and PostgreSQL

## Getting started

This project is based on this guide - [Building a RESTful API with Koa and Postgres](http://mherman.org/blog/2017/08/23/building-a-restful-api-with-koa-and-postgres)

## Want to use this project?

1. Fork/Clone
1. Install dependencies - `npm install`
1. Fire up Postgres and Redis on the default ports
1. Create two local Postgres databases - `koa_api` and `koa_api_test`
1. Migrate - `knex migrate:latest --env development`
1. Seed - `knex seed:run --env development`
1. Sanity check - `npm start`
1. Test - `npm test`
