- 👋 Hi, I’m @Naveen030224
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...

<!---
Naveen030224/Naveen030224 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
Provided is a list of data about a store’s inventory where each item in the list represents the name of an item, how much is in stock, and how much it costs. Print out each item in the list with the same formatting, using the .format method (not string concatenation). For example, the first print statment should read The store has 12 shoes, each for 29.99 USD.

12/17/2024, 10:14:46 PM - 33 of 33
1
inventory = ["shoes, 12, 29.99", "shirts, 20, 9.99", "sweatpants, 25, 15.00", "scarves, 13, 7.75"]
2
for item in inventory:
3
    item_desc, number, cost = item.split(", ")
4
    print("The store has {} {}, each for {} USD.".format(number, item_desc, cost))
5
​
6
​
7
​
8
​
9
​
Code Coach
Line4: invalid non-printable character U+00A0
    print("The store has {} {}, each for {} USD.".format(number, item_desc, cost))
                                                                           ^
Result	Actual Value	Expected Value	Notes
Pass	'for'	'# Sam...\n\n\n\n\n'	Testing whether your code includes a for loop.
Pass	'.format('	'# Sam...\n\n\n\n\n'	Testing whether your code invokes the .format method.
Fail	'The s...USD.\n'	'The s...USD.\n'	Testing your output.
You passed: 66.66666666666666% of the tests

Error
SyntaxError: bad token T_OP on line 4
Description
This message indicates that Python can't figure out the syntax of a particular statement. Some examples are assigning to a literal, or a function call

To Fix
Check your assignment statements and make sure that the left hand side of the assignment is a variable, not a literal or a function.



