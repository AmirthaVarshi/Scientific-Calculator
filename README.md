Scientific Calculator

The program has 2 classes. A simple calculator class called Calculator, and a class that inherits Calculator called Scientific.

Some of the member functions of Calculator are virtual and are overridden in the Scientific class.

The program polymorphically calls the appropriate member functions depending on the current mode (scientific vs simple).

The program flow is:
1. Prompt user for the desired operation (polymorphically determine the message based on the current mode; show more options while in scientific mode)
2. Get additional data from the user (if doing addition, get 2 numbers)
3. Perform calculation, print to screen
4. Repeat from (1)
