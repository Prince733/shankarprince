Researchers designed one system that classified interactive and noninteractive processes automatically by looking at the amount of terminal
I/O. If a process did not input or output to the terminal in a 1-second interval, the process was classified as noninteractive and was
moved to a lower-priority queue. In response to this policy, one programmer modified his programs to write an arbitrary character to the
terminal at regular intervals of less than 1 second.The system gave his programs a high priority, even though the terminal output was 
completely meaningless.

solution:- 
    First of all we have to enter the no of process for finding their priorities and initialize it as n. After that take for loop for taking 
 the for loop for taking input for 'n' processes. Next,take response time as input in milliseconds. Using if else condition find highest
 priority by the condition i.e.., if the response time is greater than 1000 then make it as lower priority i.e.., NON interactive and if it 
 is less than 1000 make it as higher priority i.e.., Interactive.
