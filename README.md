# Lab 7
## Section A

### Question 1
Consider a program for determining the previous date. Its input is triple of day, month and year with the following ranges 1 <= month <= 12, 1 <= day <= 31, 1900 <= year <= 2015.The possible output dates would be previous date or invalid date. Design the equivalence class test cases?

### Answer 1
Equivalence class testing is a testing technique that helps identify representative input values for testing. It involves dividing the input domain into a set of equivalence classes, where each class contains a set of input values that are expected to behave in the same way. For the given problem of determining the previous date, the following equivalence class test cases can be considered:

* Valid input:
  * A valid input date with day, month, and year within the given ranges.
  * Example: 10/04/2023

* Invalid input:
  * An invalid input date with day, month, or year outside the given ranges.
  * Example: 35/04/2023, 10/13/2023, 10/04/1000

* Leap year:
  * A valid input date in a leap year.
  * Example: 29/02/2024

* Non-leap year:
  * A valid input date in a non-leap year.
  * Example: 28/02/2023

* First day of the month:
  * A valid input date with the first day of the month.
  * Example: 01/04/2023

* Last day of the month:
  * A valid input date with the last day of the month.
  * Example: 30/04/2023

* Invalid day of the month:
  * An invalid input date with a day outside the range for that month.
  * Example: 31/04/2023

* Invalid February date:
  * An invalid input date with a day greater than 28 or 29 (in a leap year) for February.
  * Example: 30/02/2023

* Boundary test:
  * Input dates on the boundary of the input range.
  * Example: 01/01/1900, 31/12/2015

By testing these equivalence class test cases, we can ensure that the program handles all possible input scenarios correctly.

