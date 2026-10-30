RESISTOR COMBINATION CALCULATOR

What It Does

This Python program asks the user how many
resistors they have and collects each
resistance value in ohms. It then calculates
and displays the equivalent resistance when the
resistors are connected in series and when they
are connected in parallel.

How to Run It

Install Python 3, then run:

python resistor_calculator.py

Sample Output

============================================================
           RESISTOR COMBINATION CALCULATOR
============================================================
Enter all resistor values in ohms.

How many resistors do you have? 3
Enter resistor 1 value (ohms): 100
Enter resistor 2 value (ohms): 220
Enter resistor 3 value (ohms): 330

RESULTS 
Resistor values: [100.0, 220.0, 330.0]
Series total:      650.000 ohms
Parallel total: 56.897 ohms
Difference:     593.103 ohms
Check: The parallel total is correctly less
than the smallest resistor.

Thank you for using the calculator.

My Own Twist

I added automatic unit formatting so large
resistance values can be displayed in ohms,
kOhms or MOhms. I also added a comparison
feature that shows the difference between the
series and parallel totals and checks whether
the parallel result is less than the smallest
resistor.

What I learned

I learned how to use functions, lists, loops
and decisions together in one useful program. I
also learned how to validate user input so that
wrong entries do not immediately crash the
program.

Author

Eze Emmanuel Chukwuebuka, ND2 Mechatronics Engineering,
YabaTech.
