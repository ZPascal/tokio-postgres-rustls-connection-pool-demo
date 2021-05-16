# Connecting Securely for PostgreSQL amd using deadpool connection pooler

This project demonstrates how to use [Tokio Postgres](https://crates.io/crates/tokio-postgres) with [Rustls](https://crates.io/crates/rustls) to connect to PostgreSQL over TLS.

## Influenced repositories
- https://github.com/ecliptical/tokio-postgres-rustls-rds-demo

## Command

```bash
env PG.DBNAME=postgres PG.HOST=localhost PG.PORT=6432 PG.USER=postgres PG.PASSWORD=postgres DB_CA_CERT=docker/files/cert/ca.pem RUST_LOG=debug cargo run
```