The aim of this task is to develop a C vending machine simulator. The program must include a number of
user-defined functions; it should not make use of arrays, pointers or C-structs.
For simplicity, we assume that the vending machine has 3 products only, named ‘A’, ‘B’, and ‘C’. For each
product, we associate its price (a real value) and the number of its items in the machine. The program
should define:
• an integer admin password variable: password.
• a constant value: Min; when the quantity of any product in the machine becomes less or equal
to Min, an alert should be sent to the vending machine operator.
• a real-value variable total_amount which gives the total amount of sale since last reset.
In the following, we assume all user inputs are valid; any printed value should occupy a field of 8 spaces;
left aligned, with 2 fractional precision when applicable.
