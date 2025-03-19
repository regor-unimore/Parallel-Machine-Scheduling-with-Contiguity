# Parallel-Machine-Scheduling-with-Contiguity

Names of random instances in folder "TEST0-RANDOM" are "TEST0-X-Y-Z-A" where "X" indicates the number of jobs, "Y" indicates the number of machines, "Z" indicates the number of workers, and the letter "A" indicates the index of the instance in the XYZ group. 

The names of realistic instances in folder TEST1-REALISTIC are "TEST1-X-Y" where "X" indicates the number of jobs and "Y" indicates the index of the instance in the X group. 

Random and realistic instances (TEST0-RANDOM and TEST1-REALISTIC) are built in the same way: 

int number of jobs

int number of machines

int number of workers

int number of time slots

matrix[][] 0/1 compatibiliy jobXmachine

matrix[][] 0/1 compatibiliy jobXworker

matrix[][] 0/1 compatibiliy machineXworker

array[int] jobs’ release date (index of the time slot)

array[int] jobs’ due date (index of the time slot)

array[int] jobs’ workers load (unitary amount of workers’ load per time slot for each job)

array[int] jobs’ weight

array[int] jobs’ processing time (in number of time slots)

matrix[][] int working hours availability workerXtimeslot (in units of worker load)

int number of precedences i

matrix[][2] precedences with job indices: matrix[i][0] i-th  predecessor  - matrix[i][1] i-th  successor (indices of the jobs)

int number of contiguities j

matrix[][2] contiguities with job indices: matrix[i][0] j-th  predecessor - matrix[i][1] j-th  successor  (indices of the jobs)




