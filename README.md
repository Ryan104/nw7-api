# nw7-api
API for nw7 song sharing app

Boilerplate: https://github.com/aichbauer/express-rest-api-boilerplate#install-and-use

## Getting started
`npm install`
`npm start`

API available at `localhost:2017`


## Endpoints:
Note: `private/*` endpoints require a bearer token auth (`Authorization: Bearer {token}`)

* POST `public/register`
  - username
  - email
  - password
  - password2

* POST `public/login`
  - email
  - password

* GET `private/users`

