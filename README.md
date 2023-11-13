# SWE307-2023
## Due date: 16.11.2023 Thursday, in class.

In this project study, you are asked to create the big data-based information system shown in Figure 1. In the project work, the employee information of the company named "Magic" is stored in the "emp.csv" file on Hadoop-HDFS. The company's department information is stored in the "dept.csv" file. These two files are under the path "/user/hadoop/magic/data". Employee images are under the "/user/hadoop/magic/image" directory. 

**What is required from you is as follows:**

**1)** Hadoop-HDFS will be installed to create a HDFS - Spark pipeline.
<br>
**2)** A simple Java Web application will be developed to perform the following tasks:<br>
	&nbsp;&nbsp;&nbsp;**a)** Employee and department data will be read from CVS files as if reading data from the database (writing operation is not required)<br>
	&nbsp;&nbsp;&nbsp;**b)** Employee images will be taken directly from HDFS.<br>
	&nbsp;&nbsp;&nbsp;**c)** There will be a single web page, on this page the information will be displayed in a table using the JOIN operation on Spark dataset. Information to display: employee name, manager name, salary, commission, department.<br>
	&nbsp;&nbsp;&nbsp;**d)** You implement read and JOIN operations on CSV files provided using Java and Spring-Boot framework. You can develop your data processing part using spark-shell and scripts with Scala (or Python), and copy them to Java program as we did in the class.<br>
<br>
![Project architecture.](SWE307-pro1.png)
<br>
**Figure 1.** Big data based web information system.
<br>
**PS:** Example image files and csv files will be provided on Github repository, you can clone/download everything provided. 
<br>
<br>
**Working example output is shown below:**
<br>
![Expected output.](Screenshot.png)
