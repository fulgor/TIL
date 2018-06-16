# Get Days of February in Python

This is how you find out how many days February has in a given year.

* Method: `monthrange()`
* in: year and month
* out: array with the weekday of first day and the number of days of the month
* Syntax: calendar.monthrange(year,month)

**Example**

    > import calendar
    > print(calendar.monthrange(2018,2))
    > (3, 28)

**Days of February only**

    > print(calendar.monthrange(2018,2)[1])
    > 28

Hint: Index of array starts with 0.
