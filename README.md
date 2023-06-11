# DS_Project

# OVERVIEW
Process Scheduling program is a simulation for how the operating systems of linux work.
it contains foure type of processors (First Come First Serve (FCFS), Round Robin (RR), Shortest Job First (SJF) and Earliest Deadline First (EDF)). the program contain several actions like (Process migration, Forking, workstealing, Processor overheating,orphan killing, killing .....etc)
The program has three modes step-by-step, silent and interactive mode, and works under some assumputions like that each actions happens according to a certain input file that we put manually.
The process enter the program accourding to it's arrival time then enter the readyList for the processor that has the shortest readyList (the shortest readyList means the List that has the shortest finishing time) then the processor transfer the process to the RUN state according to it's scheduling algo then it remains there until it's cpu time equal zero or there is some sctions that may happen like forking a process or the process needs an input from the user so it will be moved to the block list untill the it recieve the input it needs. There are some extra actions may happen to the process that it recieve a signall kill at a certain time step from the input file throughout the program a workstealing or/and process migration that may happen among the processors according to a percentage that uploaded from the input file. when all the processes are done processing the program create an output file that shows you the average waiting time , the percentage of migration, workstealing , forked process and killed process, processor utilization and average utilization....etc.

# LANGUAGE
C++
# Purpose
This application was submitted as a semester project for a Data structres course.
# CREATORS
 Amira El-Garf
 
 Danah Hassan
 
 Bassem sherief
 
 Mohamed nabil


#  Input file explanation
![Screenshot (123)](https://github.com/amiraelgarf/DS_Project/assets/127895527/61886d19-d2cc-4b79-a790-d38c78fdcc9f)


# Input file

![Screenshot (111)](https://github.com/amiraelgarf/DS_Project/assets/127895527/2618cb66-57c5-4229-a52c-0a2b50417722)

# program interface for interactive mode

![Screenshot (112)](https://github.com/amiraelgarf/DS_Project/assets/127895527/976dd8e7-48d7-4963-83ce-6cd6c8fdc2ba)

# killing process & forking happened for process with id 1

![Screenshot (113)](https://github.com/amiraelgarf/DS_Project/assets/127895527/dd180ab4-7f09-467d-a11c-8ae568b32122)

# some shots from the program

![Screenshot (119)](https://github.com/amiraelgarf/DS_Project/assets/127895527/a6d15ae0-ea62-417f-9b72-10b11c5d4be5)

![Screenshot (120)](https://github.com/amiraelgarf/DS_Project/assets/127895527/e3906931-47b7-4799-a550-e55261f2a235)

# The program ended successfully after all the processes including the forked ones finished their CPU and moved to the termination list and the out file is created.
![Screenshot (121)](https://github.com/amiraelgarf/DS_Project/assets/127895527/a632496d-49e2-4dbc-9ace-772b051c7020)

# Output file sample
![Screenshot (132)](https://github.com/amiraelgarf/DS_Project/assets/127895527/19fed668-0133-4ab6-911e-727ba9b1ec6b)
![Screenshot (133)](https://github.com/amiraelgarf/DS_Project/assets/127895527/c1760e9b-58cc-452c-9dc8-0912069a10fb)
