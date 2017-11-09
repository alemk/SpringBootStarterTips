# SpringBootStarterTips
Tips for starting your Spring Boot project 
Setting up 
---------------------------
1. Select your dependencies
2. Put in additional dependencies (NekoHTML, Thymeleaf) 
```
<!-- https://mvnrepository.com/artifact/net.sourceforge.nekohtml/nekohtml -->
<dependency>
    <groupId>net.sourceforge.nekohtml</groupId>
    <artifactId>nekohtml</artifactId>
</dependency>
```
```
<!-- https://mvnrepository.com/artifact/org.thymeleaf.extras/thymeleaf-extras-springsecurity4 -->
<dependency>
    <groupId>org.thymeleaf.extras</groupId>
    <artifactId>thymeleaf-extras-springsecurity4</artifactId>
    <version>2.1.2.RELEASE</version>
</dependency>
```

3. Setup your application properties file (database connections and URLs, thymeleaf configuration, server timeouts, etc.)
   - Write them all down so you have a checklist! 
4. Create your database 
5. Run your application 


Starting out 
---------------
1. Plan your software - M, V, C: 
   - Create an IPO diagram (have at least a basic one before you start) 
   - Map out your entities 
   - Create paths for your controller
   - Determine interactions for modification and deletion 

2. Decide on a UI template to use 

3. Plan out each screen and associated actions 

4. Start building your application 

5. Keep referring to your checklist! 


