# Go Test Bench
> Intentionally vulnerable go app.

Used Go's standard library, `net/http`, for client/server implentations. For more info on this framework, visit https://golang.org/pkg/net/http/.

## How to Run Locally?
```bash
    go build app.go
    ./app
```

View app at http://localhost:8080

## How to Run Using Docker?
```bash
    # To stand up application with mongo
    docker-compose up -d
    
    # To stop app container and related service containers (ie mongo)
    docker-compose down
```

View app at http://0.0.0.0:8080