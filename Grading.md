# Grading Guide for A Type Projects
* Groups are allowed 10 minutes to present their work.
* Groups are called to present their work based on a random number announced in the class. 
* One person can be a speaker or members can present stages separately in one session.
* All group members are expected in the board while presenting. Absent members will be penalized according to excuse.
* Have all necessary data ("emp.csv", "dept.csv") and image files provided ready in your computer local filesystem as well as proper locations under HDFS or Cassandra.
* Group members help each other to hook their computer to the projector quickly.
* Members (and groups) who are not contributed at all, and do not show up at presentation will get 0 (zero) grade.

<table>
  <header>
    <th>No</th>
    <th>Task (Stage)</th>
    <th>Expeted Outcome (Points)</th>
    <th>Time</th>
    <th>Grade</th>
  </header>
  <body>
    <tr>
      <td>1</td>
      <td>Hadoop-HDFS + Spark Installation.</td>
      <td> a) Show that HDFS is running: Show image files location under HDFS. (20) <br> b) Show spark-shell is working, must show CLI prompt "scala >". (15)</td>
      <td>4 m</td>
      <td>35</td>
    </tr>
    <tr>
      <td>2</td>
      <td>Cassandra Installation.</td>
      <td>a) Show that Cassandra database server is running. Run 'cqlsh >'.  (20) <br> b) Show keyspace. Show 'emp', 'dept' tables at cqlsh. (15)</td>
      <td>3 m</td>
      <td>35</td>
    </tr>
    <tr>
      <td>3</td>
      <td>Java Spring Boot Application interact with Spark.</td>
      <td>a) Show only "emp" table content in the view with images. Data must be fetched through Spark using RDDs, not directly from Cassandra. (15)<br> b) Show full working application with joins as defined in project. Data must be fetched through Spark using RDDs, not directly from Cassandra. (30) </td>
      <td>3 m</td>
      <td>30</td>
    </tr>
    <tr>
      <td colspan="3" align="right">TOTAL</td>
      <td>10 m</td>
      <td>100</td>
    </tr>
  </body>
</table>
