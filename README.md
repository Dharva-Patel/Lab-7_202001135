# Lab-7_202001135

Name: Dharva Patel

ID: 202001135

Lab: 07 - Black-box and white-box testing

# Section A

For the program to calculate previous Date, the possible test cases are as follows

Input Data | Expected Outcome
---------- | ---------------
Equivalence Partitioning |
Valid day, Month, and Year | Previous Date
Valid Month, Valid year, day<1 or day>31 | Error Message
Month < 1 | Error Message
Month > 12 | Error Message
Invalid year < 1900 or > 2015 | Error Message
Boundary Value Analysis (DD-MM-YYYY) |
01/01/1900 | 31/12/1989
28/2/1900 | 27/2/1900
29/2/1900 | Error Message
1/5/2000 | 30/4/2000
31/4/2010 | Error Message
31/12/2015 | 30/12/2015

I made 5 distinct JAVA files, file1.java, file2.java, file3.java, file4.java, and file5.java, to test the scripts. The matching function code to be tested is contained in each file.
> Code for doing linear search on an array of integers in file1.java is provided to retrieve the index of a certain number. It returns -1 if fails to locate.

linearSearch(int v, int[] a)

