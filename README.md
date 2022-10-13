# roadtokubernetes/psql

A minimal psql client for your projects.

The versions are largely based on [the official versions](https://www.postgresql.org/support/versioning/).

```dockerfile
FROM roadtokubernetes/psql:latest

RUN psql
```

```dockerfile
FROM roadtokubernetes/psql:14

RUN psql
```