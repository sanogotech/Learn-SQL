

##  Docs

- https://www.sqlshack.com/how-to-backup-and-restore-mysql-databases-using-the-mysqldump-command/

## Dump
We can generate the backup of the MySQL database using any of the following methods:

  - Generate the backup using mysqldump utility
  - Generate Incremental backups using Binary Log
  - Generate backups using the Replication of Slaves
    
## Command

```

mysqldump -u [user name] –p [password] [options] [database_name] [tablename] > [dumpfilename.sql]

```
