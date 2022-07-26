# juniper-warp-tokio-postgres-example

## Compile

```
cargo build
```

# Compile + Run

```
cargo run
```

## Database

```
docker run --rm -it -e POSTGRES_PASSWORD=postgres -p 5432:5432 postgres:alpine
```

If you’re using different credentials for your database, be sure to put them in tokio_postgres::connect(). At this point, you can compile and run the server, then open http://localhost:8000/graphiql in your browser to see if it’s working.
