# Experimenting bi-driectional replication on PostgreSQL 16+

This repository contains notebook(s) about bidirectional replication on PostgreSQL.

The main goal was to use the new `ORIGIN` argument introduced in PostgreSQL 16.0, to see how it would 
facilitate bidirectional logical replication by not using pglogical anymore, as it was mandatory before that.

## Usage

```
docker compose up -d
```

Then connect to http://localhost:8888 to open Jupyter and start running the notebook.
