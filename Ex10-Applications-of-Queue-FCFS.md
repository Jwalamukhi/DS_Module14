# Ex10 Applications of Queue – FCFS
## DATE:
## AIM:
To write a C function to calculate the turnaround time of each process given their burst time and waiting time in First Come first Serve scheduling algorithm.
## Algorithm

1.Start with process, burst time, and waiting time arrays.

2.Loop through each process from i = 0 to n-1.

3.Compute tat[i] = burst_time[i] + wait_time[i].

4.End the algorithm.

## Program:
```
/*
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
