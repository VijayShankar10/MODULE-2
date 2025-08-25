# Ex.No4
## Ex.Name: Write a C++ program to add two numbers and three numbers using constructor overloading.
## Date:

## Aim:
To demonstrate constructor overloading by performing addition of two and three numbers.

## Algorithm:
1. Start the program.  
2. Create a class `Addition` with constructors overloaded.  
3. Constructor with 2 parameters adds two numbers and displays sum.  
4. Constructor with 3 parameters adds three numbers and displays sum.  
5. In `main()`, create objects with two and three values.  
6. End the program.  

## Program:
```cpp
#include <iostream>
using namespace std;

class Addition {
public:
    Addition(int a, int b) {
        cout << "The Sum is " << a+b << endl;
    }
    Addition(int a, int b, int c) {
        cout << "The Sum is " << a+b+c << endl;
    }
};

int main() {
    Addition obj1(5,6);
    Addition obj2(2,8,5);
    return 0;
}
```



## Output:
```
The Sum is 11
The Sum is 15
```
##Result:
<img width="856" height="251" alt="image" src="https://github.com/user-attachments/assets/a2c90b2a-281c-4abe-8bba-6cbcbca7506e" />

