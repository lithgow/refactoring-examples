Start refactoring by searching for repeating code.

In our case this is code for increasing salaries, which is differentiated only by the increase coefficient.

Create a new method with the parameter to which we will send the salary increase coefficient.

Replace the repeating code with calls to our method with the correct parameter.

Get rid of "lazy" methods that only delegate to the method with parameter.

First find all their calls and replace them with calls of the method with parameter.

After the changes are complete, you can remove the methods themselves.

Let's start the final testing.

Now refactoring is complete. If you like, you can compare the old and new code.