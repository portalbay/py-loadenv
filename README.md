# py-loadenv
A sample python script to load environment variables with either a .env file or defined environment variables.

```
import os  
from dotenv import load_dotenv 
load_dotenv() 
sqlsrv_db_host = os.getenv('sqlsrv_db_host') 
sqlsrv_db_user = os.getenv('sqlsrv_db_user') 
sqlsrv_db_password = os.getenv('sqlsrv_db_password') 
sqlsrv_db_database = os.getenv('sqlsrv_db_database') 
mydb = mysql.connector.connect( 
  host=sqlsrv_db_host, 
  user=sqlsrv_db_user, 
  password=sqlsrv_db_password, 
  database=sqlsrv_db_database 
) 
```
