# Big-Data-Architecture

## Architecture

![Big Data Architecture style](/images/1.jpg)

</br>

A big data architecture is designed to handle the ingestion, processing, and analysis of data that is too
large or complex for traditional database systems.

</br>

### Data sources

![Data sources](/images/2.jpg)

</br>
All big data solution starts with one or more data sources.

![data source 1](/images/3.jpg)

Application data stores, such as relational
databases.
Relational database, database in which all data are represented in
tabular form. The description Of a patticular entity is provided by the set
of its attribute values, stored as one row or record of the table, called a
tuple, Similar items from different records can appear in a table column,
The relational approach supports queries that involve several tables by
providing automatic Ijnks across tables. payroll data, for example, can be
stored in one table and personnel benefits data in another; complete
information on an employee can be obtained by joining the tables on
employee identification number. In more powerful relational data models,
entries can be programs, text, unstructured data in the form of binary
large objects (BLOBs), or any other format the user requires. The
relational approach is currently the most popular model for database
management systems


Static files produced by applications, such as web
server log files.
A web server log is a log file (or several files)
automatically created and maintained by a web
sewer consisting of a list of activities it
performed

Real-time data sources, such as IoT devices.
IoT devices are a part of the larger concept of
home automation, which can include lighting,
heating and air conditioning, media and security
systems and camera systems. Long-term
benefits could include energy savings by
automatically ensuring lights and electronics are
turned off or by making the residents in the
home aware of usage.


</br>

### Data storage

![data storage](/images/4.jpg)

Data for batch processing operations is typically stored
in a distributed file store that can hold high volumes of
large files in various formats.
This kind of store is often called a <b>data lake</b>.

Example:

Azure Data lake

Users can store structured, semi-structured or
unstructured data produced from applications
including social networks, relational data,
sensors, videos, web apps, mobile or desktop
devices. A single Azure Data Lake Store account
can store trillions of files where a single file can
be greater than a petabyte in size

blob containers in Azure Storage

A container organizes a set of blobs, similar to a
directory in a file system. A storage account can
include an unlimited number of containers, and a
container can store an unlimited number of
blobs.