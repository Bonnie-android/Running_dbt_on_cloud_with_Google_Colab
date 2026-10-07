Setting up and running dbt using Google Colab
RUNNING DBT IN GOOGLE COLAB

Can you set up a full dbt session in Google colab?
Yes 
What is dbt – dbt stands for Data Build Tool. 
dbt Core is a free, open-source command-line tool that lets data teams transform data directly inside their data warehouse using SQL and Jinja. Developed by dbt Labs, it forms the foundation of modern data transformation workflows. The nice thing about dbt is that it runs off of many systems. 
You can create projects on Databricks, Fabric and Snowflake for example. Dbt does this by using adapters. These are analogous to the ODBC and JDBC adapters that were used in the past. They allow dbt to interface with different platforms such as Snowflake and Databricks. To do this you need the right adapter. 
Dbt also excels at documentation and allows easy documentation of complex jobs.

For this project you will run dbt-core, which is open source and free, in Google Colab which is also open source and free.
In addition, you can set up a free student account in Snowflake or Databricks and one of these will be needed for this exercise.
You will need to know your user id, pw, database/catalog, and schema in order to run your queries from dbt.
You will also need some test tables to work with.
These test tables represent the “raw” file data that comes into a data warehouse before any transformation is performed. 
