# go-crud-api-postgres
Build a CRUD Rest API in Go using Mux, Postgres, Docker and Docker Compose

## Build and Run app
Build app using command:
```bash
$ docker compose build
```
Run app using command:
```bash
$ docker compose up go-app
```
REST apis
* Create user
```
POST localhost:8000/users
{
    "name":"ABC",
    "email": "abc@gmail.com"
}
```

* Read users
```
GET localhost:8000/users
```

* Read users with id
```
GET localhost:8000/users/{id}
```

* Update user
```
POST localhost:8000/users/{id}
{
    "name":"XYZ",
    "email": "xyz@gmail.com"
}
```

* Delete user
```
DELETE localhost:8000/users/{id}
```

## Reference
[Build a CRUD Rest API in Go using Mux, Postgres, Docker and Docker Compose](https://www.youtube.com/watch?v=aLVJY-1dKz8&list=PLPoSdR46FgI4K36elsmeoUynDUXhjvtEn&index=10)
