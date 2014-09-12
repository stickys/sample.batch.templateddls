# Java Batch persistence DDL templates

Persistence templates which are **REQUIRED** for using the Java batch function

## Instructions
1. Download appropriate DDL template for your database type
2. Customize schema, table prefix, and anything else using find/replace
3. Create database tables based on customized DDL.
4. In your server config, define a DataSource pointing to your database (and a JDBC driver def. if necessary)
5. Configure your server's batch persistence by pointing to this DataSource
## Tested Databases

**Note:** This list is intended to capture which DDLs have been used in testing, and not to give a complete test statement regarding database product versions, JDBC driver versions, etc.

- DB2 LUW [batch-db2.ddl](batch-db2.ddl)
- DB2 z/OS [batch-db2-zos.ddl](batch-db2-zos.ddl)
- Apache Derby [batch-derby.ddl](batch-derby.ddl)
- Oracle [batch-oracle.ddl](batch-oracle.ddl)

## TODO
- checkpointdata PK for DB2 z/OS

## References

WLP Beta InfoCenter

`wlp_batch_persistence_config.html`
