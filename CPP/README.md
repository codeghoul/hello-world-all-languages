Step 1. Type command to install gcc or g++ complier:
    `$ sudo apt-get install build-essential`
This will install the necessary C/C++ development libraries for your Ubuntu to create C/C++ programs.

To check gcc version type this command:
    `$ gcc –version or gcc –v`

Step 2. Now go to that folder where you will create C/C++ programs.
ex: `$ cd Documents/`
    `$ sudo mkdir programs`
    `$ cd Documents/`
    
Step 3. Open a file using any editor.
    `$ sudo gedit first.c (for C programs)`   
    `$ sudo gedit hello.cpp (for C++ prgrams)`


Step 4. Compile the program using the following command:

    `$ sudo g++ HelloWorld.cpp (or)`

    `$ sudo g++ -o Helloworld helloWorld.cpp`

Step 5. To run this program type this command:

    `$ ./a.out (If you compiled using first command)`

Or

    `$ ./hello` 