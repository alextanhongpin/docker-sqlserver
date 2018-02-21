# Running Docker


## Build

```bash
$ docker build -t alextanhongpin/sqlserver .
```

## Run

```bash
$ docker-compose up -d
```


## Exec

```bash
$ docker exec -it 526657ca3b70 /opt/mssql-tools/bin/sqlcmd -S localhost -U sa -P 'Qwerty12345'
```