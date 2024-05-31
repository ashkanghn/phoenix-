computer organizaition - spring 2024

## iran university of science and technology
## project1

name: ashkan ghaseminezhad
team member: pooria masoomi
student id : 400414093

## report
for square root code
the steps are :

Load n (144) into register x4.
Initialize lo (low bound) to 0 in register x5.
initialize hi (high bound) to n (144) in register x6.

Compute the midpoint mid as (lo+hi)/2
(lo+hi)/2 and store it in x7.
Calculate mid^2 and store it in x8.
Check if mid^2 is equal to n. If so, jump to done.
If mid^2 is less than n, adjust lo to mid + 1 and jump back to the start of the loop.
If mid^2 is greater than n, adjust hi to mid - 1 and check if the loop should continue.

The ebreak instruction is used to exit the program, which may need to be replaced by an actual exit system call depending on the execution environment.\



## report 2
