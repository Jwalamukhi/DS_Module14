# Ex8 Deque
## DATE:
## AIM:
To write a C function to count the number of elements present in the deque.

## Algorithm
1. 
2. 
3. 
4.  
5.   

## Program:
```
/*
Program to count the number of elements present in the deque
Developed by: Jwalamukhi S
RegisterNumber: 212223040079 
*/

/*#include <stdio.h>

#define MAX 10

void addFront(int *, int, int *, int *);
void addRear(int *, int, int *, int *);
int delFront(int *, int *, int *);
int delRear(int *, int *, int *);
void display(int *);
int count(int *);
*/
int count(int *arr) {
  int c = 0, i;
  for(i=0;i<MAX;i++)
  {
      if(arr[i]!=0)
      c++;
  }
  return c;

  
}
```

## Output:

![Screenshot 2025-05-20 212930](https://github.com/user-attachments/assets/ce2436fd-928e-4e66-a7ac-001698e10abe)

![Screenshot 2025-05-20 212937](https://github.com/user-attachments/assets/2b6e284e-9623-4d49-a68f-70d85d3d7918)

## Result:
Thus, the C code to count the number of elements present in the deque is implemented successfully.
