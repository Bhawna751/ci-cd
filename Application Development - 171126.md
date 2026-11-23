### Application Development - 17/11/26



https://github.com/Bhawna751/testrepo.git



1. local git repo creation
2. creating of files
3. add to repo local
4. creating remote repo
5. pushing local repo content to remote content



Q1) create local file testing.txt with message "hello world" txt file and push to remote git hub

&#x20;

use case 2:

1. clone remote repo to local
2. add one more file or modify any existing file
3. push to local git
4. push to remote git



How to use GitHub Copilot:

* enter repo -> chat with copilot
* create a java program to manage employee details. including employee id, name, department and salary provide options to add, display and search employees
* add update employee deteails and employee delete in code
* analyze this java code, identify runtime errors, explain their root causes and provide the corrected code without changing the intended functionality.
* do the code review of above generated code
* Code Refactoring: refactor this code using oop principles. create separate methods for hra, da, pf and salary calculation. improve readability and maintainability without changing the output
* review this java code and identify bugs, security vulnerabilities, performance issues and coding standard violations. suggest improvements following java best practices.





&#x20;===========================





#### Application logging fundamentals:

* logging means recording everything an app does while running

##### Flow of logging in Java Frameworks:

* java calls logger.info("Message") or something, it's the entry point
* **Logger:** decides whether the log should be processes based on its log level.
* **Appender:**  responsible for sending logs to a destination
* **Layout:** defines the format of log message
* **Destinations:** *console (print logs to console) /  Application File (writes logs to a static file) **{1 TB} /** Rolling file (creates new files based on size/date to prevent overflows)*



##### Log4j VS Log4j2



* Log4j is java logging framework
* log4j2 is modern gen apache **(USE THIS)**



\*\*Logging Levels (\*\*severity increases as you go down)

* TRACE- detailed info used for step-by-step debugging {entering a method, variable values, loop iterations}
* DEBUG - debugging info useful during developement {user record fetched from database}
* INFO - general application events that indicate normal operation {application started successfully}
* WARN - something unexpected happened, but application can continue {database connection is slow}
* ERROR - a significant problem occured and an operation failed {failed to process payment}
* FATAL - critical error causing application shutdown or unusable state {application cannot start because config file is missing}



create directory loggerrun

go to vscode

create maven project



==============================

# Application Development Fundamentals - 18/11/26

### 

Module 1: Application Architecture Fundamentals : Understanding how modern applications are structured, connected and deployed



**What is application architecture?**

* how software components are organized and communicate
* defines responsibilities, dependencies, communication paths and deployment boundaries
* building blocks-> user interface, application services, data storage and external integrations





#### Dispatcher Servlet:

* acts as a front controller, forwards request to spring mvc controllers
* inherits from HttpServlet
* handler method to handle incoming HTTP requests
* controller class - contains handler methods



Spring annotations



### JPA

* mapping java objects to rdbms
* vice-versa = ORM (object relational mapping)

==========================================

HATEOAS

created a new schema on MySQL workbench







