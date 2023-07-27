# Section 1: Spring Boot Overview
## What is JVM? JRE? and JDK?
1. [JVM - Java Virtual Machine](https://github.com/trucdg/java-virtual-machine):
   - Provides Runtime Environment in which Java bytecode can be executed.
   - Tasks of JVM:
     - Loads code
     - Verifies code
     - Executes code
     - Provides Runtime Environment
>Note: 
> - **Java is platform independent** while **JVM, JRE, and JDK are platform dependent.**
> - java is platform independent because java doesn't run directly on the operating system. It runs on the JVM which you have to install separately. The use of the same byte code for all JVMs on all platforms make the java language platform independent.
 
- The **Java Development Kit (JDK)** is a cross-platformed software development environment that offers a collection of tools and libraries necessary for developing Java-based software applications and applets.
- It is a core package used in Java, along with the **JVM (Java Virtual Machine)** and the **JRE (Java Runtime Environment)**.
- Beginners  often get confused with JRE and JDK, if you are only interested in running Java programs on your machine then you can easily do it using Java Runtime Environment. However, if you would like to develop a Java-based software application then along with JRE you need some additional tools, which is called JDK.
- JDK = JRE + Development Tools
- Development Tools examples: the Java debugger, Java compipler, etc.
![image](https://github.com/trucdg/section1-SpringBoot3-intro/assets/91285203/62c4ff94-ee89-40e9-b2f7-183c424f3f23)