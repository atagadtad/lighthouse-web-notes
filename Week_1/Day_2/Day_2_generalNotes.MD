# Day 2
### Morning Lecture
* ask for code reviews, even if you're finished
* take complex problems and simplify, generalize and dumb down to better understand
#### Chronal Calibration
* in the readme file, he wrote simplified beginning steps to tackle the problem:
1. find the initial number
2. get the bunch of numbers
3. add up all the numbers
4. * start with the 1st number, keep track of numbers and return the numbers 

Always be commiting your work. Use good descriptions to keep track of what you're doing. 
* beings to play around in node. working through the data and giving a sense of confidence that we're moving
* using the node within the terminal as a playground, to find small workable solutions in navigating through the information

```javascript
for (element of bunch.slice(2)) {
  calibration = calibration + parseInt(element)
}
```
* scope of the element within the for loop is scoped within the for loop!
* the "for of loop" is easier to read ^^
* use the console.log within functions and bits of code to 'x-ray' and find out what's going on 
* DEBUG with the console.log function
* then refactor and see where you can clean up the code!
* declare variables as CLOSE as they can be to WHERE they'll be used, apply inner scope 
* comment out old code/copied code so you can follow your past decisions and see where you may have gone wrong
* AVOID GLOBAL VARIABLES!

```javascript
data.split('/n')
```
* he took a bunch of numbers that we wanted to convert into an array, without the new line

## Summary
* go into the playground and experiment to see what works and doesn't work
* build confidence
* apply debugging techniques (console.log)
* one that worked, rafactored, and one that actually worked with the data
* make sure that every time you refactor you have an anchor to see that it's continue to work!
