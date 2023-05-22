This uses the Python 3 threading library to create a semaphore (configured as either a binary or multiple use based on CLI arguments) 

Threads independently use the semaphore to lock execution of a "critical" section of code. 

Feel free to modify numbers of threads and how many threads can hold the semaphore at the same time, to see the various effects this can have. 

Run:
  1. pip3 install -r requirements.txt
  2. python3 threading_semaphore_example.py -n 3 -s 1, which in this case will cause 3 threads to be started and only one thread can access the critical section of code.
