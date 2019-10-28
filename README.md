# hibernate-pcf
How to run the project:
1. Edit file src/main/resources/hibernate.cfg.xml with proper database url, username and password.
2. cf login
3. cf create-service elephantsql turtle SparkDB_Dev
4. cf push
5. cf logs hibernate-pcf --recent
   the console logs will be displayed with User data.
