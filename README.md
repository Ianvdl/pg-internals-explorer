# Introduction

This is a work-in-progress fork of the repo at [hlinnaka/pg-internals-explorer](https://github.com/hlinnaka/pg-internals-explorer).

# Building

Run `make` in the repo directory. 

# Running

The current version from the upstream only allows you to specify connection parameters via environment variables. For example, to connect to the `postgres` database, run:

```
export PGDATABASE='postgres'
./pg_internals_explorer
```

The complete list of variables is [documented](https://www.postgresql.org/docs/current/libpq-envars.html).
