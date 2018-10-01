# graph

Final Project Graph of Relation RIN PDII-LIPI (Add File Config)

Minimum Requirement :

    • Glassfish 4

    • Java JDK 8

    • PostgreSQL 9.2

### Test Deploying an Application From the Command Line

1.	To download a copy of the 'graph.war' application.

2.	Save the graph.war file in the directory of your choice. This directory is referred to as sample-dir.

3.	Start Glassfish Server domain before deploy the application. To Start the Default Domain. Run the asadmin start-domain command without an operand:

    > as-install/bin/asadmin start-domain

    The command starts the default domain, domain1.

4.	Use the asadmin deploy command. General command is:

    > as-install/bin/asadmin deploy war-name

    To deploy the matrix.war sample, the command is:

    >  as-install/bin/asadmin deploy sample-dir/graph.war
    
    Normally can be create in /domain1/applications/GraphofRelation/

5.	Access the matrix application by typing the following URL in your browser:

    > http://localhost:8080/GraphofRelation
    
6.	The application's start page is displayed.

See Full Documentation Glassfish : [Doc Glassfish 4](https://javaee.github.io/glassfish/doc/4.0/administration-guide.pdf).

### Config Database

Configure Script To Connect Database PostgreSQL Server in File "config.json" at /GraphofRelation/resources/data/config.json

Example Default Config :

•	host = "IP database PostgreSQL server"

•	port = "port database"

•	dbname = "the name of database"

•	username = "username to access database"

•	password = "password to access database"

•	pathjsonfile = "folder location where json file is stored" (normally it doesn't need to be changed)

** Examples Output Graph of Relation :

