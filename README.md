# Docker sand box environment for Virtuoso Open-Source Edition

## Abstruct

- Boot latest version of Virtuoso-7
- Database and misc configs is created on ./database

## Preparation

```
cp virtuoso.env.sample virtuoso.env
```

You can change any passwords in vituoso.env

## How to start virtuoso

```bash
docker compose up # Boot on forground
```

```bash
docker compose up -d # Boot on background
```

## How to stop virtuoso

```bash
Ctrl+C # for forground
```

```bash
docker compose down # for background
```

## Access to Conductor

http://localhost:8890/

- Account: dba
- Password: <your DBA_PASSWORD>
