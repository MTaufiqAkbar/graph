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

**Example Default Config :**

![config](https://user-images.githubusercontent.com/40910746/46299692-1c15ef80-c5cc-11e8-9c7b-8befc9891e74.PNG)

    • host = "IP database PostgreSQL server"

    • port = "port database"

    • dbname = "the name of database"

    • username = "username to access database"

    • password = "password to access database"

    • pathjsonfile = "folder location where json file is stored" (normally it doesn't need to be changed)

### **Example Output Graph of Relation :**

![gambar 1](https://user-images.githubusercontent.com/40910746/46299773-4a93ca80-c5cc-11e8-9b8d-1d83883ef5bc.PNG)

![gambar 2](https://user-images.githubusercontent.com/40910746/46299795-5bdcd700-c5cc-11e8-9d8c-c119b97d212d.PNG)

![gambar 3](https://user-images.githubusercontent.com/40910746/46300018-e32a4a80-c5cc-11e8-8124-2b15afe1f188.PNG)

![gambar 4](https://user-images.githubusercontent.com/40910746/46300027-e9b8c200-c5cc-11e8-8ebc-990355b6ff11.PNG)

