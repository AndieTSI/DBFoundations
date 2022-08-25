Assignments for IT FDN 130 A Su 22
<Foundations Of Databases & SQL Programming> 
(University of Washington)

Assignment 07   
August 24, 2022

<H1>Using and Creating Functions</H1>

<H2>Introduction</H2>
SQL Server has numerous built-in functions (external link). These mini-programs can save you time and help you modify, manipulate, and query data to get the results you need. 
<H2>When to Use SQL User-Defined Functions (or UDFs)</H2>
In addition to the many built-in options, most relational database management systems will let you create your own functions. These are great when you need to create special reports and run the same type of query repeatedly. They may also be used for creating custom check constraints on new data that is added. 
<H2>Scalar, Inline, and Multi-Statement Functions</H2>
Using the parameters selected, functions can be written to return either single values (scalar functions) or tables of data (table-valued functions). For the table-valued functions there are two types, inline and multi-statement. An inline table-valued function is the most basic, as it has a single SELECT statement in the body of the program. A multi-statement table-valued function, on the other hand, has more than one SELECT statement in the body, and it also requires a BEGIN and END block. 
<H2>Summary</H2>
In summary, there are multiple SQL functions available to help you find, format and report the data you need. However, if you have more complex reporting needs, you may create your own! 
