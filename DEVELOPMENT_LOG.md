# Development Log

## Instructions
Document your development process as you work on the assignment. Add entries showing:
- What you worked on 
- Problems you encountered
- How you solved them
- Time spent

**Requirements**: Minimum 5 entries showing progression over time.

---

## Example Entry Format:

### Entry 1 - [March 27, 2026, 5:00 PM]
**What I did**: Forked repository and initial setup

**Details**: 
used a university email to create a GitHub account.
successfully forked the starting repository
My name was added to the repository name, and SchedulerSimulation.java's student ID was updated.
ran the software to ensure proper execution

**Challenges**: Understanding initial project structure

**Solution**: Carefully read README.md and assignment instructions

**Time spent**: 3 hours

---

## Your Development Log:

### Entry 1 -  [March 27, 2026, 5:00 PM]
**What I did**: Forked repository and initial setup 

**Details**: used a university email to create a GitHub account.
successfully forked the starting repository
My name was added to the repository name, and SchedulerSimulation.java's student ID was updated.
ran the software to ensure proper execution

**Challenges**:  Understanding initial project structure

**Solution**: Carefully read README.md and assignment instructions

**Time spent**:   3 hours

---

### Entry 2 - [March 27, 2026, 7:00 PM]
**What I did**:Started working on Feature 1 (Process Priority) 

**Details**: Added priority field to Process class
Modified constructor to include priority
Generated random priority for each process
Displayed priority in ready queue output

**Challenges**: Passing priority correctly between classes

**Solution**: Updated constructor and ensured proper parameter passing

**Time spent**: 2hour

---

### Entry 3 - [March 27, 2026, 9:00 PM]
**What I did**:Implemented Feature 2 (Context Switch Counter) 

**Details**:Added static counter variable
Incremented counter before each thread execution
Printed total context switches at the end 

**Challenges**: Determining correct location to increment counter

**Solution**: Placed increment before Thread.start() to reflect actual switches

**Time spent**: 50 minutes

---

### Entry 4 - [March 27, 2026, 10:00 PM]
**What I did**: Worked on Feature 3 (Waiting Time Tracking)

**Details**: Added arrivalTime and waitingTime variables
Calculated waiting time using System.currentTimeMillis()
Implemented getter methods for encapsulation
Displayed summary table at the end

**Challenges**:Calculating waiting time accurately 

**Solution**:Used timestamps before and after execution 

**Time spent**: 1.5 hours

---

### Entry 5 -  [March 28, 2026, 8:00 PM]
**What I did**: Testing and debugging

**Details**: Ran simulation multiple times
Verified output correctness
Ensured all features work together
Fixed minor formatting issues

**Challenges**: Ensuring all features integrate without breaking original logic

**Solution**: Tested incrementally after each feature

**Time spent**: 2 hour

---

### Entry 6 - [March 28, 2026, 10:00 PM]
**What I did**: Testing and debugging

**Details**  Ran simulation multiple times
Verified output correctness
Ensured all features work together
Fixed minor formatting issues: 

**Challenges**: Ensuring all features integrate without breaking original logic

**Solution**: Tested incrementally after each feature

**Time spent**: 1hour

---

## Summary

**Total time spent on assignment**: 2 days

**Most challenging part**: Implementing waiting time calculation

**Most interesting learning**: Understanding thread lifecycle and scheduling

**What I would do differently next time**: Start earlier and test more frequently
