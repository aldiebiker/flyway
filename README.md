# flyway

## Postgres setup

`docker run -d   -p 5432:5432   --name postgres     -e POSTGRES_PASSWORD=mysecretpassword     -e PGDATA=/Library/PostgreSQL/12/data/   postgres`

## Convention over Configuration

## command line

`mvn  clean spring-boot:run`

## Demo use cases

- First run
- Wrong file version in dev
    - Migration already done (clean disabled)
- Wrong file version in prod
    - Migration already done (clean enabled)


