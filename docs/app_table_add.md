# How to add a new table to app.py
This document outlines steps required to add a new table to app.py python program.
Upon executing this program, new table(s) are created in the target database based on the information added to config.json file.

For every new table, three new scripts are created.

In some cases a processing RowNum table is also created used to report on the file data quality

•	DDL script for the incoming table
•	DDL for the reporting parquet table
•	SQL script to copy data from the incoming into the parquet formatted table
