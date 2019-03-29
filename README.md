# DB-Patch-Status
This is a simple script to run to check your Oracle database 18c/12cR2 RU patch status

the SQL script provided will compare the patches applied on the Oracle database Home (binaries) with the DB. for example, if somebody applies Oracle
18c RU (Release Update) on the binaries BUT doesn't apply the patch on the DB-level (using datapatch) the discrepancy will be shown.
the script is using Oracle built-in package DBMS_QOPATCH.
