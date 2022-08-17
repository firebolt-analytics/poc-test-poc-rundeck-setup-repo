# POC Repo Template


## Files and Directories
* original_files - Original POC Artifacts
* firebolt_implementation - Firebolt SQL. SQL files in subdirectores are executed in order. Prefixing the SQL files with numbers can create ordering (001_External_Tables.sql, 002_Firebolt_Tables.sql, etc.)
  * schema/ - DDL for Firebolt External Tables
  * ingest/ - DDL for Firebolt tables (and indexes)
  * queries/ - Refactored Firebolt queries

## Ignored Directories
* data - data should not be stored in Bitbucket, so this directory is Ignored
