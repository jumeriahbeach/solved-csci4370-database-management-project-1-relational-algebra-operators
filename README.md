Download Link: https://assignmentchef.com/product/solved-csci4370-database-management-project-1-relational-algebra-operators
<br>
Implement the following relational algebra operators:

<u>Select, Project, Union, Minus </u><u>and Join</u>.

Some of the operators are partially implemented in Table.java (at ELC) and what you need to do is to fully implement those operators. Tuples are stored in comparable lists (ArrayList). You can see some test cases in the main function of Table.java; however, since functions are partially implemented, it will not give the proper output. So, you should be able to see the desired output after the completion of implementation. Download the starter source code from the ELC and compile it. Upon making sure that it is working properly, you can start implementing. If you compile and run MovieDB.java, you will see the tables retrieved based on the queries, which uses partially implemented operators.

Every operator has a method to be implemented and those methods have other methods to be called and to be implemented. So, it may require implementing more than one method to complete an operator. While implementing, also pay attention to the domain (data types) since this could be important to be able to implement some of the operators. The methods may have some parts to be deleted or uncommented right after the implementation; so, please read comments within the code.

Union operator will simply merge the two tables (except the duplicate tuples in intersection). Minus operator will output the tuples that do not exist in the second table. Project operator will retrieve the elements based on the column positions. For Select, data type conversion is important (in String2Type.java). Join combines tuples from two tables. Furthermore, you need to make comparisons per the conditions given in the query (postfix).

Use a (Java) TreeMap for an index.

Your program must be thoroughly documented (generate javadoc). Use the @author tag for each class and method. Each method should have a single author. The coding workload should be split roughly among 4 team-members. We will check this by examining the @author tags and peer evaluations. Please make sure that the output of your program is easy to understand. Provide a flag for turning on/off your tracing/debugging messages in your program’s output – if necessary.







<strong>Files Description: </strong>

<ol>

 <li><strong>java: </strong>This file contains Table class which implements relational database tables. Five basic relational algebra operators are provided: project, select, union, minus and join as functions (partially implemented). The insert data manipulation operator is also provided. Missing are update and delete manipulation operators. Implement the code in this file where you find “// TO BE IMPLEMENTED”.</li>

 <li><strong>java: </strong>This file contains KeyType class which provides a key type for handling both non-composite and composite keys. A key is a minimal set of attributes that can be used to uniquely identify a tuple. Do not make any changes to file.</li>

 <li><strong>java:</strong> Concatenate two arrays to form a new wider array. Do not make any changes to this file.</li>

 <li><strong>java:</strong> This file contains MovieDB class which generates a <u>Movies database</u>, which will be used to evaluate the 5 relational algebra operators implemented by you in Table.java class. Do not make any changes to this file.</li>

</ol>

<strong>Rubric: </strong>Please find the rubric for Project 1 for point distribution and project expectations.

<strong>Programming language:</strong> Java is required for the project.

<strong>What to submit:</strong> Please submit

<ul>

 <li>all source code</li>

 <li>all the javadoc files</li>

 <li>a readme file</li>

</ul>

The readme file should contain: your names, how to compile and run your code and other specifications you want to make. Please pack all your files in a zip package with the file name: “project1_groupName”. For example: project1_dbDesigners.zip





