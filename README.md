# CSE634-Pintos
This project is by UNIST CSE364 course, reference by CSCC-69.
In this page, Iwbsph228 & PunishmentBird is teammate for solve this projects.
Our work follow "UNIST CSE Policy on Cheating and Plagiarism".

# Project 1
Main goals: Alarm clock & priority
reference by: GopalKrishna-P

In thread.h -> we add some paremeters for checking out ticks that thread sleeping.
and make two function for our sequence: thread_awake() and thread_sleep().
this functions are running like lock. first, sleep is running and awake function is running soon.
In this version, we use interrupt on/off, but we planning change this algorithm by semaphore or lock.

