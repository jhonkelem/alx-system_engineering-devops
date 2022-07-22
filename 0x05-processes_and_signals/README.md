Processes and Signals
This project contains Shell tasks for learning about Linux processes and signals using bash.

Tasks To Complete
 0. What is my PID
0-what-is-my-pid contains a Bash script that displays its own PID.
 1. List your processes
1-list_your_processes contains a Bash script that displays a list of currently running processes.
 2. Show your Bash PID
2-show_your_bash_pid contains a Bash script that displays lines containing the bash word.
 3. Show your Bash PID made easy
3-show_your_bash_pid_made_easy contains a Bash script that displays the PID, along with the process name, of processes whose name contain the word bash without using ps.
 4. To infinity and beyond
4-to_infinity_and_beyond contains a Bash script that displays To infinity and beyond indefinitely and sleeps for 2 seconds in each iteration of the loop.
 5. Don't stop me now!
5-dont_stop_me_now contains a Bash script that stops a 4-to_infinity_and_beyond process using kill.
 6. Stop me if you can
6-stop_me_if_you_can contains a Bash script that stops a 4-to_infinity_and_beyond process without using kill or killall.
 7. Highlander
7-highlander contains a Bash script that displays To infinity and beyond indefinitely, sleeps for 2 seconds in each iteration of the loop, and displays I am invincible!!! when receiving a SIGTERM signal.
67-stop_me_if_you_can is a copy of the 6-stop_me_if_you_can Bash script that kills the 7-highlander process instead of the 4-to_infinity_and_beyond process.
 8. Beheaded process
8-beheaded_process contains a Bash script that kills the process 7-highlander.
 9. Process and PID file
100-process_and_pid_file contains a Bash script that:
Creates the file /var/run/myscript.pid containing its PID.
Displays To infinity and beyond indefinitely.
Displays I hate the kill command when receiving a SIGTERM signal.
Displays Y U no love me?! when receiving a SIGINT signal.
Deletes the file /var/run/my.pid and terminates itself when receiving a SIGQUIT or SIGTERM signal.
 10. Manage my process
manage_my_process contains a Bash script that indefinitely writes I am alive! to the file /tmp/my_process and sleeps for 2 seconds in each iteration of the loop.
101-manage_my_process is a Bash script that manages manage_my_process.
When passing the argument start:
Starts manage_my_process.
Creates a file containing its PID in /var/run/my_process.pid.
Displays manage_my_process started.
When passing the argument stop:
Stops manage_my_process.
Deletes the file /var/run/my_process.pid.
Displays manage_my_process stopped.
When passing the argument restart:
Stops manage_my_process.
Deletes the file /var/run/my_process.pid.
Starts manage_my_process.
Creates a file containing its PID in /var/run/my_process.pid.
Displays manage_my_process restarted.
Displays Usage: manage_my_process {start|stop|restart} if any other argument or no argument is passed.
 11. Zombie
102-zombie.c contains a C program that creates 5 zombie processes and displays Zombie process created, PID: ZOMBIE_PID for every zombie process created.
