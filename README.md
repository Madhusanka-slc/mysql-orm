# <img src="src/main/resources/db.png"  width="55"/>  ORMapper
#### MYSQL Object Relational Mapping Library 

### How to use this Repo
* First get cloned the repo 
* ```git clone https://github.com/Madhusanka-slc/mysql-orm```
* Open the `pom.xml` via IntelliJ IDEA
* Make sure to the open it as a project, if prompt
* Reload the `pom.xml` file via **Maven Tool Window**
* Run `mvn install` command to install library to m2 directory.
* That's it.
* **Now you can use this orm library**
* **Follow the instructions to use it**
* Add the below dependency in the pom.xml dependencies.

~~~
   <dependency>
         <groupId>lk.ijse.dep9</groupId>
         <artifactId>simple-orm</artifactId>
         <version>1.0.0</version>
   </dependency>
~~~
**Example**
~~~

public class Demo {
    public static void main(String[] args) {
    
    String host="localhost";
    String port="3306";
    String database="db_orm";
    String username="root";
    String password="mysql";
    String packagesToScan="entity";
    
        InitializeDB.initialize(host,port,database,user,password,packagesToScan);
    }
}
~~~
### Version
1.0.0

### License
Copyright © 2022 Chathura Madhusanka. All Rights Reserved. <br>
This project is licensed under the [MIT](LICENSE.txt) license.