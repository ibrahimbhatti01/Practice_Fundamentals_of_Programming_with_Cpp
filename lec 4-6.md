# Questions/Solutions

### Lecture 04:

    1. Given a four-digit integer, separate and print digits on the screen.

```c++
//Solution
#include <iostream>

main()
{
	  int x = 1234;
	  
	  int result;
	  result = x % 10;
	  
	  std::cout << "result = " << result << std::endl;
	  
	  
	  x = x / 10;
	  
	  result = x % 10;

	  std::cout << "result = " << result << std::endl;


	  x = x / 10;

	  result = x % 10;

	  std::cout << "result = " << result << std::endl;
	  
	  
	  x = x / 10;

	  result = x % 10;

	  std::cout << "result = " << result << std::endl;

	  return 0;
}

```

```C++
// Refined Program
#include <iostream>

main()
{
	  int number;
	  
	  std::cout << "Please enter a 4-digit number: ";
	  std::cin >> number;
	  
	  int digit;
	  digit = number % 10;
	  
	  std::cout << "digit = " << digit << std::endl;
	  
	  
	  number = number / 10;
	  
	  digit = number % 10;

	  std::cout << "digit = " << digit << std::endl;


	  number = number / 10;

	  digit = number % 10;

	  std::cout << "digit = " << digit << std::endl;
	  
	  
	  number = number / 10;

	  digit = number % 10;

	  std::cout << "digit = " << digit << std::endl;

	  return 0;
}
```

```C++
// Printing 4-digits in reverse order
#include <iostream>

main()
{
	  int number;
	  
	  std::cout << "Please enter a 4-digit number: ";
	  std::cin >> number;
	  
	  int digit;
	  
// Integer division will truncate fractional part.
	  digit = number / 1000;
	  
	  std::cout << "digit = " << digit << "\n";

// modulous with 1000 will give the first place chracter.
	  number = number % 1000;
	  
	  digit = number / 100;
	  std::cout << "digit = " << digit << "\n";


	  number = number % 100;
	  
	  digit = number / 10;
	  std::cout << "digit = " << digit << "\n";

	  
	  number = number % 10;

	  digit = number / 1;
	  std::cout << "digit = " << digit << "\n";

	  return 0;
}
```

---
---


### Lecture 05:

        1. Print sizes of variables data types.

```C++
// Solution
#include <iostream>

main()
{
	  std::cout << "C++: Variable's data types size calculator in bytes\n";
	  std::cout << "\n ----------------------------------------------\n\n";
	  
	  std::cout << "The size of 'char' is : " << sizeof(char) << " byte\n";
	  std::cout << "The size of 'short' is : " << sizeof(short) << " byte\n";
	  std::cout << "The size of 'int' is : " << sizeof(int) << " byte\n";
	  std::cout << "The size of 'long' is : " << sizeof(long) << " byte\n";
	  std::cout << "The size of 'long long' is : " << sizeof(long long) << " byte\n";
	  std::cout << "The size of 'float' is : " << sizeof(float) << " byte\n";
	  std::cout << "The size of 'double' is : " << sizeof(double) << " byte\n";
	  std::cout << "The size of 'long double' is : " << sizeof(long double) << " byte\n";
	  std::cout << "The size of 'bool' is : " << sizeof(bool) << " byte\n";

	  return 0;
}
```

```C++
