# Snippetbox

Follow along "Let's Go" book


## How to run?

Spin up docker container for MySql by 
```
docker-compose up -d
```

and start the server from terminal with

```
go run cmd/web/!(*_test).go
```

If it doesn't work try adding following in your terminal (for MacOS):

```
setopt kshglob
```

If everything works then just point your browser to `http://localhost:4000`

