# Assignment 5: Basics of Interprocess Communication (Cat. ID 22)


## Race Condition
A race condition describes a scenario where two processes try to access and/or change the same shared data at the same time. This could lead to several problems, e.g. the second process overwrites the data set by the first one.


## Disabling interrupts
### Why is it impossible to achieve Mutual Exclusion via disabling interrupts on a multi-core machine?

### Why is it dangerous to give user processes the power to disable interrupts?


## Peterson's Solution
### Document the two scenarios of the handout

### Document the fail-scenario of strict alternation

### What does the "loser" variable mean and when does it have any effect?

### Extend the given functions for handling the processes