# Java SpringBoot
# Content
- Introduction
- Excercise
- Install dependencies
- Run code
- Information

# Introduction

**What is Spring boot?**
> Spring Boot is a tool that was created in order to further simplify the development of applications based on the already popular Spring Core framework. Spring Boot seeks that the developer only focus on the development of the solution, completely forgetting about the complex configuration that Spring Core currently has in order to function.


**What is a dependency?**
> Small characteristic of a specific object, which can have a particular impact on the operation of a unit. <p/>
For example, the dependencies of a Smartphone would be:
> - Camera
> - Microphone
> - Screen
> - Drums

**What is a bean?**
> A bean is basically modules developed in Spring, these are responsible for providing us with all the logic we need for our application. Example: If we need to reference that our class is a model we make use of the @entity bean. This allows us to use properties created for this type of module that speed up our development.

**Dependency Injection**
> The Principle of Dependency Injection is nothing more than being able to pass (inject) the dependencies when needed instead of initializing the dependencies within the receiving class.

**Annotation**
> An Annotation is a way of adding metadata to Java source code that is available to the application at run or compile time. It is a simpler alternative to using XML.<p/>
> TYPES OF ANNOTATIONS:
> - **@Controller:** To indicate that this will be the class that will manage user requests for get, post, put, patch or delete.
> - **@Service:** With this notation we specify that all our business logic, calculations or calls to other external APIs will be found in this class.
> - **@Repository:** It is used for the classes or interfaces that will work with the access to the database, it takes care of the persistence.

# Excercise

The project that was developed is a REST API that controls the operations of users. This API gets information from a H2 database. What this API does is:

- Delete a user
- Post a new user
- Gets the users
- Updates a user
- Pagination of users

# Install dependencies

- [Install OpenJDK 11 or later](https://www.oracle.com/mx/java/technologies/javase-jdk11-downloads.html)
- [Install Intellj](https://www.jetbrains.com/es-es/idea/download/#section=windows) or another IDE thats supports OpenJDK 11 or later and contains maven

For this project you can check [maven repository](https://mvnrepository.com/)

- Add spring-boot-devtools
- Add spring-boot-starter-web
- Add spring-boot-starter-data-jpa
- Add spring-boot-starter-test

# Run code

You can run the program in the Intellij IDE usin maven.

   <div><img src ="https://vaadin.com/docs/latest/static/44aa85798d7510627ce48c5b38738da1/03979/welcome-screen.png" width ="800px">  </div>    


# Information

for more info you can check the [java Spring boot course](https://platzi.com/clases/spring-boot/)
