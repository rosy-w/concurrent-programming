This example uses _thread to start threads that execute asynchronously. 

Note that there are time.sleep calls to increase the probability that all threads will complete prior to the test harness exiting, though this is not guaranteed.  

Run:
1. pip3 install -r requirements.txt, which will install the libraries required
2. python3 start_new_thread_example.py -n 3, which in this case will cause 3 threads to be started. Can add more threads by modifying the -n arguments in the command line.
