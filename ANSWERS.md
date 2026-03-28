# Assignment Questions

## Instructions
Answer all 4 questions with detailed explanations. Each answer should be **3-5 sentences minimum** and demonstrate your understanding of the concepts.

---

## Question 1: Thread vs Process

**Question**: Explain the difference between a **thread** and a **process**. Why did we use threads in this assignment instead of creating separate processes?

**Your Answer: A thread is a smaller unit of execution within a process that shares memory, whereas a process is an independent program in execution with its own memory space. Compared to threads, processes are more costly to develop and maintain. Because they share resources within the same process, threads enable speedier communication. Because threads are lightweight and effective at imitating numerous processes, they were used in this task. Separate procedures would result in needless complexity and overhead.**

[Write your answer here. Consider: What is a process? What is a thread? How do they differ in terms of memory, resources, creation overhead? Why are threads more suitable for this simulation?]

---

## Question 2: Ready Queue Behavior

**Question**: In Round-Robin scheduling, what happens when a process doesn't finish within its time quantum? Explain using an example from your program output.

**Your Answer: A process in Round-Robin scheduling is pushed to the end of the ready queue if it does not complete within its time quantum. This ensures fairness by granting CPU time to other programs. When its turn in the line arrives, the process will be carried out once more.

An example of what I produced

P1 finished quantum in 5000 ms.
Time left: 6609 ms
P1 provides the CPU for the context switch.
P1 is now in the ready queue.

An explanation of the example

This output demonstrates that process P1 did not complete within the allotted quantum. As a result, it returned to the ready queue after yielding the CPU. This guarantees scheduling fairness by allowing other processes to run before P1 has another opportunity.**

[Write your answer here. Describe the specific behavior - where does the process go? When does it run again? Give an example from your actual program output showing a process that was re-queued.]

Example from my output:
```
[Paste a relevant snippet from your program output here showing a process being re-queued]
```

**Explanation of example:**
[Explain what's happening in the output snippet you pasted]

---

## Question 3: Thread States

**Question**: A thread can be in different states: **New**, **Runnable**, **Running**, **Waiting**, **Terminated**. Walk through these states for one process (P1) from your simulation.

**Your Answer: New: When the Thread object is created but not yet begun, P1 is in the New state.
Runnable: When Thread.start() is called, P1 enters the Runnable state, preparing it for execution.
Running: When the CPU runs its run() method within its time quantum, P1 is in the Running state.
Waiting: When Thread, P1 goes into the Waiting state.The main thread calls join(), which makes the scheduler wait for P1 to complete its execution.
Terminated: When P1's remaining time is zero and it has finished executing, it enters the Terminated state.**

[Write your answer here. For each state, explain when P1 enters that state during the simulation. Use your understanding of the code to trace through the lifecycle.]


---

## Question 4: Real-World Applications

**Question**: Give **TWO** real-world examples where Round-Robin scheduling with threads would be useful. Explain why this scheduling algorithm works well for those scenarios.

**Your Answer: First example: Web server

An explanation:
A web server uses threads to manage several client requests at once.

Why Round-Robin is effective in this situation:
Round-Robin makes sure that each request receives an equitable amount of CPU time. It keeps the server from being monopolized by a single request. This enhances responsiveness and guarantees effective service for all users.**

### Example 1: [Name of application/scenario]

**Description**: Description:
Operating systems manage multiple applications running at the same time.
[Describe the real-world scenario or application]

**Why Round-Robin works well here**: Every process receives an equal amount of CPU time thanks to round-robin scheduling. It prevents starvation and keeps the system responsive. In time-sharing systems where numerous people interact with the system, this is particularly helpful.
[Explain why Round-Robin scheduling is suitable. Consider fairness, responsiveness, predictability, etc.]

### Example 2: [Name of application/scenario]

**Description**: Operating systems manage multiple applications running at the same time.
[Describe the real-world scenario or application]

**Why Round-Robin works well here**: Every process receives an equal amount of CPU time thanks to round-robin scheduling. It keeps the system responsive and avoids hunger. In time-sharing systems where numerous people interact with the system, this is particularly helpful.
[Explain why Round-Robin scheduling is suitable. Consider fairness, responsiveness, predictability, etc.]

---

## Summary

**Key concepts I understood through these questions:**
1. Difference between threads and processes
2  Round-Robin scheduling behavior
 3 Thread lifecycle states

 

**Concepts I need to study more:**
1. Advanced synchronization techniques
2. Deadlock handling
