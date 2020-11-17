# SwiftPlot
A (graphical) modelling app 

After a school assignment with a somewhat broken modelling application, I decided to build my own STABLE application. And it is big fun! 
There's still a lot that needs to be done, to make it fool proof. If you're not a fool, then it's safe and quick and runs on iPad and Mac.

# Usage
Press the plus button to add functions and formula's. 
You've to break them down in multiple parts with 2 inputs and one output: v = v + a * dt should become anew = a * dt, v = v + anew. 
These formula's will be visible in order of execution in the menubar.
It's important to always have an tstop and a t! when t >= tstop the model wil stop execution. When not present, the model will run indefinitely.


Make a model:
- press +
- create a new execution block formula: write an execution and press add. Is the block done? press save.
- press check variables
- set all the variables that should have a start value. Reminder: t must reach tstop or the model will run forever!
- press run
- now it's time to plot


When it's time to plot:
- set the x-axis
- set the y-axis
- press plot
