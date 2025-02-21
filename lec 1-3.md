## Easy Questions:

        1. Simple Addition of Two Integers:
        Write a program that declares two integer variables, assigns them values (e.g., 8 and 15), and then prints their sum.

```C++
//Solution:
#include <iostream>

main()
{
	  int x;
	  int y;
	  
	  x = 8;
	  y = 15;
	  
	  int sum = x + y;
	  
	  std::cout << "sum = ";
	  std::cout << sum;
}
```

        2. Display a String:
        Write a program that prints the following message on the screen: "Welcome to C Programming!" using cout.

```C++
//Solution
#include <iostream>

main()
{
	  std::cout << "Welcome to C Programming";
}
```

## Normal Questions:

        1. Calculate the Product of Two Numbers:
        Write a program that declares two int variables, assigns them values (e.g., 4 and 5), and then prints the result of multiplying them.

```c++
//Solution
#include <iostream>

main()
{
	  int x;
	  int y;
	  
	  x = 4;
	  y = 5;
	  
	  int result = x * y;
	  
	  std::cout << "result = " << result;
}
```

        2. Variable Initialization and Output:
        Write a program that declares three variables: one int, one float, and one char. Assign values to them (e.g., int=5, float=3.14, char='A'). Output the values of these variables using cout.

```c++
//Solution
#include <iostream>

main()
{
 	  int x;
	  float y;
	  char z;
	  
	  x = 999999999; //can't add one more place to it.
	  y = 3.141414141414; //float stores upto 5 decimal places
	  z = 'A'; //char stores single charater --Woverflow
	  
	  std::cout << "x = " << x << std::endl;
	  std::cout << "y = " << y << std::endl;
	  std::cout << "z = " << z << std::endl;
}
```
## Hard Questions:

        1. Calculate the Difference Between Two Numbers:
        Write a program that declares two int variables and calculates the difference between them. Output the result. Try this by subtracting a larger number from a smaller number (e.g., 10 - 20), and print the result.

```c++
//Solution
#include <iostream>

main()
{
 	  int x = 10;
 	  int y = 20;
 	  
 	  int result = x - y;
 	  
 	  std::cout << "result = " << result;
}
```

        2. Basic Swap Program Using a Temporary Variable:
        Write a program that swaps the values of two integer variables (x and y) using a temporary variable. Assign values to x and y (e.g., x=7 and y=12) and display the values before and after the swap.

```c++
//Solution
#include <iostream>

main()
{
	  int x = 7;
	  int y = 12;
	  
	  std::cout << "x = " << x << std::endl;
	  std::cout << "y = " << y << std::endl;
	  
	  int temp;
	  
	  //Swapping values
	  temp = x;
	  x = y;
	  y = temp;
	  
	  std::cout << "After swaping\n";
	  std::cout << "x = " << x << std::endl;
	  std::cout << "y = " << y << std::endl;
}

```