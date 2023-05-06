This demonstrates the dining philosophers problem.
This solves deadlock as it prevents waiting for a fork when a philosopher has one in hand. 
If the philosopher has the right fork but can't get the left fork, they release the right fork and then wait to now get the left fork, which now becomes his first fork.
Keep retrying and swapping the fork pickup order until they get both.
