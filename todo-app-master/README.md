# REST API Task application in Go 


## Aplication covers the following concepts:
- Development of Web Applications in Go, following the design of the REST API.
- Working with the framework <a href="https://github.com/gin-gonic/gin">gin-gonic/gin</a>.
- The Clean Architecture approach in building the structure of the application. Dependency injection technique.
- Working with Postgres database. Run from Docker. Generation of migration files.
- Application configuration using <a href="https://github.com/spf13/viper">spf13/viper</a> library. Working with environment variables.
- Working with the database using the library <a href="https://github.com/jmoiron/sqlx">sqlx</a>.
- Registration and authentication. Working with JWTs middleware.
- Writing SQL queries.
- Graceful Shutdown

### To start aplication:


```

make build && make run

```


If you are running the application for the first time, you must apply the migrations to the database:

```

make migrate

```
