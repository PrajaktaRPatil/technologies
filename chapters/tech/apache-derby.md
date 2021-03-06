## Apache Derby :o:  :hand:   :smiley:   fa18-523-66


|          |                      |
| -------- | -------------------- |
| title    | Apache Derby         | 
| status   | 10                   |
| section  | SQL and SQL Services |
| keywords | SQL and SQL Services |



Apache Derby is java based relational database
system [@www-apachederby]. Apache Derby has JDBC driver which can
be used by Java based applications. Apache derby is part of the Apache
DB subproject and licensed under Apache version 2.0.

Derby Embedded Database Engine is the database engine with JDBC and
SQL as programming APIs.  Client/Server functionality is achieved by
Derby network server, it allows connection through TCP/IP using DRDA
protocol [@www-apachederbycharter]. ij, database utility makes it
possible for SQL scripts to be run on JDBC database. The dblook
utility is the schema extraction tool. The sysinfo utility is used for
displaying version of Java environment and Derby.

There are two deployment options for Apache Derby, embedded and Derby
network server option. In embedded framework, Derby is started and
stopped by the single user java application without any administration
required. In the case of Derby network server configuration, Derby is
started by multi user java application over TCP/IP. Since Apache Derby
is written in Java, it runs on any certified JVM (Java Virtual
Machine) [@www-derbymanual].


#### Apache Derby Summary (Ritu Sanjay  fa18-523-66)

Relational database systems have long been popular among developers to
store data. It popularity stems from the fact that information between
various tables can be linked together using keys that uniquely
identify any atom in a table. Not to mention that RDBMS provide easy
to manage data. Examples of RDBMS include MS SQL, Oracle, Derby etc.

Wikipedia would describe Derby as follows

> "Apache Derby (previously distributed as IBM Cloudscape) is a
>  relational database management system (RDBMS) developed by the
>  Apache Software Foundation that can be embedded in Java programs and
>  used for online transaction processing" [@fa18-523-66-derby-wiki].

Derby is implemented completely in Java. Devices that make use of the
Java Micro edition can take full advantage of Derby, given the fact
that it only leaves about 2MB as footprint for both the embedded JDBC
driver and the base engine. It requires no maintenance (until the
application changes), and hence can be embedded in applications
written in Java, where details are hidden from the user. Derby runs on
most OSs including windows, AIX, solaris, UNIX and Mas OS.

In the famous book Apache Derby - Off to the Races by Zikopoulos,
Baklarz, and Scott (2005), the authors are of the view that

> "not all client/server or Web applications require the muscle of an
>  enterprise-class infrastructure database" [@fa18-523-66-derby-book].

Only about 20–30% of applications actually require RDBMS
capabilities. Furthermore, their hosting environments usually do not
have the system requirements to run full-fledged data engines. Note
that these systems still need robustness and scalability to ensure
data integrity and this is where Apache derby comes in. Another,
benefit of using Derby is that it eliminates the use of a database
administrator. The DB can be managed programmatically from the
application itself [@fa18-523-66-derby-book].

The following scenarios describe instances where Derby could be the suitable choice:

1. Small business client database applications: Eliminating the need
   for a DBA can significantlly reduce costs
2. Local registries and repositories: Since the DB is fully
   transactional, developers need not worry about crashes that can
   destroy configuration files.
3. Small business client/server and Web-based applications: To build
   websites low on maintenance but high on reliability. This ensures that
   businesses have plenty of head room for seasonal spikes.



