# Polyclinic database
This is a project aiming to demonstarte my database modelling and SQL skills.

In the project, I **build a database** for a regular Russian polyclinic (no worries though, only tables' data are in Russian) and perform complex **SQL-queries to gain data** that could be used **for analysis**.

## Description
The database is designed for an imaginery polyclinic, assuming it'd be used in their information system. 

<img align="center" src="https://github.com/Azidalus/Polyclinic-database/assets/93527942/8f7a9362-f97d-4b87-9c27-1e4b03a6955b" width=50% height=50%>

The polyclinic has several branches (in the DB they're called *Parts*). Each one has regular doctors (table *Doctors*), and one head doctor who's in charge of that part. Each branch provides services to only specific addreses that are "linked" to that branch. This concept is represented by tables *PartsStructure* ans *ResponsibleForPart*. 

Patients make appointments (table *Appontment*) to doctors. An appointment can be either a regular consultation with a doctor (table *Visits*) or passing a test (table *Analyzes*), which there're various types (table *AnalyzesType*). 

Finally, there's a table with doctors' schedule, displaying working days of the doctors and a cabinet where you can find them.


