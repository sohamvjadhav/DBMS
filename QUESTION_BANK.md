# Question Bank (DBMS)

## Unit 3 (Q1 & Q2)

**Q1.** What is decomposition? Consider the relation F (FN, PN, C, D) with the following Functional Dependencies: FD1: FN, PN ->C FD2: C ->D FD3: D -> F If F is decomposed in to F1 (FN,PN,C) and F2 (C,D). check decomposition is lossless or lossy?

**Q2.** Explain 2NF and 3NF and BCNF with example.

**Q3.** Explain partial, full and transitive dependency with examples. **(Repeated 2 times)**

**Q4.** Explain entity and referential integrity constraints used in SQL.

**Q5.** Define 3NF. Explain with example, how to bring the relation in 3NF?

**Q6.** Explain 3NF and BCNF and give its example. Also enlist their differences. **(Repeated 2 times)**

**Q7.** What are the desirable properties of decomposition? Explain it with example. **(Repeated 2 times)**

**Q8.** Elaborate the significance of codd s rule. Explain 12 rules proposed by codd s. **(Repeated 3 times)**

**Q9.** What is anomaly in relational model. Explain how normalization can be used to reduce the anomalies.

**Q10.** Justify the impact of normalization on database? Explain 2nd normal form, 3rd normal form and BCNF with example.

**Q11.** What are relational integrity constraints. Explain with example Domain constraints, Referential-Integrity and enterprise constraints.

**Q12.** Explain following Codd s rules with suitable examples : i) Physical Data Independence ii) Integrity Independence iii) Systematic Treatment of NULL Values

**Q13.** Explain following Codd s rules with suitable examples : i) Guaranteed Access Rule ii) Comprehensive Data Sub-Language Rule iii) High-Level Insert, Update, and Delete Rule

**Q14.** Explain following Codd s rules with suitable examples: i) Guaranteed Access Rule ii) Comprehensive Data Sub-Language Rule iii) Integrity Independence iv) Systematic Treatment of NULL Values.

**Q15.** Explain different features of good relational database design.

**Q16.** What is the impact of insert, update and delete anomaly on overall design of database? How is normalization used to remove these anomalies? **(Repeated 4 times)**

**Q17.** Explain why database normalization is required for good relational database design? Explain with example requirements of different normal forms like 1NF, 2 NFand 3NF.

**Q18.** What is functional dependency? Explain its use in database design. Consider the following schema. Student (RollNo, Branch_code, Marks_Obtained, Exam_Name, Total_Marks) Identify the functional dependencies and check whether the given schema is in 3NF or not. If not justify and convert the schema into 3NF.

---

## Unit 4 (Q3 & Q4)

**Q19.** Write a short note on : i) Log based recovery ii) Shadow Paging

**Q20.** What is R-timestamp(Q) and W-timestamp(Q) Explain the necessary condition used by time stamp ordering protocol to execute for a read / write operation. **(Repeated 2 times)**

**Q21.** During execution, a transaction passes through several states, until it commits or aborts. List all possible sequence of states through which transaction may pass. Explain the situation when each state transition occurs.

**Q22.** Suppose a transaction T i issues a read command on data item Q.How time-stamp based protocol decides whether to allow the operation to be executed or not using time-stamp based protocol of concurrency control. Explain in detail time stamp based protocol.

**Q23.** Suppose a transaction T i issues a read command on data item Q. How time-stamp based protocol decides whether to allow the operation to be executed or not using time-stamp based protocol of concurrency control. Explain the situations when each state transition occurs.

**Q24.** State and explain the ACID Properties. During its execution, a transaction passes through several states, until it finally commits or aborts. List all possible sequences of states through which a transaction may pass. Explain the situations when each state transition occurs. **(Repeated 3 times)**

**Q25.** When do deadlocks happen, how to prevent them, and how to recover if deadlock takes place?

**Q26.** How to ensure the atomicity using Recovery Methods? Explain the log based recovery method in detail.

**Q27.** To ensure atomicity despite failures we use Recovery Methods. Explain in detail log based recovery method.

**Q28.** What is conflict serializability? How to check schedule is conflict serializable schedule? Explain with one example. **(Repeated 2 times)**

**Q29.** Explain the two-phase lock protocol for concurrency control. Also explain its two versions: strict two-phase lock protocol and rigorous two-phase lock protocol.

**Q30.** What is recoverable schedule? Why is recoverability of schedule desirable?Are there any circumstance under Which it could be desirable to allow non recoverable schedular? Explain your answer.

**Q31.** To ensure atomicity despite failures we use Recovery Methods Explain in detail following Log-Based Recovery methods with example. i) Deferred Database Modifications ii) Immediate Database Modifications

**Q32.** Explain the concept of conflict serializability with suitable example. Since every conflict-serializable schedule is view serializable, why do we emphasize conflict serializability rather than view serializability? **(Repeated 2 times)**

**Q33.** A transaction may be waiting for more time for an Exclusive (X) lock on an item, while a sequence of other transactions request and are granted as Shared (S) lock on the same item. What is this problem? How is it solved by two phase lock protocol?

**Q34.** What is conflict serializability? Check following schedule is conflict serializable or not? Also, explain the concept of conflict equivalent schedule. T1 T2 T3 T4 R(X) R(Z) W(X) R(Y) W(Y) W(X) W(Y) W(Z) R(X) denotes read operation on data item X by transaction Ti. W(X) denotes read operation on data item X by transaction Ti.

**Q35.** Consider the following two transactions: T31: read(A); read(B); if A = 0 then B:=B+1; Write (B) T32: read(B); read(A); if B= 0 then A: = A+1; write (A). Add lock and unlock instructions to transactions T31 and T32, so that they observe the two phase locking protocol. Can the execution of these transactions result in a deadlock?

**Q36.** Explain two phase locking protocol. Consider the following two transactions. T1 : read (A); read (B); if A = 0 then B : = B + 1; Write (B). T2 : read (B); read (A); if B = 0 then A : = A + 1; Write (A). Add lock and unlock instructions to transactions T1 and T2, so that they observe the two phase locking protocol. Can the execution of these transactions result in a deadlock?

**Q37.** Check whether following schedule is view serializable or not. Justify your answer. (Note : T 1 & T2 are transactions). Also explain the concept of view equivalent schedules and conflict equivalent schedule considering the example schedule given below : 1 T2 read (A) A := A 50 read (A) temp :=A * 0.1 A := A - temp write (A) read (B) write (A) read (B) B := B + 50 write (B) B := B + temp write (B)

---

## Unit 5 (Q5 & Q6)

**Q38.** BASE Transactions ensures the properties like Basically Available, Soft State, Eventual Consistency. What is soft state of any system, how it is depend on Eventual consistency property?

**Q39.** State and Explain CAP Theorem.

**Q40.** Compare SQL and NOSQL Database.

**Q41.** Explain Map Reduce with example.

**Q42.** Explain CAP theorem and BASE properties.

**Q43.** Explain BASE Properties of NOSQL Database.

**Q44.** Explain the difference between SQL and NOSQL database.

**Q45.** Explain the CRUD operations used in MongoDB with example.

**Q46.** What is structured and unstructured data. Explain with example.

**Q47.** Explain Document Based and Key value data model of NOSQL Database.

**Q48.** State and explain the concept of CAP theorem and BASE properties with example.

**Q49.** Explain Structured, Semi-structured and Unstructured data types with examples. **(Repeated 2 times)**

**Q50.** Enlist the different types of NOSQL databases and explain with suitable examples.

**Q51.** Describe distributed database. Explain System architecture of distributed transaction.

**Q52.** Explain the CAP theorem referred during the development of any distributed application. **(Repeated 2 times)**

**Q53.** Explain the NOSQL database types with examples and write down the real time applications.

**Q54.** List the different NOSQL data models. Explain document store NOSQL data model with example. **(Repeated 2 times)**

**Q55.** Explain following types of data with example i) Structured ii) Semi-structured iii) Unstructured

**Q56.** Explain BASE properties with its significance. How soft state of system is depending on Eventual consistency property?

**Q57.** Draw and explain architecture of Distributed database system. State the reasons for building distributed database systems.

**Q58.** List the different NOSQL data models. Explain following NOSQL database types with examples. i) Column-oriented ii) Document-oriented

**Q59.** Explain how NOSQL databases are different than relational databases? Describe in detail the key value store NOSQL data model with example.

**Q60.** Explain following NOSQL database types with examples and also state the scenario where it is useful i) Column-oriented ii) Graph iii) Document -oriented

**Q61.** Analyze the use of NOSQL databases in current social networking environment also explain need of NOSQL databases in social networking environment over RDBMS.

**Q62.** Describe the following operations with MongoDB syntax: i) Map-Reduce ii) Aggregation pipeline

---

## Unit 6 (Q7 & Q8)

**Q63.** Write short note on i) Geometric data ii) Geographic data

**Q64.** Write short note on : i) Active databases ii) Deductive databases **(Repeated 2 times)**

**Q65.** What is object relational database? What are its advantages and disadvantages?

**Q66.** Write a short note on emerging databases : i) Active and Deductive Databases ii) Main Memory Databases

**Q67.** Write a short note on complex data types : i) Semi-structured data ii) Features of semi-structured data models **(Repeated 4 times)**

**Q68.** What are spatial data. Explain Geographic and Geometric data.

**Q69.** Describe spatial data like Geographic data and Geometric data.

**Q70.** What is object relational database system. Explain Table inheritance with example. **(Repeated 2 times)**

**Q71.** Difference between relational databases and object relational databases with example

**Q72.** What is the significance of XML databases? Explain with proper example when to use XML database. **(Repeated 4 times)**

**Q73.** What is Deductive Database. Explain its features and state its advantages over traditional database. **(Repeated 2 times)**

**Q74.** Describe the significance of JSON data type and object. Discuss with syntax all JSON data types with suitable example.

**Q75.** Explain how encoding and decoding of JSON object is done in JAVA with example. **(Repeated 3 times)**

---
