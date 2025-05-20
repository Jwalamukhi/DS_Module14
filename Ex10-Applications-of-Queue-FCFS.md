# Ex10 Applications of Queue – FCFS
## DATE:
## AIM:
To write a C function to calculate the turnaround time of each process given their burst time and waiting time in First Come first Serve scheduling algorithm.
## Algorithm
1. 
2. 
3. 
4.  
5.   

## Program:
```
/*
Program to find and display the priority of the operator in the given Postfix expression
Developed by: Jwalamukhi S
RegisterNumber: 212223040079 
*/

int turnaroundtime( int proc[], int n,int burst_time[], int wait_time[], int tat[]) {
   int i;
   for ( i = 0; i < n ; i++)
   tat[i] = burst_time[i] + wait_time[i];
   return 0;
}
```

## Output:

![Screenshot 2025-05-20 211731](https://github.com/user-attachments/assets/9d7fc7ba-5744-454c-a21f-fe6f466442aa)



## Result:
Thus, the C function to calculate the turnaround time of each process given their burst time and waiting time in First Come first Serve scheduling algorithm is implemented successfully.
