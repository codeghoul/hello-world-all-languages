Hello World in Java

Prerequisites
-------------
Step 1: Setup Java development environment on your Computer

Procedure
-----------

Step 2: Create the program by typing it into a text editor and saving it to a file – HelloWorld.java.

Step 3: Compile it by typing “javac HelloWorld.java” in the terminal window.

Step 4: Execute (or run) it by typing “java HelloWorld” in the terminal window.

Hello World Guide
-----------------

1: Class definition:This line uses the keyword class to declare that a new class is being defined.
    `class HelloWorld` 
HelloWorld is an identifier that is the name of the class. The entire class definition, including all of its members, will be between the opening curly brace  {  and the closing curly brace  } .

1: main method: In Java programming language, every application must contain a main method whose signature is:
    `public static void main(String[] args)`

public: So that JVM can execute the method from anywhere.
static: Main method is to be called without object. 
The modifiers public and static can be written in either order.
void: The main method doesn't return anything.
main(): Name configured in the JVM.
String[]: The main method accepts a single argument: 
          an array of elements of type String.
Like in C/C++, main method is the entry point for your application and will subsequently invoke all the other methods required by your program.

3: The next line of code is shown here. Notice that it occurs inside main( ).
    `System.out.println("Hello, World");`
This line outputs the string “Hello, World” followed by a new line on the screen.
Output is actually accomplished by the built-in println( ) method. 
System is a predefined class that provides access to the system, and out is the variable of type output stream that is connected to the console.