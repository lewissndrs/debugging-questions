* What is the purpose of a breakpoint?
- A breakpoint sets a point where the program will pause so that the debugger can start.

* Does the line of code on a breakpoint run when you start debugging?
- No, it will stop before the line and wait for you to tell the debugger to step.

* How do we debug the next line of code?
- We use the step function and then examine what info the debugger gives about the variables in play.

* What does the step into command do?
- Step over will move to the next line, while step into will take you through any methods called in the line.

* What is the difference between evaluate expression and evaluate code fragment?
-Evaluate expression will run a single line of code at a time. You do not use a semi-colon at the end of an expression in this mode. Evaluate code fragment mode will run several lines of code at once, and requires a semi-colon at the end of each line.