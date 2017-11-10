# DaemonTester
This projects shows how to properly inject data into an simple tester that follows the following abstraction: It gets the program, the args to run it with, the actions to perform and what to expect, all from the json file at /config

I created this repository to show how the use of closures in Python can help code legibility, as a way to avoid comments.

The use of timeouts and piping of the program output allows for runtime-testing in languages that have runtime errors, like C. The problem with CUnit in this specific case was that it needed functions to run and test, and the code I made this framework for did not have them. Only one big main with a while loop. 

