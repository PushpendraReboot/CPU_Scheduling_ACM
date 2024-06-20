# CPU_Scheduling_ACM
 CPU Scheduling application named Devastation
 
**CPU Scheduling Web Application**

Welcome to the CPU Scheduling Web Application! This project aims to provide a visual representation and simulation of various CPU scheduling algorithms. Users can interactively input processes with their arrival and burst times and select a scheduling algorithm to see how it operates.

This web application allows users to simulate different CPU scheduling algorithms. It visually represents the order of execution and calculates various metrics such as turnaround time, waiting time, and completion time for each process.

**Features:**

Interactive user interface for inputting process details.

_Supports multiple CPU scheduling algorithms:_

First-Come, First-Served (FCFS)
Shortest Job First (SJF)
Round Robin (RR)
Priority Scheduling
Longest Remaining Time First (LRTF)
Shortest Remaining Time First (SRTF)

Visual representation of the scheduling process.

Calculation of average turnaround time, waiting time, and completion time.

**Technologies Used:**

HTML5
CSS3
JavaScript
Bootstrap
Chart.js for graphical representation
jQuery

**Usage**

Select CPU Algorithm: Choose a CPU scheduling algorithm from the list of radio buttons.
Enter Process Details: Input the arrival time and burst time for each process. Optionally, enter priority if the Priority Scheduling algorithm is selected.
Add/Remove Processes: Use the "Add a Row +" button to add new processes and the "Delete a Row -" button to remove selected processes.
Execute: Click the "Execute" button to run the selected scheduling algorithm.
View Results: The table will display the process execution order and relevant metrics. The Gantt chart below the table will visually represent the scheduling process.

**Scheduling Algorithms**

First-Come, First-Served (FCFS)
Executes processes in the order they arrive.

Shortest Job First (SJF)
Selects the process with the shortest burst time next.

Round Robin (RR)
Executes processes in a cyclic order, allocating a fixed time slice (quantum) to each process.

Priority Scheduling
Executes processes based on priority. Lower priority number means higher priority.

Longest Remaining Time First (LRTF)
Selects the process with the longest remaining burst time.

Shortest Remaining Time First (SRTF)
Selects the process with the shortest remaining burst time.

License
This project is licensed under the MIT License. See the LICENSE file for details.
