# Lakebase Architecture


## Endpoints

| Endpoint | Read-write | Read-only |
| --- | --- | --- |
| Direct connection | `ep-<endpoint-id>.database.<region>.databricks.com` | `ep-<endpoint-id>-ro.database.<region>.databricks.com` |
| PgBouncer | `ep-<endpoint-id>-pooler.database.<region>.<cloud>.databricks.com` | `ep-<endpoint-id>-ro-pooler.database.<region>.<cloud>.databricks.com` |
