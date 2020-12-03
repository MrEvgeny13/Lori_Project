# Lori_Project

**Startup instruction:**

1) Create a database (in this case in PostgreSQL) for future tables;

2) Create "db.proreties" in "resources";

3) Fill "db.properties" using a template:

\#jdbc

jdbc.driverClassName=org.postgresql.Driver 

jdbc.url=jdbc:postgresql://localhost:5432/*name of your database* 

jdbc.user=*user name* 

jdbc.pass=*user's password* 


\#hibernate

hibernate.dialect=org.hibernate.dialect.PostgreSQL9Dialect 

hibernate.show_sql=true 

hibernate.hbm2ddl.auto=create 

hibernate.temp.use_jdbc_metadata_defaults = false 
