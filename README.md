\# Database Week 6 Assignment

\## PostgreSQL Backups, Point-in-Time Recovery, and Replication



\### Objective

To practice PostgreSQL database backup, recovery, WAL archiving, and streaming replication.



\### Tasks Completed



1\. \*\*Logical Backup\*\*

&#x20;  - Created a custom-format backup of the `bootcamp` database.

&#x20;  - Verified the backup using `pg\_restore --list`.



2\. \*\*WAL Archiving\*\*

&#x20;  - Configured WAL archiving.

&#x20;  - Verified that WAL files were created.



3\. \*\*Point-in-Time Recovery (PITR)\*\*

&#x20;  - Performed recovery to a specified target time.

&#x20;  - Verified the recovered records in `pitr\_recovery\_demo`.



4\. \*\*Physical Base Backup\*\*

&#x20;  - Created a PostgreSQL base backup.

&#x20;  - Verified the backup files and manifest.



5\. \*\*Streaming Replication\*\*

&#x20;  - Created a replication user.

&#x20;  - Set up a standby PostgreSQL instance.

&#x20;  - Verified that replication was streaming with zero lag at the time of checking.



\### Screenshots



Evidence is available in the `screenshots/` folder:



\- `backup.png`

\- `pitr-recovery.png`

\- `streaming-replication.png`

\- `base-backup.png`



\### Tools Used

\- PostgreSQL 18

\- Git Bash

\- Git and GitHub



\### Conclusion

This lab provided practical experience with PostgreSQL logical and physical backups, WAL archiving, point-in-time recovery, and streaming replication.

