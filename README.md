# Docker sand box environment for Virtuoso Open-Source Edition

## Abstruct

- Boot latest version of [Virtuoso Open-Source Edition](https://vos.openlinksw.com/owiki/wiki/VOS)
- Database and misc configs are created on ./database

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

## How to crean up all database and configs

```bash
docker compose down
rm ./database/*
docker compose up -d
```

## Access to Conductor

http://localhost:8890/

- Account: dba
- Password: (DBA_PASSWORD)
