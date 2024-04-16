Adding a DataSourceID to a Dataset table using PowerBI REST API. Datasource ID is not natively on the JSON response. However, it is used to make the API. Each given source should have a datasourceid to make a relationship between the 2 tables. Each datasource response is different depending on the source used for that dataset (i.e. SQL Server as a source will have a different response than that of Snowflake source).
