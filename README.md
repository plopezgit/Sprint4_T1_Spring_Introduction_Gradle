# Sprint4_T1_Spring_Introduction_Gradle


Description:

This exercise introduces the SPRING framework.
You'll start using the HTTP protocol, using Postman, and discovering how to manage dependencies with Gradle.

Level 1:

- Spring and Gradle exercise:

This exercise is a first contact with Spring and Gradle.
Access the page: https://start.spring.io/, and generate a Spring boot project with the following characteristics:

- [x] Import it into Eclipse using the option File > Import > Existing Gradle Project.
- [x] In the application.properties file, set the server.port variable to the value 9001.

We will turn this application into a REST API:

- [x] Depending on the main package, create another subpackage called Controllers, and inside it, add the HelloWorldController class. It must have two methods:
- [x] String hi
- [x] String hi2

- [x] These two methods will receive a String parameter called name, and will return the phrase:
- “Hello, “ + name + “. You are running a Gradle project”.

- [x] The first method will respond to a GET request, and must be configured to receive the parameter as a RequestParam. The "name" parameter will have the default value "UNKNOWN". You will have to answer to:

- http://localhost:9001/HelloWorld
- http://localhost:9001/HelloWorld?name=My name

- [x] The second method will respond to a GET request, and must be configured to receive the parameter as a PathVariable. The "name" parameter will be optional. You will have to answer to:

- http://localhost:9000/HelloWorld2
- http://localhost:9000/HelloWorld2/myname


**Very important:**

In addition to the Git link for the solved assignment, you will need to include at least two different links to the resources we have provided you with on campus that have helped or could have helped you solve the entire assignment or some parts.