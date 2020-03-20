There are 3 student processes and 1 teacher process. Students are supposed to do their assignments and they need 3 things for that pen, 
paper and question paper. The teacher has an infinite supply of all the three things. One students has pen,an other has paper and another 
has question paper. The teacher places two things on a shared table and the student having the third complementary thing makes the 
assignment and tells the teacher on completion. The teacher then places another two things out of the three and again the student having 
the third thing makes the assignment and tells the teacher on completion. This cycle continues. WAP to synchronize the teacher and the 
students.

Explanation: 
                      In the given solution I have taken all the student processes and resources in 2D array and initialized then to 0.
 I have made 3 student processes in three different functions which will be executed by single s_thread and one t_thread for execution 
of teacher process. User will get a menu to select any two out of three resources that are to be placed on shared table.  If one
process is completed there will be a message printed on the screen saying process is completed.  When one process is executing no other 
student or teacher process will execute and for achieving this I have used Mutex lock.  When a process starts to execute it acquires 
the lock and when it completes the execution releases the lock.  After completion of all the three processes the program will end.
