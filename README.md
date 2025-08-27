Aim: To study and implement C++ arithmetic pointers

#Program a: This C++ program demonstrates pointer usage in a simple way.A regular variable a is declared and assigned a value of 10. A pointer aptr is declared to store the address of a.Using *aptr gives the value stored at the address pointed to by aptr.The program also shows the memory address of a.

Algorithm:

- Step-1: Start
- Step-2: Declare an integer variable a and assign it the value 10
- Step-3: Declare a pointer aptr of type int*
- Step-4: Assign the address of a to aptr using aptr = &a
- Step-5: Print the value of a
- Step-6: Print the value pointed to by aptr using *aptr
- Step-7: Print the address stored in aptr
- Step-8: Print the address of a using &a
- Step-9: End

#Program b: This C++ program demonstrates how arrays and pointers are related and how you can use pointer arithmetic to access array elements.Array Declaration: arr[] = {10, 20, 30} creates an array with 3 elements by initialising the pointer. *arr gives the first element of the array (10). Inside the loop, *ptr gives the current element, and ptr++ moves to the next. 

Algorithm:

- Step-1: Start
- Step-2: Declare an integer array arr with values {10, 20, 30}
- Step-3: Print the first element of the array using *arr
- Step-4: Declare an integer pointer ptr and assign it to the base address of arr (i.e., ptr = arr)
- Step-5: Start a loop from i = 0 to i < 3
- Step-6: Print the value pointed to by ptr using *ptr
- Step-7: Increment the pointer ptr using ptr++ to move to the next array element
- Step-8: End the loop
- Step-9: End

#Program c: This program demonstrates two important concepts in C++ by Pointer dereferencing and modification and Array-pointer relationship.

Algorithm:

- Step-1: Start
- Step-2: Declare an integer variable a and assign it the value 10
- Step-3: Declare a pointer aptr and assign it the address of a
- Step-4: Print the value pointed to by aptr (which is value of a)
- Step-5: Modify the value at the address pointed by aptr to 20
- Step-6: Print the value of a (now changed to 20)
- Step-7: Declare an integer array arr with elements {10, 20, 30}
- Step-8: Print the first element of the array using *arr
- Step-9: End

#Program d: This C++ program demonstrates the relationship between arrays and pointers through a simple example. An integer array arr is declared and initialized with the values {10, 20, 30}. In C++, the name of an array (arr in this case) acts as a pointer to its first element. Therefore, when we use the expression *arr, it dereferences the pointer and accesses the value at the first memory location of the array, which is 10. The program then prints this value using cout. As a result, the output of the program is 10. This demonstrates how the array name can be used like a pointer to access and manipulate array elements.

Algorithm:

- Step-1: Start
- Step-2: Declare an integer array arr with values {10, 20, 30}
- Step-3: Access the first element of the array using *arr
- Step-4: Print the first element (10)
- Step-5: End
