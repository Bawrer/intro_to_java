# intro_to_java
## week 1 day 1
Java is a high-level, object-oriented programming language that is designed to be platform-independent, meaning that Java programs can run on any device that has a Java Virtual Machine (JVM) installed.

## Advantages of Java:
1. Object-Oriented Programming (OOP): Java is a pure object-oriented programming language, which promotes code organization, reusability, and maintainability.

2. Strong Community Support: Java has a large and active community, which means there are extensive resources, libraries, and frameworks available. Developers can easily find support and solutions to their problems.

3. Scalability: Java is known for its scalability, making it suitable for building large-scale enterprise applications.

## disadvantages:

1. Performance: While the performance of Java has improved over the years, some low-level languages, like C or C++, may still offer better performance for certain types of applications.

2. Startup Time: Java applications may have a longer startup time compared to languages that are compiled to native code.

3. Learning Curve: Java's extensive ecosystem and libraries can make it challenging for beginners to learn the language quickly.

# java components

## java code(.java file)
 – this is the java code you have written, and its saved in the .java file(s)

## javac compiler:
 compile the source code files(.java) into a bytecode so that the jmv will be execute it.Bytecode is saved in a class file by compiler.

 ## Bytecode

 the resulting code after the source code has been executed by the compiler.

 ## Java Virtual Machine (JVM)

the primary function used to execute the bytecode produced by the compiler.

every os has its jvm, the output after execution of bytecode is the same accross all OS, that is why java is platform independent.

## steps to follow when executing a code
1. write a java program in an IDE with exwntion .java

2. the javac compiler is the primary compiler included in the JDK. It takes program as an input and convert it into java bytecode as an output

3. Java Virtual machine- it executes the bytecode generated by the compiler and this phase is called RUN PHASE.

## jdk 
complete Java development kit that includes JRE, compiler, and some more tools like javaDoc, java Debugger and more.
for you as a programmer you need to have JDK in order to be able to create java programs.

## JRE
 is the runtime environment required for running Java applications. It includes the JVM and other libraries that are needed for running Java programs but not for compiling them.

 # java Main features

 ## Platform Independence (Write Once, Run Anywhere):
 Java programs are compiled into bytecode, which is an intermediate form that can be executed on any device with a Java Virtual Machine (JVM).

## Object-Oriented: 
Java is designed around the principles of object-oriented programming (OOP). It supports concepts such as classes, objects, inheritance, polymorphism, and encapsulation, making it easy to organize and structure code.

## simple
 Java has a straightforward syntax, and its popularity has led to a large and active developer community. There are plenty of resources, tutorials, and forums available for learning and getting support.

## Robust language

when Java is described as a "robust" programming language, it refers to its ability to provide strong safeguards against errors and its capability to handle unexpected conditions gracefully.

## Security:
 Java has built-in security features, including a robust security model and a bytecode verifier, which helps ensure that code running on the JVM is safe and doesn't violate security constraints

## Multithreading:
 Java supports multithreading, allowing developers to write programs that can perform multiple tasks concurrently

 ## setting up the environment
etting up a Java development environment involves installing the Java Development Kit (JDK) and an Integrated Development Environment (IDE). Here are the steps to set up a basic Java environment:

1. Install the Java Development Kit (JDK):
## For Windows:
## Download JDK:
Visit the Oracle JDK download page or use an alternative like OpenJDK.

## Install JDK:
Follow the installation instructions provided on the download page.

## Set the PATH variable:
Add the JDK bin directory to your system's PATH variable. This allows you to run Java commands from any command prompt.

## java first program
public class firstProgram {
   public static void main(String[]args){
      System.out.println("hello world");
   }

} 

