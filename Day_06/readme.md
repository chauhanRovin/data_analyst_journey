# Loops
   Loops are used to execute a block of code repeatedly until a condition is met or all items in a sequence are processed. The main types     are For loops and While loops.

 # For loop
   For loops is used to iterate over a sequence such as a list, tuple, string or range. It executes a block of code once for each item in     the sequence. 
   Example:
   n = 4
   for i in range(0, n):
    print(i)

  # While loop
   While loop repeatedly executes a block of code as long as the given condition remains true. When the condition becomes false, the line     immediately after the loop in the program is executed.
   Example:
   count = 0
   while (count < 3):
    count = count + 1
    print(count)

  # Nested Loops
   A nested loop is a loop inside another loop. The inner loop executes completely for every iteration of the outer loop.
   Example:
   for i in range(1, 5):
    for j in range(i):
        print(i, end=' ')
    print()
