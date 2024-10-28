# Assignment 3

## Group Members:
- **Partik Dev** 
- **Gurmandeep Johal**

## Student ID:
- **devp2:** 400478418
- **johalg11:** 400467941

## Program Explination:
The program is designed to have 5 students go to the TAs office as these are the students that are assigned to the TA. The number of students can change by altering the defined constant `NUMSTUDENTS`. We have set our `n` number of students to 5. However, this could be changed by modifying the program to accept an integer argument indicating the desired number of student threads. The input would be read in the main function with the `argc` and `argv`. Each student thread would be accounted through thread ID. The number of threads would be created by setting `pthread_t` for students to be a pointer to dynamically allocated data. Moreover, our program ensures that students in the hallway are process in turn and the one that request to vists the TA through the semaphore will be the student/thread to signal the awakening of the TA thread. Additionally, Students will go back to programming if they see that the hallway seats are filled or once they are done visiting the TA's office. Finally the TA will work with students for a random amount of as set by our random timer, but will go to sleep if there are no students to help. 

## Contributions:

Both group members collaborated equally on the project during lab sessions and via discord communication. However, each member did particular tasks for the assignment.

Partik Dev: Focused on constructing the logic for interpreting mutex locks and semaphores. For instance, Partik constructed the logic structure of when students would enter be able to enter the room, when students would be able to seat outside, and when students would need to leave the and return later. Along with the student semaphore logic, Partik constructed the logic for the TA semaphore which would help notify when the TA should help students and when the TA would go back to sleep. Finally, Along with creating the logic Partik would define variables, mutex locks, and semaphores in the code. 

Gurmandeep Johal: Focused on implementing and putting together the structure of the code. Gurmandeep would implement the functions involving the routine of the student and the TA. Gurmandeep constructed the code of the main function and the random sleep function to allow time in between each thread that is processed. Additionally, Gurmandeep designed the output to be user friendly and easier user readability for the user. 

Both group members worked together on testing, debugging, and finalizing the code for submission.
