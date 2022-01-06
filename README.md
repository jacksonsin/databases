# Upload csv to PostgreSQL database
1. In Excel, File/Save As, select CSV, save your current sheet.
2. Transfer to a holding directory on the Pg server the postgres user can access in PostgreSQL:
3. COPY mytable FROM '/path/to/csv/file' WITH CSV HEADER; -- must be superuser

 # Reference
https://www.postgresqltutorial.com/import-csv-file-into-posgresql-table/
