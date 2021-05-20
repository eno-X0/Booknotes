### Some comments about CPP diffrent from C

#### about input (from keyboard) & output (to screen)
- while C use `#include <stdio.h>` & use func `scanf()` and `printf()` etc. but --
- CPP should :
	 ```C++
	 #include <iostream>
	 using namespace std
	 ```
	+ and then : use `cin>>a` to input from keyboard and `cout<<'a'` to output to screen
	+ 
#### about assign a value to a variable while the variable is declared
- CPP can use `int x = 20;` or `int x(20)`;
- that is, the type in CPP is close to constructor.

#### about reference variable & pointer
- reference variable is like a alias to a exist variable and is used like this : `int x, &xa=x;`
- the pointer type is the same as C

#### dynamic memory allocation about C & CPP
- C
	+ `int *p = (int *)malloc(n * sizeof(int));`
	+ `free(p);`
- CPP
	+ `int *p = new int; int *pa = new int[5]; `
	+ `delete p; delete []pa;`

#### about '&' in CPP
- a operator with multi-meaning
- bitwise AND
- a type of reference variable
- address-of operator in pointer
