## SAS STATEMENTS

A SAS statement is a type of SAS language element that is used to perform a particular
operation in a SAS program or to provide information to a SAS program. SAS
statements are free-format. This means that they can begin and end anywhere on a line,
that one statement can continue over several lines, and that several statements can be on
the same line. Blank or special characters separate words in a SAS statement.

**TIP** You can specify SAS statements in uppercase or lowercase. In most situations,
text that is enclosed in quotation marks is case sensitive.
Here are two important rules for writing SAS programs:
- A SAS statement ends with a semicolon.
- A statement usually begins with a SAS keyword.

There are two types of SAS statements:
- statements that are used in DATA and PROC steps
- statements that are global in scope and can be used anywhere in a SAS program
    *TITLE, LIBNAME, OPTIONS, and FOOTNOTE.*
    
    
**SAMPLE SAS DATA**

data sasuser.admit2;<br/>
set sasuser.admit;<br/>
where age>39;<br/>
run;<br/>
proc print data=sasuser.admit2;<br/>
run;<br/>
