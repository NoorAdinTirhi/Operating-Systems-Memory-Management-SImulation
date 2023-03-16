# Operating-Systems-Memory-Management-Simulation

Operating Systems Memory-Processes Simulator, Simulates a Round Robin Processes Schedueler and multiple types of Page Replacement

# Scheduler
![Untitled Diagram](https://user-images.githubusercontent.com/115925101/225583511-d177a891-d8f3-4e57-ab60-b829f67df542.png)

# Page Repalcement

-FIFO : look into all processes with more frames than the minimum, compare all their pages, then remove the page from with the least brought time.

-Least Recently Used : look into all processes with more frames than the minimum, check the last use time of all frames, remove the frame that has the earliest use time

-Second Chance : look into all frames with more frames than the minimum, look into a frame, if its marked for removal, remove it, otherwise mark it for removal


