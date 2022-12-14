# Introduction to Java Programming 

> Java was developed by **James Gosling** in **Sun MicroSystems** in **1995**. 

It is a high-level programming language. It makes writing, compiling and debugging programming easier.

Allows developers to write once run anywhere. Programs written in java can be reused and can run on all platforms that support java.

> **Advantages of Java**
- **Object-Oriented**
- **Platform-Independent**
- **Secure and Robust**
- **Multi-Threaded**
- **Portable**
- **Interpreted**

> **Applications of Java**
- **Desktop GUI**
- **Embedded Systems**
- **Web Applications**
- **Application Servers**
- **Web Servers**
- **Enterprise Applications**
- **Big Data Technologies**

> **Basic Java Terminologies**
1. **Java Virtual Machine**:- Generally referred as JVM. It is a platform required to execute a java program.
    - Program is written in any of the code editor.
    - The compilation is done by JAVAC compiler. It takes program as input and converts to bytecode.
    - JVM executes the bytecode generated by the compiler.

    Every system has a different JVM but the output they produce after the execution of bytecode is the same across all the operating systems. This is why Java is known as **Platform Independent Language**.

2. **ByteCode**:- Javac compiler of JDK compiles the java source code into bytecode so that it can be executed by the JVM. It is saved as **.class** file by the compiler.

3. **Java Development Kit (JDK)**:- It is a complete java development kit that includes everything including compiler, JRE, java debuggers and java docs...etc.

4. **Java Runtime Environment (JRE)**:- JRE allows to run java programs (not compile). JRE includes a browser, JVM, applet supports and plugins.

5. **Garbage Collector**:- In Java, programmers cannot delete objects. To delete or recollect that memory JVM has a program called **Garbage Collector**. They can recollect the objects that are not referenced. So handling memory management is very easy.

6. **Classpath**:- The classpath is the file path where in the java compiler and JVM looks for **.class** files to load and execute the java program.

> **Features of Java Programming**
1. **Platform Independent**:- Compiler converts the source code into bytecode and later the JVM executes the bytecode generated by the compiler. This byte can run on any platform i.e Windows, Linux or MacOS which means if we compile the program in Windows, then it can be run on Linux and vice-versa. 

2. **Object-Oriented Programming Language**:- Java Language is considered an object-oriented language because it is based on the concept of objects and classes. Without the creation of objects and classes, it is impossible to write any code in Java. 
> OOPS concepts:-
   - **Inheritance**
   - **Data abstraction**
   - **Polymorphism**
   - **Data Encapsulation**

3. **Simple**:- Java is one of the simple languages as it does not have pointers, operator overloading, multiple inheritances and explicit memory allocations.

4. **Robust**:- Java language is robust which means reliable. The main features of java that make it robust are garbage collection, exception handling and memory allocation.

5. **Secure**:- Several security flaws are impossible to exploit like stack corruption or buffer overflow and acccessing out of bounds arrays. Also java programs run in an environment that is independent of the operating system(OS) environment which makes java programs run secure.

6. **Distributed**:- Remote Method Invocation and Enterprise Java Beans are used for creating distributed applications in java. The java programs can be easily distributed on one or more systems that are connected to each other through an internet connection.

7. **Multithreading**:-  Java supports multithreading. It is a Java feature that allows concurrent execution of two or more parts of a program for maximum utilization of the CPU.

8. **Portable**:- The platform-independent feature of java in which its platform-independent bytecode can be taken to any platform for execution makes java portable.

9. **High Performance**:- Java architecture is defined in such a way that it reduces overhead during the runtime and at some time java uses Just In Time (JIT) compiler where the compiler compiles code on-demand basics where it only compiles those methods that are called making applications to execute faster.

10. **Dynamic Flexibility**:- Java being completely object-oriented gives us the flexibility to add classes,  new methods to existing classes and even create new classes through sub-classes. Java even supports functions written in other languages such as C, C++ which are referred to as native methods.

#### Basics of a Java Program [Click Here to view the Program](https://github.com/manjunathnmessi/Mission-Google/blob/master/Day1/Day1/Learn.java)

1. **Comments**:- Comments are used for explaining code and are used in a similar manner in Java or C or C++. Compilers ignore the comment entries and do not execute them. Comments can be of a single line or multiple lines.

Single Line Comments:

Syntax:-
````
// Single-line Comment
````

Multi Line Comments:

Syntax:-
````
/* Multi Line Comment */
````

2. **import java.io**:- This means all the classes of io package can be imported. Java io package provides a set of input and output streams for reading and writing data to files or other input or output sources.

3. **class**:- The class contains data and methods to be used in the program. Methods or Functions define the behaviour of the program.

4. **static void main()**:- static keyword tells us that this method can be accessed without instantiating the objects.

5. **void**:- This keyword will tell that this method will not return anything.

6. **System.in**:- This is the standard input stream that can be used to read the input from keyboard or any other standard input device.

7. **System.out**:- This is the standard output stream that is used to produce the result of a program or an output device like the computer screen.

8. **println()**:- It is a method used to display the text on the console. It prints the text on the console and moves to the next line of the console. The next printing takes place from the next line

9. **String [] args**:- This is the argument passed to the main function which is an array of strings with the array name args. 


### So , This brings an end to DAY1 -> let's catch on [DAY2](https://github.com/manjunathnmessi/Mission-Google/tree/master/Day2)
