# Three-Google-Papers
Three google papers pioneer the Big data era

**Summary**


**GFS**:

In 2003, Google released the Google File System, which is an extensible large distributed file system for accessing large amounts of data. It runs on low-cost hardware to provide high fault tolerance. Summary: The file is split into a lot of blocks, stored on the commercial machine cluster using a redundancy manner.

**MapReduce**:

In 2004, Google released the Map Reduced algorithm which is developed based on GFS. This paper describes the distributed computing method of big data. The main idea is to decompose tasks and process them simultaneously in several computing nodes with weak processing capacity, and then combine the final results to complete big data processing.

**BigTable**:

in 2006, Google released the Big Table system. The emergence of the Big table triggers the development of the NoSQL database. In the previous Relational Database, the data can be stored in different tables using the manner of columns and rows and should abide by the I, II, III normalisation form to reduce the data redundancy. But the idea of the Big Table is to store all data into one big table by sacrificing the spatial to exchange the response time.