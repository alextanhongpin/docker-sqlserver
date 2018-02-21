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

## Viewing

To view the SQL on MacOS or Linux, it's recommended to use tools like the SQL Operation Studios.