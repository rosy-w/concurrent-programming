Program to demonstrate the Sleeping Barber Problem
N customers can sit in waiiting room
waiting room is finite size
when inactive, the barber sleeps
If barber is sleeping, the customer should wake him
If there is no more space in the queue/waiting room, the customer leaves

Issues that can be demonstrated:
- Livelock/Overutilization - barber is chatty/preoccupied with sth while trimming the client and ends up taking too much time yet the queue is growing
- Underutilization - there are no customers and barber stays asleep

Notes:
- queue.task_done lets workers say when a task is done. Someone waiting for all the work to be done with Queue.
- has a bug where it loops on the last function.
- change the euro sign in the last print stmt to "Barbers payment total:" due to an error that arose in my terminal for being non-utf-8.
- ignore the error on Earnings in case it occurs. Works okay on local Visual Studio
