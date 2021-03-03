# Python-Datapipeline
Injesting Data into Postgres Database using Python

TestData.py
contains code for Generating Dummy Test data(Columns: txid, uid and Amount) using Random in python to a URL using Flask.

Dataloader.py
Reads Data from URL created in TestData.py and injests it to PostGres Database on the local system.
